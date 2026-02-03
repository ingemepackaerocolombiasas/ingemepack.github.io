# ingemepack
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>INGEMEPACK AEROCOLOMBIA SAS</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root{
      --color-principal:#0a3d62;
      --color-secundario:#1e90ff;
      --color-fondo:#f4f6f8;
    }

    body{
      margin:0;
      font-family:Arial, Helvetica, sans-serif;
      background:var(--color-fondo);
      color:#333;
    }

    header{
      background:var(--color-principal);
      color:white;
      padding:30px;
      text-align:center;
    }

    section{
      padding:40px 20px;
      max-width:1100px;
      margin:auto;
    }

    h2{
      color:var(--color-principal);
    }

    .beneficios, .aplicaciones{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
    }

    .card{
      background:white;
      padding:20px;
      border-radius:8px;
      box-shadow:0 0 10px rgba(0,0,0,0.1);
    }

    .cta{
      background:var(--color-secundario);
      color:white;
      text-align:center;
      padding:40px 20px;
    }

    footer{
      background:#222;
      color:white;
      text-align:center;
      padding:20px;
    }

    .editor{
      position:fixed;
      top:10px;
      right:10px;
      background:white;
      padding:10px;
      border-radius:6px;
      box-shadow:0 0 10px rgba(0,0,0,0.2);
      font-size:14px;
    }
  </style>
</head>

<body contenteditable="true">

<header>
  <h1>INGEMEPACK AEROCOLOMBIA SAS</h1>
  <p>Soluciones industriales en forros de vinilo</p>
</header>

<section>
  <h2>Forros para paneles industriales en vinilo</h2>
  <p>
    Protegemos sus paneles eléctricos y equipos industriales contra polvo,
    humedad, grasa y desgaste, aumentando la vida útil y mejorando la
    presentación de su operación.
  </p>
</section>

<section>
  <h2>Beneficios</h2>
  <div class="beneficios">
    <div class="card">✔ Protección total</div>
    <div class="card">✔ Fácil limpieza</div>
    <div class="card">✔ Material resistente</div>
    <div class="card">✔ Fabricación a medida</div>
  </div>
</section>

<section>
  <h2>Aplicaciones</h2>
  <div class="aplicaciones">
    <div class="card">Paneles eléctricos</div>
    <div class="card">Tableros de control</div>
    <div class="card">Equipos industriales</div>
    <div class="card">Industria aeronáutica</div>
  </div>
</section>

<section class="cta">
  <h2>Solicite su cotización hoy</h2>
  <p>Contáctenos y reciba asesoría personalizada</p>
  <p><strong>Email:</strong> contacto@ingemepack.com</p>
  <p><strong>Tel:</strong> +57 XXX XXX XXXX</p>
</section>

<footer>
  <p>© 2026 INGEMEPACK AEROCOLOMBIA SAS</p>
</footer>

<div class="editor">
  ✏️ Puede editar esta página directamente<br>
  Haga clic sobre cualquier texto
</div>

</body>
</html>
