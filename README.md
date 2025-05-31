<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    .tab-container {
      display: flex;
      background-color: #333;
      overflow: hidden;
    }

    .tab-button {
      background-color: inherit;
      border: none;
      outline: none;
      cursor: pointer;
      padding: 14px 20px;
      color: white;
      transition: background-color 0.3s;
      flex-grow: 1;
    }

    .tab-button:hover {
      background-color: #575757;
    }

    .tab-button.active {
      background-color:  #45627e;
    }

    .tab-content {
      background-color: white;
      padding: 20px;
      margin: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      display: none;
    }

    .tab-content.active {
      display: block;
    }

    .progress-bar {
      background-color: #e0e0e0;
      border-radius: 20px;
      overflow: hidden;
      height: 25px;
      margin-top: 10px;
    }

    .progress {
      height: 100%;
      line-height: 25px;
      color: white;
      text-align: center;
      background-color: #45627e;
    }
  </style>
</head>
<body>

  <div class="tab-container">
    <button class="tab-button active" onclick="openTab('Aportaciones', event)">Aportaciones</button>
    <button class="tab-button" onclick="openTab('Aportadores', event)">Aportadores</button>
    <button class="tab-button" onclick="openTab('Lo mas relevante', event)">Lo mas relevante</button>
  </div>

  <div class="tab-content active" id="Aportaciones">
    <h2>Aportaciones de la programacion al campo medico</h2>
    <p>info</p>
  </div>

  <div class="tab-content" id="Aportadores">
    <h2>Aportadores principales</h2>
    <p>info</p>
  </div>

  <div class="tab-content" id="Lo mas relevante">
    <h2>Aportaciones mas relevantes</h2>
    <p>info</p>
  </div>

  <script>
    function openTab(tabId, event) {
      // Oculta todas las pestañas
      const allTabs = document.querySelectorAll('.tab-content');
      allTabs.forEach(tab => tab.classList.remove('active'));

      // Quita la clase 'active' de todos los botones
      const allButtons = document.querySelectorAll('.tab-button');
      allButtons.forEach(button => button.classList.remove('active'));

      // Muestra la pestaña seleccionada
      document.getElementById(tabId).classList.add('active');

      // Activa el botón actual
      event.currentTarget.classList.add('active');
    }
  </script>

</body>
</html>
