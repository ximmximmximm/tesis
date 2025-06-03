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
    <button class="tab-button" onclick="openTab('Desafios y Obstaculos', event)">Desafios y Obstaculos</button>
    <button class="tab-button" onclick="openTab('Fin', event)">Conclucion</button>
  </div>

  <div class="tab-content active" id="Aportaciones">
    <h2>Aportaciones de la programacion al campo medico</h2>
    <ul>
-Historias Clínicas Electrónicas (HCE):
Las HCE permiten almacenar, compartir y acceder a la información médica de los pacientes de forma digital. Esto mejora la continuidad del cuidado, evita la pérdida de información y facilita el acceso rápido y seguro entre diferentes profesionales de la salud, sin depender de registros físicos. También permiten integrar resultados de laboratorios, imágenes médicas y notas clínicas en un solo lugar.
    </ul>
    <ul>
-Bioinformática y Biología Computacional:
Gracias a la programación, es posible analizar grandes cantidades de datos biológicos, como secuencias de ADN y ARN. Esto permite identificar mutaciones genéticas, predecir enfermedades hereditarias, simular interacciones moleculares y diseñar medicamentos personalizados. También se utiliza para mapear redes de interacción celular y entender mecanismos complejos de enfermedades como el cáncer.
      </ul>
    <ul>
-Inteligencia Artificial (IA):
La IA se aplica en medicina para asistir en el diagnóstico temprano de enfermedades mediante el análisis de imágenes médicas (como radiografías o resonancias), predecir riesgos de salud basándose en historiales clínicos, y optimizar tratamientos personalizados. También se usa en chatbots médicos, análisis de lenguaje natural en informes clínicos y sistemas de apoyo a la toma de decisiones clínicas.
  </ul>
    <ul>
-Aplicaciones Móviles de Salud:
Las apps de salud permiten a los usuarios llevar un control de su bienestar diario. Estas pueden medir signos vitales como ritmo cardíaco o niveles de oxígeno, gestionar recordatorios de medicación, consultar historial médico, contactar con profesionales y recibir alertas de emergencia. Son especialmente útiles para el monitoreo de enfermedades crónicas como diabetes o hipertensión.
    </ul>
<ul>
-Diseño y fabricación de prótesis y dispositivos médicos:
Mediante tecnologías como la impresión 3D y la programación asistida por computadora (CAD/CAM), se pueden diseñar prótesis completamente adaptadas a la anatomía del paciente. Esto no solo mejora la funcionalidad y comodidad, sino que reduce costos y tiempos de producción. Además, permite el desarrollo de dispositivos médicos inteligentes, como marcapasos programables o exoesqueletos robóticos para rehabilitación.
</ul>
<ul>
-La sala de lectura de la Biblioteca Médica Nacional:
Donde los usuarios de la red de salud ya pueden consultar, en soporte digital (Multimedia), la colección «34 años de la Revista Cubana de Pediatría», correspondiente al periodo 1960-1994. Esta es una oportunidad para acceder a la memoria histórico-científica de la Pediatría en el sector de salud.
</ul>
<ul>
-Instituto Central de Investigaciones Digitales (I.C.I.D):
Ha creado equipos de alta tecnología, utilizando para ello las computadoras: el CardioCid, el NeuroCid, el S.U.M.A (Sistema Ultra Micro Analítico) usadas en la detección del S.I.D.A.
</ul>
<ul>
-SISCAN-Cuba:
Es un proyecto para el Registro Nacional de Cáncer, dentro del Sistema Nacional de Información Estadística del Ministerio de Salud Pública de Cuba. Se encarga de recolectar, almacenar, procesar y analizar la información sobre todos los casos de cáncer que se diagnostican cada año en Cuba. Es un registro de base poblacional y de alcance nacional de gran importancia si se considera que esta enfermedad es la segunda causa de muerte en Cuba.
</ul>
<ul>
-Facultad de Ciencias Médicas de Holguín:
Se desarrolló un software para la investigación, el Sistema Morfo-Estereológico Asistido por Computadoras con Digitalización de Imágenes (COMSDI-Plus), con el cual se han podido realizar muchas investigaciones histológicas y patológicas, el que se ha introducido en muchos centros del país y que constituye un orgullo de esa institución.
</ul>
<ul>
-Las simulaciones para el mejoramiento del proceso de Enseñanza y Aprendizaje se elaboraran con la utilización del programa SIMED (Simulación Médica)
Software libre cubano que usa otras herramientas libres como APACHE, MySQL y PHP. Considerado de gran relevancia tanto nacional como internacional por Gabriel Perdomo González Doctor en Medicina del Centro de Cibernética Aplicada a la Medicina (CECAM)
</ul>
<ul>
-La Empresa SOFTEL:
Perteneciente al Ministerio de la Informática y la Comunicación (MIC), desde sus inicios también desarrolló la informática médica, y dentro de esta la rama de Inteligencia Artificial en aplicaciones como INFOTOXI, encargado de controlar y diagnosticar intoxicación por productos tóxicos en centros dedicados a este tema; GERISOFT, para la Atención Primaria de Salud del adulto mayor y el SEAA, Sistema de Ayuda Diagnóstica en la Asistencia Primaria.
</ul>
  </div>

  <div class="tab-content" id="Aportadores">
    <h2>Aportadores principales</h2>
        <ul>
