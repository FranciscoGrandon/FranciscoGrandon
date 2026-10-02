<div align="center">

# Francisco Grandón Vergara

**AI & Data Operations Lead | Enterprise Automation & Systems Engineer**  
*Ingeniero de Ejecución en Administración y Finanzas · Especialista en Arquitectura de Datos & Edge AI*

Concepción, Chile 🇨🇱

[![GitHub](https://img.shields.io/badge/GitHub-FranciscoGrandon-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/FranciscoGrandon)
[![Google Skills](https://img.shields.io/badge/Google_Skills-Silver_League_%C2%B7_2.248_pts-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8)
[![Microsoft Learn](https://img.shields.io/badge/Microsoft_Learn-FRANCISCO--GRANDON-0078D4?style=flat-square&logo=microsoft&logoColor=white)](https://learn.microsoft.com/es-es/users/FRANCISCO-GRANDON)
[![Email](https://img.shields.io/badge/Contacto-francisco.grandon%40outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:francisco.grandon@outlook.com)

</div>

---

<!-- Creado por Francisco Grandón Vergara - Depto. Operaciones Comerciales -->

## ⚡ Propuesta de Valor & Visión Profesional

Ingeniero y arquitecto de soluciones que fusiona **rigor financiero, auditoría de procesos comerciales y visión estratégica de negocio** con **ingeniería de software avanzada e Inteligencia Artificial en el edge**.

Especializado en traducir problemáticas operativas complejas y grandes volúmenes de datos transaccionales en sistemas autónomos, modelos de visión artificial embebidos, pasarelas multi-agente y flujos de automatización desatendida de alta confiabilidad. Con experiencia directa en entornos industriales y corporativos de gran escala (Essbio / Nuevosur), operando sobre plataformas críticas como **SAP ERP-ISU, SAP HANA y ecosistemas móviles Android**.

### 📌 Métricas de Impacto & Diferenciales Clave

* 🚀 **100% de Trazabilidad & Auditoría Postal:** Diseño e implementación de motor híbrido (API REST/SOAP + CSV) para cruce y conciliación del 100% de la facturación postal certificada entre SAP, imprenta AMF y Correos de Chile.
* 🗄️ **228 Consultas Analíticas Indexadas en SAP HANA:** Creación del catálogo maestro y CLI en Python (`QueryLibrary`) que estructura y parametriza el conocimiento operativo de medición, facturación y cortes.
* 🧠 **Edge AI & Visión Multimodal On-Device:** Implementación de modelos TFLite ($224 \times 224 \times 3$) y visión multimodal (Gemini API / SigLIP) para lectura automática de medidores y validación fotográfica en terreno con inferencia sub-segundo.
* 🤖 **Sistemas Autónomos & Protocolos Multi-Agente:** Autor de la arquitectura de orquestación `orchestration.md v2.0` y pasarelas seguras (`agent-gateway`) con sandboxing de procesos y tolerancia a fallos.
* 🛡️ **Gobernanza & Cumplimiento Corporativo:** Rigurosa adherencia a políticas de solo lectura en SAP Productivo, protección contra inyecciones de prompt y acreditación en seguridad de agentes corporativos (Google Cloud GEAR).

---

## 🛠️ Stack Tecnológico & Arquitectura

| Capa / Dominio | Tecnologías y Herramientas |
| :--- | :--- |
| **Lenguajes Core** | `Python 3.12` `Java` `SQL (SAP HANA & SQLite)` `PowerShell` `HTML5 / CSS3` |
| **Inteligencia Artificial & Edge Vision** | `TensorFlow Lite` `TensorFlow` `PyTorch` `Google SigLIP` `MobileNetV3` `Gemini Multimodal API` `OpenCV` |
| **Sistemas Corporativos & Bases de Datos** | `SAP GUI Scripting API (Windows 64-bit)` `SAP HANA` `SAP ERP-ISU` `SQLite` `Cloudflare D1` |
| **Data Analytics & Business Intelligence** | `Pandas` `Microsoft Power BI` `DAX` `Microsoft Excel Avanzado` `Treeview GUI` |
| **Mobile & Sistemas Distribuidos** | `Android SDK Nativo` `CameraX & CameraGPS` `OpenStreetMap (OSM)` `REST / SOAP APIs` `Telegram Bot API` |
| **DevOps, Automatización & Sandbox** | `Antigravity Multi-Agent CLI` `Win32 COM Automation` `Selenium` `Git & GitHub` `Termux Linux` |

---

## 🎓 Formación Académica

| Título / Grado | Casa de Estudios | Año | Credencial Verificada |
| :--- | :--- | :---: | :---: |
| **Ingeniero de Ejecución en Administración y Finanzas** | Instituto Profesional Virginio Gómez | 2010 | [Visualizar Título Profesional](./Titulo_Profesional_IP_Virginio_Gomez_Ingeniero_Ejecucion_Administracion_Finanzas_2010.jpg) |

---

## 🚀 Proyectos Destacados & Arquitectura de Ingeniería

### 🔬 [SGL Vision Studio & Lab](https://github.com/FranciscoGrandon/sgl-vision-studio)
> **Ecosistema On-Device & Desktop para Visión Artificial en Terreno**
* **Problema:** Los lectores de medidores en terreno capturan miles de imágenes bajo condiciones ambientales adversas (reflejos, nichos oscuros, suciedad), generando falsos positivos en el control de calidad.
* **Solución Técnica:** Suite desktop en Python para gestión de datasets y re-etiquetado activo (*Active Learning / Hard Negative Mining*), junto con un banco de pruebas móvil en Android nativo ([sgl-vision-lab](https://github.com/FranciscoGrandon/sgl-vision-lab)) con operadores nativos C++ TFLite (`Float32`, $224 \times 224 \times 3$) y sincronización por ADB Hot-Swap.
* **Impacto:** Eliminación de dependencias externas en el runtime móvil y optimización del ciclo de retroalimentación de modelos de visión.
* **Stack:** `Python` `TensorFlow` `TFLite C++` `Android SDK` `Java` `OpenCV`

---

### 💡 [LECTRON & LECTRON APK](https://github.com/FranciscoGrandon/lectron-apk)
> **Lectura Inteligente de Medidores de Agua basada en IA Multimodal & Android Nativo**
* **Problema:** La transcripción manual de diales y rodillos analógicos es propensa a errores humanos que repercuten directamente en la facturación y reclamos de clientes.
* **Solución Técnica:** Arquitectura dual integrada por una API de alto rendimiento en FastAPI y una aplicación Android nativa que procesa imágenes con modelos multimodales Gemini, discriminando automáticamente metros cúbicos ($m^3$) de litros y almacenando auditoría local en SQLite.
* **Impacto:** Automatización integral de la lectura con verificación visual y tolerancia a desconexión en terreno.
* **Stack:** `Python` `FastAPI` `Gemini Vision API` `Android Native (Java)` `SQLite`

---

### 🏢 [SAP GUI Automation](https://github.com/FranciscoGrandon/sap-automation)
> **Automatización Robótica (RPA) Desatendida en SAP GUI ERP-ISU para Windows 64-bit**
* **Problema:** La extracción manual de órdenes masivas (`IW39`, `ZDM_0050`) y reportes ALV en SAP ERP-ISU demanda cientos de horas-hombre y conlleva riesgos de error operacional.
* **Solución Técnica:** Motor RPA en Python basado en la API COM oficial de SAP GUI Scripting, con **guardrails programáticos inquebrantables de sólo lectura** (`SapGuiClient`), bloqueo nativo de teclas peligrosas (VKey 11 / `Ctrl+S`), listas negras de transacciones y soporte de ejecución headless/background para subagentes.
* **Impacto:** Automatización desatendida y resiliente de reportes críticos con cero incidentes de modificación de datos en producción.
* **Stack:** `Python 3.12` `SAP GUI Scripting COM` `Win32` `Pandas` `Antigravity CLI`

---

### 📦 [Trazabilidad de Despacho Postal Certificado](https://github.com/FranciscoGrandon/trazabilidad)
> **Plataforma de Auditoría End-to-End con Sincronización API & Cruce Masivo**
* **Problema:** Desfases entre lo clasificado por SAP, lo impreso por el taller externo (AMF) y la admisión física por Correos de Chile, con riesgo de cartas extraviadas o incumplimiento de plazos legales.
* **Solución Técnica:** Sistema automatizado de cruce en 3 niveles con cliente unificado REST/SOAP para Correos de Chile, base de datos local con caché persistente y generador de dashboards ejecutivos en HTML.
* **Impacto:** Visibilidad del 100% de los documentos, detección inmediata de piezas no admitidas y reducción drástica de tiempos de auditoría de despacho.
* **Stack:** `Python` `REST/SOAP API Client` `SAP Export` `Pandas` `Dashboard HTML/JS`

---

### 🤖 [Agent Gateway & Antigravity Multiagent Orchestration](https://github.com/FranciscoGrandon/antigravity-multiagent-orchestration)
> **Protocolo Multi-Agente v2.0 & Pasarela Remota Segura con Telegram Bot**
* **Problema:** Necesidad de controlar, despachar y monitorizar agentes autónomos locales desde dispositivos móviles sin exponer la terminal ni comprometer la máquina anfitriona.
* **Solución Técnica:** Implementación del protocolo de orquestación (`orchestration.md v2.0`) y desarrollo de [agent-gateway](https://github.com/FranciscoGrandon/agent-gateway), pasarela asíncrona en Python que enlaza el CLI local de Antigravity con la API de Telegram bajo estrictas políticas de sandbox, listas blancas y aislamiento de procesos.
* **Impacto:** Supervisión remota segura y ejecución coordinada de pipelines multiagente en tiempo real.
* **Stack:** `Python` `Telegram Bot API` `Antigravity CLI` `Process Sandboxing` `Asyncio`

---

### 🛰️ [MockGPSPro](https://github.com/FranciscoGrandon/MockGPSPro)
> **Simulador de Telemetría GPS Anti-Heurística con Visor OpenStreetMap en Vivo**
* **Problema:** Imposibilidad de validar aplicaciones móviles georreferenciadas en terreno sin incurrir en costos logísticos de traslado físico continuo.
* **Solución Técnica:** Aplicación Android nativa que genera telemetría de ubicación simulada con algoritmos anti-heurísticos (fluctuación realista de velocidad, satélites y altitud) y visor interactivo offline basado en OpenStreetMap.
* **Impacto:** Aceleración de pruebas QA para aplicaciones de inspección y lectura en entornos simulados de alta fidelidad.
* **Stack:** `Android SDK` `Java` `OpenStreetMap (OSMDroid)` `Mock Location API` `Telemetry Engine`

---

### 🗄️ [Biblioteca Maestra SQL SAP HANA](https://github.com/FranciscoGrandon)
> **Catálogo Indexado de 228 Consultas Comerciales & Motor CLI para Agentes**
* **Problema:** Dispersión histórica de scripts SQL analíticos para facturación, medición y cortes, provocando inconsistencias y sobrecarga en la formulación de consultas.
* **Solución Técnica:** Repositorio estandarizado con metadatos UTF-8, esquemas documentados y paquete CLI modular en Python (`QueryLibrary`) que permite a humanos y agentes de IA localizar, parametrizar y ejecutar queries de forma segura con muestreo controlado.
* **Impacto:** Estandarización de 228 procesos de consulta y consulta segura con límite de contexto optimizado.
* **Stack:** `SAP HANA SQL` `Python CLI` `Tkinter GUI Multi-Pestaña` `Metadata Engine`

---

### 📱 [Registro de Entrega Essbio](https://github.com/FranciscoGrandon/registro-de-entrega-essbio)
> **Captura Georreferenciada en Terreno & Sincronización Serverless en Cloudflare D1**
* **Problema:** Falta de evidencia verificable e inmutable de la entrega de notificaciones y documentos comerciales a clientes en terreno.
* **Solución Técnica:** App móvil Android con captura fotográfica y georreferenciación integrada (CameraGPS), conectada a una base de datos distribuida en la red global de Cloudflare (D1) y visor web de auditoría en tiempo real.
* **Impacto:** Trazabilidad irrefutable con coordenadas satelitales y marcas de tiempo sincronizadas en la nube.
* **Stack:** `Android SDK (Java)` `CameraGPS` `Cloudflare D1` `SQLite` `Web Dashboard`

---

## 📜 Certificaciones & Acreditaciones Profesionales

### 🧠 I. Inteligencia Artificial Empresarial, Agentes Autónomos & Ciberseguridad

> **[Perfil Oficial Google Skills (Silver League · 2,248 pts)](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8)**

| Certificación / Insignia | Emisor | Fecha | Acreditación Verificada |
| :--- | :--- | :---: | :---: |
| **Model Armor: Securing AI Deployments** | Google Cloud (GEAR) | Sep 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/27621323) |
| **Gen AI: Beyond the Chatbot** | Google Cloud (GEAR) | Sep 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/27549789) |
| **Secure Enterprise AI Agents** | Google Cloud (GEAR) | Sep 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/27512911) |
| **Google Cloud Agent Governance and Security** | Google Cloud (GEAR) | Sep 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/27512517) |
| **Create Your First Gemini Enterprise Application** | Google Cloud (GEAR) | Jul 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/25425887) |
| **Enterprise Agents and Use Cases** | Google Cloud (GEAR) | Jul 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/25425841) |
| **Agent Fundamentals** | Google Cloud (GEAR) | Jul 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/25425809) |
| **Introduction to AI Agents** | Google Cloud (GEAR) | Jun 2026 | [Ver Insignia Google Skills](https://www.skills.google/public_profiles/abcdc188-a406-4f46-90e2-0ba40e67b3c8/badges/24709973) |
| **Técnico en Seguridad Informática: Análisis de Riesgos (65 hrs)** | Fundación Carlos Slim | 2023 | [Ver Certificado PDF](./Certificado_Fundacion_Carlos_Slim_Tecnico_Seguridad_Informatica_Analisis_Riesgos_65h_2023.pdf) |
| **Cómputo Básico (18 hrs)** | Fundación Carlos Slim | 2023 | [Ver Constancia PDF](./Constancia_Fundacion_Carlos_Slim_Computo_Basico_18h_2023.pdf) |

---

### 📊 II. Data Analytics, Business Intelligence & Power Platform

> **[Perfil Oficial Microsoft Learn (FRANCISCO-GRANDON)](https://learn.microsoft.com/es-es/users/FRANCISCO-GRANDON)**

| Trofeo / Módulo Acreditado | Emisor | Fecha / Horas | Acreditación Verificada |
| :--- | :--- | :---: | :---: |
| **🏆 Path: Get started with Microsoft data analytics** | Microsoft Learn | Abr 2023 | [Ver Trofeo Oficial](https://learn.microsoft.com/es-es/training/paths/data-analytics-microsoft/) |
| **🏆 Path: Get started with Power BI** | Microsoft Learn | Abr 2023 | [Ver Trofeo Oficial](https://learn.microsoft.com/es-es/training/paths/get-started-power-bi/) |
| **Describe Power BI Desktop models** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/dax-power-bi-models/) |
| **Analyze data with Power BI** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/analyze-data-power-bi/) |
| **Get data with Power BI Desktop** | Microsoft Learn | Abr 2023 | [Ver Logro en Perfil](https://learn.microsoft.com/es-es/users/FRANCISCO-GRANDON/achievements#KSNG4KKB) |
| **Describe the capabilities of Microsoft Power BI** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/introduction-power-bi/) |
| **Get started building with Power BI** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/get-started-with-power-bi/) |
| **Explore what Power BI can do for you** | Microsoft Learn | Abr 2023 | [Ver Logro en Perfil](https://learn.microsoft.com/es-es/users/FRANCISCO-GRANDON/achievements#WRDUWC4N) |
| **Discover data analysis** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/data-analytics-microsoft/) |
| **Describe how to build applications with Power Apps** | Microsoft Learn | Abr 2023 | [Ver Módulo Oficial](https://learn.microsoft.com/es-es/training/modules/introduction-power-apps/) |
| **Power BI - Aplicación Práctica para Negocios (24 hrs)** | SENCE | 2018 | [Ver Certificado PDF](./Certificado_SENCE_Power_BI_Aplicacion_Practica_24h_2018.pdf) |
| **Excel - Manejo de Base de Datos y Gestión Avanzada (24 hrs)** | SENCE | 2018 | [Ver Certificado PDF](./Certificado_SENCE_Excel_Manejo_Base_de_Datos_24h_2018.pdf) |

---

### 💻 III. Ingeniería de Software, Python & Desarrollo Digital

| Certificación / Programa | Institución | Horas / Año | Credencial Verificada |
| :--- | :--- | :---: | :---: |
| **Capacitación Python Intermedio - Avanzado** | ASR Capacitación | 30 hrs · 2024 | [Ver Certificado PDF](./Certificado_ASR_Capacitacion_Python_Intermedio_Avanzado_30h_2024.pdf) |
| **Capacitación Python Básico y Procesamiento de Datos** | ASR Capacitación | 30 hrs · 2024 | [Ver Certificado PDF](./Certificado_ASR_Capacitacion_Python_Basico_Proceso_Datos_30h_2024.pdf) |
| **Diseño Web con HTML5 + CSS** | SENCE / Fundación Telefónica | 30 hrs · 2019 | [Ver Diploma PDF](./Diploma_SENCE_Fundacion_Telefonica_Diseno_Web_HTML5_CSS_30h_2019.pdf) |

---

### 🏢 IV. Operaciones Industriales, Finanzas & Cumplimiento Normativo

| Acreditación | Institución | Horas / Calificación | Credencial Verificada |
| :--- | :--- | :---: | :---: |
| **Supervisor de Operaciones** | Fundación Carlos Slim | 61 hrs · Nota 8.75 | [Ver Certificado PDF](./Certificado_Fundacion_Carlos_Slim_Supervisor_de_Operaciones_61h_2023.pdf) |
| **Jefe de Mantenimiento** | Fundación Carlos Slim | 61 hrs · Nota 8.89 | [Ver Certificado PDF](./Certificado_Fundacion_Carlos_Slim_Jefe_de_Mantenimiento_61h_2023.pdf) |
| **Contabilidad Empresarial** | Fundación Carlos Slim | 9 hrs · Nota 9.00 | [Ver Constancia PDF](./Constancia_Fundacion_Carlos_Slim_Contabilidad_Empresarial_9h_2023.pdf) |
| **Disciplina en el Trabajo** | Fundación Carlos Slim | 7 hrs · Nota 8.00 | [Ver Constancia PDF](./Constancia_Fundacion_Carlos_Slim_Disciplina_en_el_Trabajo_7h_2023.pdf) |
| **Prevención de Delitos en la Empresa (Ley N° 20.393)** | SENCE | 12 hrs · 2013 | [Ver Certificado PDF](./Certificado_SENCE_Prevencion_Delitos_Ley_20393_12h_2013.pdf) |
| **Gestión del Riesgo y Autocuidado ante Radiación UV** | SENCE | 16 hrs · 2025 | [Ver Certificado PDF](./Certificado_SENCE_Radiacion_UV_Gestion_Riesgo_Autocuidado_16h_2025.pdf) |

---

## 📬 Contacto & Colaboración Profesional

Abierto a colaborar en iniciativas de **transformación digital, ingeniería de datos a gran escala, diseño de agentes de IA empresariales y optimización de procesos operativos y comerciales críticos**.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Seguir-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/FranciscoGrandon)
[![Email Proyectos](https://img.shields.io/badge/Email_Outlook-francisco.grandon%40outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:francisco.grandon@outlook.com)
[![Email Corporativo](https://img.shields.io/badge/Email_Essbio-francisco.grandon%40essbio.cl-008FD3?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:francisco.grandon@essbio.cl)
[![Email Personal](https://img.shields.io/badge/Email_Personal-grandonpanxo%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:grandonpanxo@gmail.com)

</div>
