<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Finanza España - Prestamos Rapidos 24h</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {font-family: Arial; background: #0a2540; margin: 0; padding: 0; color: #333;}
        .header {background: #0a2540; color: white; padding: 30px 20px; text-align: center;}
        .header h1 {margin: 0; font-size: 28px;}
        .header p {margin: 5px 0 0 0;}
        .container {background: white; padding: 30px; border-radius: 10px; max-width: 500px; margin: 20px auto;}
        h2 {color: #0a2540; text-align: center;}
        input {width: 90%; padding: 12px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; display: block; margin-left: auto; margin-right: auto;}
        button {background: #25D366; color: white; padding: 15px; border: none; border-radius: 5px; font-size: 18px; width: 100%; font-weight: bold; cursor: pointer;}
        button:hover {background: #1ebe5a;}
    </style>
</head>
<body>
    <div class="header">
        <h1>Finanza España</h1>
        <p>Prestamos de 1.000 € a 500.000 € al 2% TAEG</p>
    </div>
    
    <div class="container">
        <h2>1. Simulador de Prestamo</h2>
        <input type="number" id="monto" placeholder="Monto solicitado €" value="20000">
        <input type="number" id="anos" placeholder="Plazo en años" value="5">
        <p style="text-align:center;"><b>Pago mensual estimado:</b></p>
    </div>

    <div class="container">
        <h2>2. Tus datos personales</h2>
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