-Dennis Ritchie
En el año de 1967, siguiendo los pasos de su padre Alistair E. Ritchie, comenzó a trabajar para los Laboratorios Bell.
Desde aquí comenzaría a utilizar el usuario dmr, tanto en su correo de trabajo, como en los foros de USENET.
Aquí participó en los equipos que ayudaron a desarrollar el sistema operativo Servicio de Información y Cómputo
Multiplexado (Multiplexed Information and Computing Service, mejor conocido como Multics) y los lenguajes de
programación BCPL,  Traductor algebráico (Algebraic Translator, ALTRAN por sus siglas en inglés) y B.
    </ul>
      <ul>
-Donald A.B. Lindberg
El Dr. Donald A.B. Lindberg fue un pionero en el campo de la informática médica. Fue elegido como el primer presidente
de la Asociación Americana de Informática Médica (AMIA), donde desempeñó un papel fundamental en el establecimiento
de los principios y objetivos de esta disciplina emergente. Además, fue miembro fundador de la Fundación Health on the Net (HON
</ul>
    <ul>
-Edward Shortliffe
Desarrolló MYCIN, uno de los primeros sistemas expertos en medicina, diseñado para ayudar a
diagnosticar infecciones bacterianas y recomendar antibióticos
MYCIN usaba reglas lógicas programadas y fue pionero en el uso de IA en diagnóstico clínico
Fundador del campo de la informática biomédica.
      </ul>
    <ul>
-Peter Szolovits
Profesor en el MIT, trabajó en sistemas de ayuda al diagnóstico como CADUCEUS.
Fue pionero en el uso de procesamiento del lenguaje natural (PLN) para interpretar notas 
médicas escritas por médicos,contribuyó al desarrollo de sistemas de decisión clínica computarizados.
</ul>
    <ul>
-Atul Butte
Es Profesor Distinguido Priscilla Chan y Mark Zuckerberg y Director Inaugural
del Instituto Bakar de Ciencias de la Salud Computacional (bchsi.ucsf.edu) de la Universidad de California,
San Francisco (UCSF), también es el Científico de Datos Jefe de todo el Sistema de Salud de la
Universidad de California, con 20 facultades de medicina, 6 centros médicos y 10 hospitales
</ul>
    <ul>
-Carol Friedman
Es una figura destacada en el campo de la informática biomédica, especialmente reconocida
por sus contribuciones al procesamiento del lenguaje natural (NLP, por sus siglas en inglés) aplicado
a la medicina. Sus aportes han sido fundamentales para traducir el lenguaje clínico (como el que se encuentra
en notas médicas y registros de salud) en información estructurada y útil para sistemas computacionales
</ul>
        <ul>
-Wilhelm Conrad Röntgen
En 1869, consiguió doctorarse en la Universidad de Zúrich, el 8 de noviembre de 1895 descubrió que si el tubo de descarga
catódico se encerraba en una caja oscura donde no entrase la luz y colocaba papel cubierto por platinocianuro de bario,
este se volvía fluorescente al ser expuesto al tubo catódico, lo cual denomino como Rayos X.
    </ul>
  </div>

  <div class="tab-content" id="Lo mas relevante">
    <h2>Programacion Medicinal</h2>
        <p>
La programación en la medicina es mucho más que una simple herramienta tecnológica; se ha consolidado como un pilar fundamental en la investigación, el diagnóstico, el tratamiento y la gestión eficiente de los servicios de salud. Con el avance acelerado de la tecnología y la informática médica, los profesionales sanitarios disponen hoy de herramientas potentes que les permiten tomar decisiones más informadas, brindar una atención más precisa y mejorar de forma notable la calidad de vida de los pacientes.

Actualmente, existen programas comerciales especializados que permiten administrar de manera integral un consultorio o centro médico, tanto en el aspecto financiero como en la organización de la atención. Estos sistemas ofrecen soluciones adaptables a las necesidades particulares de cada usuario, optimizando procesos como la facturación, la gestión de turnos, el seguimiento de historias clínicas y la comunicación con los pacientes. Su versatilidad ha hecho que se conviertan en aliados indispensables en la práctica médica moderna.

Uno de los beneficios más visibles para los pacientes es la posibilidad de interactuar con los servicios médicos sin necesidad de acudir físicamente a los centros de salud. A través de aplicaciones y plataformas en línea, es posible agendar citas, recibir recordatorios automatizados, acceder a resultados de estudios y, en muchos casos, realizar consultas médicas por videoconferencia. Este tipo de atención remota es especialmente útil para personas con movilidad reducida, pacientes crónicos o quienes viven en zonas rurales alejadas.

En el campo clínico, los avances informáticos incluyen herramientas innovadoras como el dictado de voz asistido por inteligencia artificial, que permite a los médicos registrar de forma rápida y precisa el historial clínico del paciente, integrándolo de manera automática en los sistemas digitales de salud. Además, los sistemas de alerta sobre interacciones medicamentosas, duplicidad de tratamientos o alergias ayudan a prevenir errores y a reforzar la seguridad del paciente. La posibilidad de recibir información en tiempo real sobre signos vitales o resultados de laboratorio ha mejorado la capacidad de respuesta ante emergencias y ha favorecido el monitoreo continuo de enfermedades crónicas.

La programación también ha revolucionado la investigación biomédica. En áreas como el descubrimiento de fármacos y la genómica, se utilizan algoritmos complejos para analizar enormes volúmenes de datos genéticos, identificar patrones de enfermedades y simular interacciones moleculares. Este enfoque, basado en el análisis de datos a gran escala, ha permitido acortar los tiempos de desarrollo de nuevos medicamentos y personalizar tratamientos según el perfil genético del paciente, abriendo las puertas a la medicina de precisión.

Por otro lado, en las operaciones hospitalarias, la programación desempeña un papel clave en la optimización de recursos. Gracias a sistemas de gestión inteligentes, es posible planificar la asignación del personal, coordinar agendas quirúrgicas, controlar inventarios de insumos médicos y mejorar el flujo de pacientes en urgencias o consultas ambulatorias. Estas mejoras no solo elevan la eficiencia institucional, sino que también reducen costos y tiempos de espera.

La programación en medicina no es solo una herramienta complementaria, sino una pieza estratégica en la transformación del sistema de salud. Su integración continúa en expansión, y su impacto seguirá creciendo a medida que evolucionen las tecnologías digitales, siempre con el objetivo final de ofrecer una atención médica más humana, accesible, segura y basada en la evidencia.
    
</p>
  </div>
  <div class="tab-content" id="Desafios y Obstaculos">
    <h2>Desafíos y Consideraciones Éticas</h2>
    <p>
      A medida que los sistemas tecnológicos adquieren mayor capacidad para procesar información clínica, existe la posibilidad de que los médicos comiencen a depender excesivamente de estos instrumentos, reduciendo su juicio clínico a una función secundaria. Este fenómeno, conocido como “automatización del criterio”, puede debilitar la toma de decisiones médicas informadas si los profesionales no conservan una actitud crítica hacia las recomendaciones generadas por algoritmos. En algunos casos, se ha observado que el personal médico acepta los resultados computacionales sin verificarlos o sin considerar el contexto clínico particular del paciente, lo que puede llevar a errores significativos en el tratamiento.

Tambien los programas que asisten en diagnósticos o decisiones clínicas deben ser extremadamente precisos. Un error de programación o un sesgo en los datos puede conducir a diagnósticos incorrectos.Lo cual ocasionaria conducir a diagnósticos erróneos, retrasos en el 
tratamiento o incluso a intervenciones médicas inapropiadas.

Los sistemas médicos modernos, como los historiales clínicos electrónicos (EHR), recopilan grandes volúmenes de datos personales sensibles, incluyendo antecedentes médicos, diagnósticos, tratamientos, resultados de laboratorio e incluso información genética. El uso de programación para analizar, almacenar o compartir esta información exige la implementación de estrictos estándares de seguridad informática, ya que una vulnerabilidad en el código o una mala gestión de los datos puede tener graves consecuencias.

Cuando no se aplican medidas adecuadas de protección —como cifrado, control de acceso, autenticación segura o auditorías constantes—, se abre la posibilidad a incidentes como:
Filtraciones de datos personales, que pueden ser utilizados de forma indebida por terceros, afectando la privacidad y la dignidad de los pacientes.
Robo de identidad médica, en el cual delincuentes utilizan datos clínicos para obtener tratamientos o fármacos de manera fraudulenta.
Extorsiones o chantajes, especialmente cuando se trata de enfermedades delicadas o estigmatizadas, cuya divulgación no autorizada puede afectar gravemente la vida personal y laboral de los pacientes.
Pérdida de confianza en el sistema de salud, ya que los pacientes podrían mostrarse reacios a compartir información relevante si perciben que no será tratada con el debido resguardo.

Tambien una de las principales advercidades que enfrento la programacion medicinal fue la falta de interoperabilidad entre diferentes sistemas de salud. Muchos hospitales y clínicas utilizan plataformas incompatibles entre sí, lo que dificulta la integración de datos y el funcionamiento fluido de herramientas programadas. La ausencia de estándares universales para el intercambio de información médica (como HL7 o FHIR) provoca redundancias, pérdida de datos y errores de interpretación.
    </p>
  </div>

<div class="tab-content" id="Fin">
    <h2>Breve Introduccion y Conclusion</h2>
<p>
Breve introducción sobre la programación y la medicina:
La programación informática constituye una disciplina fundamental en el desarrollo de soluciones tecnológicas,
al permitir la creación de algoritmos y estructuras lógicas que instruyen a las computadoras para ejecutar
tareas específicas. Mediante lenguajes de programación como Python, Java, R, C++, entre otros, es posible
diseñar sistemas capaces de procesar grandes volúmenes de datos, automatizar procesos complejos y generar
modelos predictivos que mejoran la eficiencia en múltiples ámbitos. Paralelamente, la medicina se consolida
como una ciencia y un arte orientado a la preservación, promoción y recuperación de la salud humana, a
través del estudio, prevención, diagnóstico y tratamiento de enfermedades.

En las últimas décadas, la convergencia entre programación y medicina ha dado lugar a un nuevo paradigma
en la atención sanitaria, caracterizado por el uso intensivo de tecnologías digitales. La programación ha
pasado de ser una herramienta auxiliar a convertirse en un componente estructural de la medicina moderna,
permitiendo el desarrollo de aplicaciones clínicas, plataformas de telemedicina, sistemas de historia 
clínica electrónica, dispositivos médicos inteligentes, algoritmos de inteligencia artificial (IA) aplicados
al diagnóstico, así como modelos de análisis de datos a gran escala en el ámbito epidemiológico y genómico.

  <h3>
    CONCLUCION:
  </h3>
  <p>
    En conclusión, la programación se presenta como un pilar clave en el desarrollo de una medicina más avanzada,
    personalizada y eficiente. Su correcta aplicación y regulación determinarán en gran medida el rumbo de la salud
    digital en los próximos años, por lo que es imprescindible seguir fomentando la investigación interdisciplinaria,
    la formación técnica del personal médico y el desarrollo ético de nuevas soluciones tecnológicas.
  </p>
</p>

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
