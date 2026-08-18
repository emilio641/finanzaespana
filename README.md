<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Finanza España - Planes de Préstamos Rápidos</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {font-family: Arial; background: #f4f4f4; margin: 0; padding: 20px; text-align: center;}
        .container {background: white; padding: 30px; border-radius: 10px; max-width: 500px; margin: auto;}
        h1 {color: #006400;}
        input {width: 90%; padding: 12px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;}
        button {background: #25D366; color: white; padding: 15px; border: none; border-radius: 5px; font-size: 18px; width: 100%; cursor: pointer;}
        button:hover {background: #1ebe5a;}
    </style>
</head>
<body>
    <div class="container">
        <h1>Finanza España</h1>
        <p><b>Obtén tu préstamo rápido en 24 horas</b></p>
        <p>Sin papeleo. 100% seguro y confidencial.</p>
        
        <form onsubmit="enviarWhatsApp(); return false;">
            <input type="text" id="nombre" placeholder="Tu nombre completo" required>
            <input type="tel" id="whatsapp" placeholder="Tu número de WhatsApp" required>
            <button type="submit">Obtener mi plan ahora</button>
        </form>
        
        <p style="font-size:12px; margin-top:20px;">Atendemos de Lunes a Viernes</p>
    </div>

    <script>
        function enviarWhatsApp() {
            var nombre = document.getElementById("nombre").value;
            var whatsapp = document.getElementById("whatsapp").value;
            var mensaje = "Hola, me llamo " + nombre + ". Quiero información sobre los préstamos. Mi WhatsApp es: " + whatsapp;
            var url = "https://wa.me/+34695 79 65 48?text=" + encodeURIComponent(mensaje);
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
