# Plataforma Educativa: Seguridad Informática (Clave: 702)

[![UNAM](https://img.shields.io/badge/UNAM-FES%20Cuautitl%C3%A1n-002B7F?style=for-the-badge)](https://www.cuautitlan.unam.mx/)
[![Licenciatura](https://img.shields.io/badge/Licenciatura-Inform%C3%A1tica-D4AF37?style=for-the-badge)](https://www.cuautitlan.unam.mx/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-2ea44f?style=for-the-badge&logo=github)](https://salvadorGoros.github.io/Seguridad-Inform-tica/)

Sitio web educativo interactivo desarrollado para la asignatura obligatoria **Seguridad Informática (Clave: 702)** de la **Licenciatura en Informática** (Séptimo Semestre) de la **Facultad de Estudios Superiores Cuautitlán**, Universidad Nacional Autónoma de México (UNAM).

---

## 🌐 Despliegue en GitHub Pages
El sitio se despliega automáticamente en GitHub Pages con cada cambio publicado en la rama `main`. El workflow de GitHub Actions publica los archivos estáticos del repositorio, sin requerir compilación.

🔗 **[Ver Sitio Web en Vivo](https://salvadorGoros.github.io/Seguridad-Inform-tica/)**

Para habilitar el primer despliegue, en GitHub abre **Settings → Pages** y selecciona **GitHub Actions** como fuente de publicación. Después de subir los cambios, puedes consultar el resultado en la pestaña **Actions**.

---

## 📚 Estructura Temática del Programa Oficial (80 Horas)

1. **Unidad 1: Introducción a la Seguridad Informática** (5 hrs Teóricas / 0 Prácticas)
   - Definición de seguridad informática vs. seguridad de la información.
   - Historia y estructura de la información (*Data at Rest*, *Data in Transit*, *Data in Use*).
   - Tipos de seguridad (Física vs. Lógica / Activa vs. Pasiva).
   - Propiedades de un sistema seguro (Tríada CID: Confidencialidad, Integridad y Disponibilidad).
2. **Unidad 2: Problemáticas Actuales en Seguridad Informática** (5 hrs Teóricas / 0 Prácticas)
   - Vulnerabilidades (CVE/CVSS), amenazas y ataques.
   - Servicios formales de seguridad (Estándar ITU-T X.800).
   - Criptografía aplicada: Simétrica (AES), Asimétrica (RSA/ECC) y Funciones Hash (SHA-256).
3. **Unidad 3: Políticas y Normatividad Vigentes** (10 hrs Teóricas / 0 Prácticas)
   - Misión de la seguridad y definición de políticas institucionales.
   - Ciclo de diseño e implementación de políticas (PDCA).
   - Metodologías de análisis y gestión de riesgos (MAGERIT, ISO/IEC 27005).
   - Análisis de vulnerabilidades y pentesting ético.
   - Normatividad Internacional (ISO/IEC 27001/27002) y Marco Legal Mexicano (Código Penal Federal Arts. 211 bis 1-7 y LFPDPPP).
4. **Unidad 4: Detección de Intrusos** (9 hrs Teóricas / 10 Prácticas)
   - Mecanismos de seguridad lógica (MFA, RBAC, Hardening) y física (Datacenters, HVAC, agentes limpios FM-200/Novec 1230).
   - Sistemas IDS/IPS: NIDS en puerto SPAN (Snort, Suricata) y HIDS en host (Wazuh, OSSEC).
   - Detección por firmas vs. detección por anomalías.
5. **Unidad 5: Código Malicioso** (9 hrs Teóricas / 10 Prácticas)
   - Negación de Servicio (DoS/DDoS) y redes Botnet.
   - Taxonomía del malware: Caballos de Troya, Virus, Gusanos y Bombas Lógicas.
   - Analizadores de tráfico y modo promiscuo (Sniffers).
6. **Unidad 6: Seguridad en Redes** (10 hrs Teóricas / 12 Prácticas)
   - Esquemas de defensa en profundidad, Zonas Desmilitarizadas (DMZ) y arquitectura Zero Trust.
   - Niveles de seguridad en el modelo OSI / TCP-IP.
   - Protocolo de autenticación Kerberos (KDC, AS, TGS y Tickets TGT).
   - Conexiones seguras con SSH y protocolos SSL / TLS 1.3 (Handshake y HTTPS).
   - Firewalls de inspección de estado (Stateful), WAF y filtrado con `iptables`.
   - Protocolos inalámbricos IEEE 802.11: vulnerabilidades de WEP/WPA, WPA2-CCMP y robustez de WPA3 (SAE Dragonfly).

---

## 🛠️ Tecnologías Utilizadas
- **HTML5 Semántico:** Navegación dinámica SPA (Single Page Application) sin recargas.
- **CSS3 Moderno:** Paleta institucional UNAM (Azul `#002B7F` y Oro `#D4AF37`), diseño responsivo y adaptabilidad para móviles.
- **JavaScript Nativo (Vanilla):** Control de vistas, selector interactivo de módulos temáticos y cuestionario diagnóstico autocalificable.
- **SVG Vectorial:** Infografías arquitectónicas embebidas de alta definición.
- **Integración Multimedia:** Videoteca académica con conferencias oficiales de UNAM-CERT (`@SeguridadTV`), AprendeTIC DGTIC, TV UNAM y TVIngenieria.

---

## 🏫 Créditos Institucionales
- **Institución:** Universidad Nacional Autónoma de México (UNAM)
- **Facultad:** Facultad de Estudios Superiores Cuautitlán (FES Cuautitlán)
- **Licenciatura:** Licenciatura en Informática
- **Asignatura:** Seguridad Informática (Clave: 702)
- **Desarrollador / Alumno:** Salvador Lugo (Goros)
