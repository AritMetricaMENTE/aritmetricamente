---
layout: default
title: Inicio - AritMetricaMENTE
---

<!-- SECCIÓN HERO DE BIENVENIDA (Fondo claro para fusionarse con el logo) -->
<div style="text-align: center; padding: 50px 20px; background: radial-gradient(circle, #ffffff 0%, #f4f7fc 100%); border-radius: 16px; margin-bottom: 40px; border: 1px solid #e2e8f0; box-shadow: 0 10px 25px rgba(30, 98, 212, 0.05);">
    
    <!-- CONTENEDOR DEL LOGO -->
    <img src="/assets/img/Logo_AritMetricaMENTE_Ajustado.jpeg" alt="AritMetricaMENTE Logo" style="max-width: 280px; height: auto; margin-bottom: 20px;" onerror="this.style.display='none';">
    
    <h1 style="color: #0e387a; font-size: 2.4rem; margin-bottom: 15px; font-weight: 800; letter-spacing: -0.5px;">Psicología y Psicometría Basada en la Evidencia</h1>
    
    <p style="font-size: 1.15rem; max-width: 750px; margin: 0 auto; color: #475569; line-height: 1.6;">
        Articulamos el rigor de la psicometría avanzada, la analítica de datos y la calidez del enfoque clínico cognitivo-conductual para ofrecer soluciones de evaluación de alta precisión.
    </p>
</div>

<!-- TÍTULO DE SECCIÓN -->
<h2 style="text-align: center; color: #0e387a; margin-bottom: 35px; font-weight: 700; font-size: 1.8rem; position: relative;">
    Nuestros Focos de Negocio
    <span style="display: block; width: 60px; height: 4px; background: #1e62d4; margin: 10px auto 0 auto; border-radius: 2px;"></span>
</h2>

<!-- ESTILOS INTERACTIVOS Y CONFIGURACIÓN DE REJILLA -->
<style>
    /* Fuerza que los 3 servicios se ubiquen en una única fila en pantallas grandes */
    .services-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 24px;
        margin-bottom: 40px;
    }

    .service-card {
        background: white; 
        border: 1px solid #e2e8f0; 
        border-top: 5px solid #1e62d4; 
        padding: 30px 25px; 
        border-radius: 12px; 
        box-shadow: 0 4px 15px rgba(30, 98, 212, 0.02); 
        display: flex; 
        flex-direction: column; 
        justify-content: space-between; 
        transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        text-align: center; /* Alinea los textos al centro para armonizar con el logo centrado */
    }
    .service-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 12px 24px rgba(30, 98, 212, 0.08);
        border-color: #1e62d4;
    }
    .service-card-highlighted {
        background: #fcfdfe; 
        border: 1px solid #dbeafe; 
        border-top: 5px solid #0e387a; 
        padding: 30px 25px; 
        border-radius: 12px; 
        box-shadow: 0 6px 20px rgba(14, 56, 122, 0.04); 
        display: flex; 
        flex-direction: column; 
        justify-content: space-between; 
        transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        text-align: center; /* Alinea los textos al centro */
    }
    .service-card-highlighted:hover {
        transform: translateY(-5px);
        box-shadow: 0 12px 24px rgba(14, 56, 122, 0.1);
        border-color: #0e387a;
    }
    .icon-container {
        width: 64px; 
        height: 64px; 
        background-color: #f0f6ff; 
        border-radius: 50%; 
        display: flex; 
        align-items: center; 
        justify-content: center; 
        margin: 0 auto 20px auto; /* 'margin: 0 auto' centra horizontalmente el contenedor circular */
    }

    /* Adaptabilidad: Pasa a 1 sola columna vertical en celulares de menos de 800px */
    @media (max-width: 800px) {
        .services-grid {
            grid-template-columns: 1fr;
        }
    }
</style>

