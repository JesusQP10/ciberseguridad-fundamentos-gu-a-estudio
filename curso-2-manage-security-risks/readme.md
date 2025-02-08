# 📌 README: Gestión de Riesgos en Ciberseguridad

## 🛡️ Introducción
Este módulo te proporcionará las herramientas y conocimientos necesarios para **identificar, evaluar y mitigar** los riesgos cibernéticos en organizaciones. Aprenderás a desarrollar estrategias proactivas para **proteger activos digitales** y responder eficazmente a incidentes de seguridad.

---

## 🎯 Objetivos de Aprendizaje
✔️ Comprender los fundamentos de la gestión de riesgos.  
✔️ Identificar y evaluar los riesgos cibernéticos más comunes.  
✔️ Desarrollar un plan de gestión de riesgos personalizado.  
✔️ Implementar controles de seguridad efectivos.  
✔️ Responder a incidentes de seguridad de manera eficiente.  

---

## Parte I: Fundamentos 🏛️

### Capítulo 1: Tríada CIA y Gestión de Activos 🔑

#### 1.1 Tríada CIA: Pilares de Seguridad 💖
*   Confidencialidad 🤫
    *   Cifrado Simétrico (AES-256) 🔐
    *   Cifrado Asimétrico (RSA) 🔑-🔓
    *   Caso: Equifax 😱
*   Integridad ✅
    *   Funciones Hash (SHA-256) 🧮
    *   Firmas Digitales ✍️
    *   Ejercicio: Hash de archivo 🧪
*   Disponibilidad 🚀
    *   Redundancia y Balanceo 🔄 (Ej: Netflix 🍿)
    *   DRP 🚑 (Componentes Clave 🛡️)

#### 1.2 Gestión de Activos y Riesgos 🛡️
*   Asset (Activo) 💎
    *   Clasificación 📊 (Críticos 🔥/ No Críticos ☁️)
    *   Ejercicio: Matriz de Criticidad 📝
*   Risk (Riesgo) ⚠️
    *   Análisis Cuantitativo/Cualitativo 🔢/🤔
    *   Herramienta: Matriz de Calor 🌡️

## Capítulo 2: Marcos Normativos y Cumplimiento 📜

#### 2.1 NIST CSF: Guía Maestra 🗺️
*   5 Funciones Clave 🖐️: Identificar 🔍, Proteger 🛡️, Detectar 🚨, Responder 🚒, Recuperar 🔄
*   Caso: Empresa de Salud ✅

#### 2.2 NIST SP 800-53: Controles Federales 🏛️
*   Controles Prioritarios ⭐: AC-3 🛂, SI-4 👁️
*   Ejercicio: Selección de Controles 📝

#### 2.3 Regulaciones Globales 🌍
*   GDPR (Europa) 🇪🇺
    *   Principios Clave: Consentimiento, Olvido 🔒
    *   Multa Meta 💸
*   HIPAA (EEUU - Salud) 🇺🇸
    *   PHI 🏥 (Cifrado y Auditorías)
    *   Caso Anthem Inc. 💔

## Parte II: Amenazas y Vulnerabilidades 😈

### Capítulo 3: Malware y Ataques Modernos 👾

#### 3.1 Ransomware: Pandemia Digital 🦠
*   Anatomía del Ataque 💀: Infiltración 🕵️‍♂️, Propagación 🕸️, Cifrado 🔒, Extorsión 💸
*   Ejemplo: WannaCry 💥
*   Ejercicio: Simulación Ransomware 🧪

#### 3.2 Ingeniería Social: El Engaño Humano 🎭
*   Técnicas Avanzadas 🎣: Spear Phishing 🎯 (Ej: CEO Falso ⚠️), Vishing 📞
*   Caso: Twitter 🐦
*   Ejercicio: Campaña Phishing Ético ✉️

### Capítulo 4: Vulnerabilidades y Cadena de Suministro ⛓️

#### 4.1 Vulnerabilidades Comunes (OWASP Top 10) 🤕
*   Inyección SQL 💉
    *   Código Vulnerable ❌ vs Solución ✅
    *   Ejercicio: Lab Inyección SQL (WebGoat) 💻

#### 4.2 Ataques Cadena de Suministro 💣
*   Ejemplo: SolarWinds 💥 (18.000 Afectados 😱)
    *   Lecciones 💡: Firmas Digitales 🔑, SBOM 📜
*   Ejercicio: Análisis SBOM 🔍

## Parte III: Herramientas y Estrategias de Defensa 🛡️

### Capítulo 5: Seguridad en Redes y Nube 🌐

