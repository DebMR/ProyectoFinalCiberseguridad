# Proyecto Final Ciberseguridad
🛡️ Proyecto Final de Ciberseguridad - 4Geeks Academy

Descripción:

Este proyecto simula un escenario del mundo real en el que una organización ha sufrido un compromiso de seguridad. Como analista de ciberseguridad, tu responsabilidad es restaurar, proteger y documentar un servidor crítico comprometido. La máquina proporcionada simula un entorno Debian real y presenta diversas vulnerabilidades que deben ser detectadas, explotadas de forma controlada, corregidas y documentadas adecuadamente.

El proyecto está dividido en tres fases:

1. Corrección de un hackeo existente (análisis forense)

2. Detección y explotación controlada de una nueva vulnerabilidad

3. Diseño de un plan de respuesta ante incidentes y un SGSI según ISO 27001

🧩 Fases del Proyecto

🔍 Fase 1: Corrección de un Hackeo

Objetivo: Analizar el incidente, identificar el vector de ataque, bloquear el exploit y restablecer la seguridad del servidor.

Tareas realizadas:

Revisión de logs (/var/log/auth.log, etc.)

Identificación de accesos sospechosos y usuarios no autorizados

Detección de malware y rootkits

Eliminación de puertas traseras y procesos persistentes

Refuerzo de configuraciones (cambios en firewall, eliminación de puertos abiertos, cambio de contraseñas)

Redacción de un informe forense detallado

🕵️‍♂️ Fase 2: Detección y Corrección de una Nueva Vulnerabilidad

Objetivo: Identificar una vulnerabilidad no relacionada con el ataque anterior, explotarla de manera controlada, y corregirla.

Tareas realizadas:

Escaneo de puertos y servicios con herramientas como nmap

Detección de una mala configuración de Apache y escalada de privilegios

Documentación completa del proceso de explotación (paso a paso)

Aplicación de medidas correctivas

Redacción de un informe de pentesting

📋 Fase 3: Plan de Respuesta a Incidentes y SGSI

Objetivo: Crear un plan completo de respuesta a incidentes conforme a las mejores prácticas del NIST y diseñar un SGSI alineado con la norma ISO 27001.

Componentes entregados:

Plan de respuesta a incidentes basado en NIST SP 800-61

Sistema de Gestión de Seguridad de la Información (SGSI):

Análisis de riesgos

Políticas de seguridad

Planes de acción y control

Implementación de medidas DLP:

Cifrado de datos sensibles

Backups automáticos

Controles de acceso estrictos

Presentación ejecutiva para la gerencia

📄 Entregables Incluidos

📘 Informe de Análisis Forense

🧪 Informe de Pentesting

🛠️ Plan de Respuesta a Incidentes

🔐 Documentación del SGSI (ISO 27001)

📊 Presentación ejecutiva (PDF/PPT)

🧰 Herramientas y Tecnologías Utilizadas

grep, awk, journalctl, logwatch – para análisis de logs

chkrootkit, rkhunter, lynis – para escaneo de malware y rootkits

nmap, netstat, lsof – para detección de puertos y servicios

fail2ban, ufw, iptables – para configuración de firewall y hardening

OpenVAS, Nikto, Burp Suite – para escaneo y pruebas de seguridad

Documentación de referencia: NIST SP 800-61 y ISO/IEC 27001
