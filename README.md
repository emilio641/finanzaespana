<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Finanza España - Prestamos Rapidos</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {font-family: Arial; background: #f4f4f4; margin: 0; padding: 20px; text-align: center;}
        .container {background: white; padding: 30px; border-radius: 10px; max-width: 500px; margin: auto;}
        h1 {color: #006400;}
        input {width: 90%; padding: 12px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;}
        button {background: #25D366; color: white; padding: 15px; border: none; border-radius: 5px; font-size: 18px; width: 100%;}
    </style>
</head>
<body>
    <div class="container">
        <h1>Finanza España</h1>
        <p><b>Obten tu prestamo rapido en 24 horas</b></p>
        <p>Sin papeleo. 100% seguro.</p>
        <form onsubmit="enviarWhatsApp(); return false;">
            <input type="text" id="nombre" placeholder="Tu nombre completo" required>
            <input type="tel" id="whatsapp" placeholder="Tu numero de WhatsApp" required>
            <button type="submit">Obtener mi plan ahora</button>
        </form>
    </div>
<script>
function enviarWhatsApp() {
var nombre = document.getElementById("nombre").value;
var mensaje = "Hola, me llamo " + nombre + ". Quiero informacion sobre los prestamos.";
window.open("https://wa.me/+34695796548?text=" + encodeURIComponent(mensaje), '_blank');
}
</script>
</body>
</html>
