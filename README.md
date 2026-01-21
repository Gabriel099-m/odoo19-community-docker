# 🚀 Odoo 19 Community con Docker

Este repositorio contiene la configuración necesaria para **instalar y ejecutar Odoo 19 Community usando Docker y Docker Compose**, de forma rápida y reproducible.

El proceso completo de instalación y puesta en marcha está explicado **paso a paso en video**.

---

## 🎥 Video de instalación (Paso a paso)

👉 **Mira el video aquí:**  
🔗 https://drive.google.com/file/d/1NYMiMcaStpajjWs6khY9jiFzMeyHc6TZ/view?usp=sharing

En el video se explica:
- Estructura del proyecto
- Configuración del archivo `.env`
- Uso de `docker-compose`
- Levantar Odoo 19 Community
- Acceso al sistema desde el navegador

---

## 📁 Estructura del proyecto

```bash
odoo-v19-community/
├── addons/            # Addons personalizados (opcional)
├── config/            # Archivos de configuración de Odoo
├── filestore/         # Datos generados por Odoo (NO se versiona)
├── docker-compose.yml # Orquestación de contenedores
├── .env               # Variables de entorno
└── README.md