<!-- GRILLA DE SERVICIOS CON CONTACTOS SEGMENTADOS -->
<div class="services-grid">

    <!-- Tarjeta 1: Consulta psicológica (Enfoque: Paciente / Público General) -->
    <div class="service-card">
        <div>
            <div class="icon-container" style="background-color: #e0ecff;">
                <img src="/assets/img/Isotipo_Servicio_Terapia_AritMetricaMENTE.jpeg" alt="Consulta" style="width: 36px; height: 36px; object-fit: contain;" onerror="this.parentNode.style.display='none';">
            </div>
            <h3 style="margin-top: 0; color: #0e387a; font-size: 1.25rem; font-weight: 700; margin-bottom: 12px;">1. Consulta Psicológica</h3>
            <p style="color: #475569; font-size: 0.95rem; line-height: 1.6; margin-bottom: 0;">Procesos de intervención clínica individualizada bajo el modelo cognitivo-conductual, garantizando un enfoque riguroso y empático respaldado por la evidencia.</p>
        </div>
        <div style="margin-top: 20px; display: flex; justify-content: space-between; align-items: center; gap: 10px;">
            <a href="/consultas.html" style="color: #1e62d4; font-weight: bold; text-decoration: none; font-size: 0.9rem;">Saber más &rarr;</a>
            <!-- Contacto para Consultas Psicológicas -->
            <a href="mailto:consultas@aritmetricamente.com?subject=Consulta%20Psicologica" style="color: #475569; text-decoration: none; font-size: 0.85rem; border: 1px solid #cbd5e1; padding: 6px 12px; border-radius: 6px; background: #f8fafc; font-weight: 500;">Agendar Cita</a>
        </div>
    </div>

    <!-- Tarjeta 2: PsicometrIA (Enfoque: Instituciones, Empresas, HR) -->
    <div class="service-card-highlighted">
        <div>
            <div class="icon-container" style="background-color: #e0ecff;">
                <img src="/assets/img/Isotipo_Servicio_Medicion_AritMetricaMENTE.jpeg" alt="PsicometrIA" style="width: 36px; height: 36px; object-fit: contain;" onerror="this.parentNode.style.display='none';">
            </div>
            <h3 style="margin-top: 0; color: #0e387a; font-size: 1.25rem; font-weight: 700; margin-bottom: 12px;">2. PsicometrIA</h3>
            <p style="color: #475569; font-size: 0.95rem; line-height: 1.6; margin-bottom: 0;">Desarrollamos metodologías y arquitecturas de vanguardia para el diseño de pruebas psicométricas y optimización de bancos de ítems a través de algoritmos de inteligencia artificial.</p>
        </div>
        <div style="margin-top: 20px; display: flex; justify-content: space-between; align-items: center; gap: 10px;">
            <a href="/pruebas.html" style="color: #0e387a; font-weight: bold; text-decoration: none; font-size: 0.9rem;">Saber más &rarr;</a>
            <!-- Contacto corporativo de proyectos / B2B -->
            <a href="mailto:medicion@aritmetricamente.com?subject=Servicios%20PsicometrIA" style="color: #0e387a; text-decoration: none; font-size: 0.85rem; border: 1px solid #bdf0ff; padding: 6px 12px; border-radius: 6px; background: #edf7ff; font-weight: 500;">Cotizar Proyecto</a>
        </div>
    </div>

    <!-- Tarjeta 3: Asesoría (Enfoque: Investigadores y Organizaciones) -->
    <div class="service-card">
        <div>
            <div class="icon-container" style="background-color: #e0ecff;">
                <img src="/assets/img/Isotipo_Servicio_Investigacion_AritMetricaMENTE.jpeg" alt="Asesoría" style="width: 36px; height: 36px; object-fit: contain;" onerror="this.parentNode.style.display='none';">
            </div>
            <h3 style="margin-top: 0; color: #0e387a; font-size: 1.25rem; font-weight: 700; margin-bottom: 12px;">3. Asesorías Metodológicas</h3>
            <p style="color: #475569; font-size: 0.95rem; line-height: 1.6; margin-bottom: 0;">Brindamos consultoría experta en diseño de investigaciones, curación estructurada de bases de datos, análisis estadístico multivariado y modelamiento psicométrico complejo.</p>
        </div>
        <div style="margin-top: 20px; display: flex; justify-content: space-between; align-items: center; gap: 10px;">
            <a href="/asesorias.html" style="color: #1e62d4; font-weight: bold; text-decoration: none; font-size: 0.9rem;">Saber más &rarr;</a>
            <!-- Contacto académico/consultoría -->
            <a href="mailto:asesorias@aritmetricamente.com?subject=Solicitud%20de%20Asesoria%20Metodologica" style="color: #475569; text-decoration: none; font-size: 0.85rem; border: 1px solid #cbd5e1; padding: 6px 12px; border-radius: 6px; background: #f8fafc; font-weight: 500;">Solicitar Asesoría</a>
        </div>
    </div>

</div>

<!-- SECCIÓN LLAMADA A LA ACCIÓN (CTA) FINAL -->
<div style="text-align: center; padding: 40px; background: linear-gradient(135deg, #0e387a 0%, #1e62d4 100%); border-radius: 16px; color: white; box-shadow: 0 10px 20px rgba(14, 56, 122, 0.15); margin-top: 50px;">
    <p style="font-weight: 500; font-size: 1.25rem; color: #f1f5f9; margin-bottom: 20px; text-shadow: 0 1px 2px rgba(0,0,0,0.1);">¿Listo para optimizar la toma de decisiones con el respaldo de la ciencia y los datos?</p>
    <a href="mailto:contacto@aritmetricamente.com" style="display: inline-block; background-color: #ff9f0a; color: #0e387a; padding: 14px 32px; text-decoration: none; border-radius: 8px; font-weight: 800; font-size: 1rem; box-shadow: 0 4px 15px rgba(255, 159, 10, 0.4); transition: background-color 0.2s ease;">Iniciar una Consulta Especializada</a>
</div>
