
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
    <p>Algunas de las aportaciones más importantes de la programación en la medicina son cosas como 

-Historias Clínicas Electrónicas (HCE):
Las cuáles permiten almacenar, compartir y acceder a la información médica de los pacientes de manera eficiente y segura

-Bioinformática y Biología Computacional:
La programación permite el análisis de grandes cantidades de datos genéticos, la simulación de interacciones farmacológicas y el desarrollo de nuevas terapias

-Inteligencia Artificial (IA):
La IA se utiliza en medicina para el diagnóstico de enfermedades, la predicción de riesgos,etc.

-Aplicaciones Móviles de Salud:
Las aplicaciones móviles permiten a los pacientes acceder a información sobre su salud, monitorear sus signos vitales, recibir recordatorios de medicamentos

-Diseño y fabricación de prótesis y dispositivos médicos:
La impresión 3D y la programación permiten el diseño y la fabricación de prótesis personalizadas y dispositivos médicos a medida

-La sala de lectura de la Biblioteca Médica Nacional:
Donde los usuarios de la red de salud ya pueden consultar, en soporte digital (Multimedia), la colección «34 años de la Revista Cubana de Pediatría», correspondiente al periodo 1960-1994. Esta es una oportunidad para acceder a la memoria histórico-científica de la Pediatría en el sector de salud.

-Instituto Central de Investigaciones Digitales (I.C.I.D):
Ha creado equipos de alta tecnología, utilizando para ello las computadoras: el CardioCid, el NeuroCid, el S.U.M.A (Sistema Ultra Micro Analítico) usadas en la detección del S.I.D.A.

-SISCAN-Cuba:
Es un proyecto para el Registro Nacional de Cáncer, dentro del Sistema Nacional de Información Estadística del Ministerio de Salud Pública de Cuba. Se encarga de recolectar, almacenar, procesar y analizar la información sobre todos los casos de cáncer que se diagnostican cada año en Cuba. Es un registro de base poblacional y de alcance nacional de gran importancia si se considera que esta enfermedad es la segunda causa de muerte en Cuba.

-Facultad de Ciencias Médicas de Holguín:
Se desarrolló un software para la investigación, el Sistema Morfo-Estereológico Asistido por Computadoras con Digitalización de Imágenes (COMSDI-Plus), con el cual se han podido realizar muchas investigaciones histológicas y patológicas, el que se ha introducido en muchos centros del país y que constituye un orgullo de esa institución.

-Las simulaciones para el mejoramiento del proceso de Enseñanza y Aprendizaje se elaboraran con la utilización del programa SIMED (Simulación Médica)
Software libre cubano que usa otras herramientas libres como APACHE, MySQL y PHP. Considerado de gran relevancia tanto nacional como internacional por Gabriel Perdomo González Doctor en Medicina del Centro de Cibernética Aplicada a la Medicina (CECAM)

-La Empresa SOFTEL:
Perteneciente al Ministerio de la Informática y la Comunicación (MIC), desde sus inicios también desarrolló la informática médica, y dentro de esta la rama de Inteligencia Artificial en aplicaciones como INFOTOXI, encargado de controlar y diagnosticar intoxicación por productos tóxicos en centros dedicados a este tema; GERISOFT, para la Atención Primaria de Salud del adulto mayor y el SEAA, Sistema de Ayuda Diagnóstica en la Asistencia Primaria.
</p>
  </div>

  <div class="tab-content" id="Aportadores">
    <h2>Aportadores principales</h2>
    <p>info</p>
  </div>

  <div class="tab-content" id="Lo mas relevante">
    <h2>Aportaciones mas relevantes</h2>
    <p>La programación en la medicina es mucho más que una simple herramienta tecnológica. Se ha convertido en un pilar fundamental en la investigación, el diagnóstico y el tratamiento de enfermedades. Gracias a los avances en la tecnología y la informática, los profesionales de la salud pueden acceder a herramientas y sistemas que mejoran significativamente la atención médica,hoy en día se cuenta con programas comerciales que permiten administrar el consultorio, tanto en términos financieros como de organización de la atención. La potencialidad de estos programas es muy grande y pueden adaptarse, efectivamente, a las necesidades de cada usuario, como dicen sus promotores comerciales.

Los programas informáticos hacen las cosas más fáciles a los pacientes, que pueden, por ejemplo, pedir cita a través de internet o incluso ser evaluados o monitorizados en primera instancia por videoconferencia, evitando desplazamientos innecesarios.

En la actualidad, los avances de la informática en salud incluyen herramientas útiles como dictado de voz (para el historial médico de cada paciente y su inclusión en sistemas digitales de salud de forma eficiente); alertas sobre interacciones con medicamentos, exámenes de laboratorio, recomendación e información en tiempo real sobre la situación de un paciente, especialmente si tiene una condición crónica.

Descubrimiento de fármacos e investigación genómica: En la investigación farmacéutica y la genómica, la programación se utiliza para analizar grandes cantidades de datos genéticos y simular interacciones farmacológicas . Operaciones hospitalarias y gestión de recursos: Los centros sanitarios utilizan la programación para optimizar la asignación de recursos, la programación del personal y el flujo de pacientes</p>
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
