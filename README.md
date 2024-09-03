# Salud-psicologia
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Depresión y Salud Mental en Jóvenes</title>
</head>
<body>
    <header>
        <h1>Depresión y Salud Mental en Jóvenes</h1>
        <p>Bienvenido a nuestra página dedicada a la información y concientización sobre la depresión y la salud mental en jóvenes. Por favor, regístrese para acceder al contenido.</p>
        <form action="/registro" method="GET">
            <label for="edad">Por favor, indique su edad:</label>
            <input type="number" id="edad" name="edad" required>
            <input type="submit" value="Registrar">
        </form>
    </header>
    
    <h2>Información sobre la Depresión y la Salud Mental</h2>
    
    <section>
        <h3>¿Qué es la Depresión?</h3>
        <p>La depresión es un trastorno del estado de ánimo que causa una sensación persistente de tristeza y pérdida de interés en las actividades diarias. Puede afectar a la forma en que una persona piensa, siente y se comporta, y puede generar problemas emocionales, físicos y de funcionamiento cotidiano.</p>
    </section>
    
    <section>
        <h3>El Suicidio y la Depresión</h3>
        <p>La depresión es un factor de riesgo importante para el suicidio. Las personas que experimentan depresión grave pueden sentirse abrumadas por el dolor emocional y la desesperanza, lo que puede llevar a pensamientos o actos suicidas. Es fundamental buscar ayuda profesional si alguien experimenta pensamientos suicidas.</p>
    </section>
    
    <section>
        <h3>Prevención y Tratamiento</h3>
        <p>La detección temprana, el acceso a tratamiento y el apoyo emocional son fundamentales en la prevención y manejo de la depresión. Es importante hablar con un profesional de la salud mental si experimenta síntomas de depresión o conoce a alguien que pueda necesitar ayuda.</p>
    </section>
    
    <section>
        <h3>Efectos de la Depresión en la Vida Cotidiana</h3>
        <p>La depresión puede afectar diversos aspectos de la vida cotidiana, incluyendo el desempeño académico, las relaciones sociales, la productividad laboral, la autoestima y la salud física. Es importante abordar la depresión de manera integral para mejorar la calidad de vida y el bienestar emocional.</p>
    </section>
    
    <footer>
        <p>Esta página tiene fines informativos y de concientización. Si necesita ayuda o tiene alguna pregunta, no dude en contactar a un profesional de la salud mental o a una línea de ayuda especializada.</p>
    </footer>
</body> 
</html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Depresión y Salud Mental en Jóvenes</title>
</head>
<body>
<h1>Bienvenido a nuestra página sobre Depresión y Salud Mental en Jóvenes</h1>

<p>Por favor, ingresa tu nombre y edad:</p>

<input type="text" id="nombre" placeholder="Nombre">


<input type="number" id="edad" placeholder="Edad">


<button onclick="registrarUsuario()">Registrar</button>

<script>
function registrarUsuario() {
  const nombre = document.getElementById('nombre').value;
  const edad = document.getElementById('edad').value;

  if (!nombre || !edad) {
    alert('Por favor completa todos los campos.');
    return;
  }

  if (isNaN(edad) || edad <= 0) {
    alert('La edad debe ser un número positivo.');
    return;
  }

  alert(Gracias por registrarte, ${nombre}. Tu edad es ${edad}.);
}
</script>

</body>
</html>