#### 5.1 Arquitecturas de Red Seguras 🧱
*   Segmentación y Microsegmentación ✂️ (Ej: IoT en VLAN 🏰)
*   NGFW: Guardián Avanzado 💂
    *   Funciones Clave: Filtrado, IPS, SSL 🧠
    *   Ejercicio: Reglas pfSense 🔥

#### 5.2 Seguridad en la Nube ☁️
*   Modelo Responsabilidad Compartida 🤝: IaaS 💻 vs SaaS 📧
*   Riesgos Comunes ⚠️:  Configuraciones Err

    *   Ejercicio: Auditoría AWS ☁️

### Capítulo 6: IA en Ciberseguridad 🤖

#### 6.1 IA Defensiva: Protección Automatizada 🛡️
*   Detección de Anomalías 👽 (Ej: Darktrace 👀)
    *   Caso: Exfiltración de Datos 🚨
*   Respuesta Automatizada (SOAR) 🚀
    *   Flujo de Trabajo Típico 🤖

#### 6.2 IA Adversaria: Amenazas Emergentes 😈
*   Deepfakes 🎭 (Ej: CEO Falso 💸)
*   Ejercicio: Deepfake Simple 🧪

## Parte IV: Gestión de Incidentes y Ética 🤝

### Capítulo 7: Respuesta a Incidentes y Recuperación 🚑

#### 7.1 Ciclo de Vida del Incidente (NIST) ⛑️
*   Fases: Preparación 🏋️‍♀️, Detección 🚨, Contención 🚧, Erradicación 💥, Recuperación 🔄, Lecciones 🎓

#### 7.2 Caso: Colonial Pipeline (2021) ⛽
*   Ataque: Ransomware DarkSide
*   Lecciones 💡: Backups Offline 💾, Comunicación 🗣️
*   Ejercicio: Simulación Respuesta Ransomware 🎭

### Capítulo 8: Ética y Hacktivismo ⚖️

#### 8.1 Dilemas Éticos 🤔
*   Responsible Disclosure 📣 (Ej: Google Project Zero)
*   Debate: Hackeo Ético Gubernamental 🗣️

#### 8.2 Hacktivismo: Activismo Digital 💻
*   Ejemplos: Anonymous 🎭, WikiLeaks 📰
*   Ejercicio: Análisis Ético Snowden 🗣️

## Apéndices: Recursos Adicionales 📚

### A. Profundizar 🚀
*   Certificaciones 🏆: CISSP ⭐, CEH 🦹
*   Plataformas Entrenamiento 🎮: Hack The Box 🕹️, TryHackMe 🧠

### B. Laboratorios Avanzados 🛠️
*   SIEM con ELK Stack ⚙️
*   Análisis Forense con Autopsy 🕵️‍♀️

### C. Plantillas y Checklists 📋
*   Plan Respuesta Incidentes 📝
*   Checklist NIST CSF ✅

## 🛠️ Manual de Ejercicios Prácticos (Resumen) 🚀

### Ejercicio 1: Phishing con GoPhish 🎣
*   Objetivo: Campaña de concienciación.
*   Herramientas: GoPhish, Servidor.
*   Pasos: Instalar, Perfil Remitente, Página Falsa, Correo, Destinatarios, Lanzar, Monitorizar, Capacitar 🧑‍🏫

### Ejercicio 2: SIEM con ELK Stack ⚙️
*   Objetivo: Analizar logs de red.
*   Herramientas: Ubuntu, ELK Stack.
*   Pasos: Instalar Java, Elasticsearch, Kibana, Logstash, Configurar Logstash, Enviar Logs, Visualizar en Kibana 📊

### Ejercicio 3: Análisis Malware con Cuckoo 🕵️‍♀️
*   Objetivo: Identificar comportamiento malicioso.
*   Herramientas: Ubuntu, Cuckoo, Windows VM.
*   Pasos: Dependencias, Clonar Cuckoo, Configurar, Iniciar Cuckoo, Enviar Muestra, Ver Informe 🔍

### Ejercicio 4: Simulación Ransomware con Metasploit 🎭
*   Objetivo: Entender propagación y contención.
*   Herramientas: Kali Linux, Windows VM, Metasploit.
*   Pasos: Payload Metasploit, Listener, Ejecutar Payload, Simular Cifrado, Contención, Recuperación ⛑️

### Ejercicio 5: Firewall con pfSense 🔥
*   Objetivo: Bloquear tráfico malicioso.
*   Herramientas: pfSense VM, Clientes Windows/Linux.
*   Pasos: Instalar pfSense, Interfaz Web, Reglas Bloqueo, Geolocalización, Probar Reglas ✅
