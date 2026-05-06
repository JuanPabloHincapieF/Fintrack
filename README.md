# FinTrack - Control de Gastos Personales

![Android](https://img.shields.io/badge/Platform-Android-green?logo=android)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-purple?logo=kotlin)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-blue)

> Aplicación Android para el registro, categorización y análisis de gastos e ingresos personales.

---

## Descripción del Proyecto

**FinTrack** es una aplicación móvil nativa para Android diseñada para ayudar a los usuarios a llevar un registro detallado y organizado de sus gastos e ingresos personales. La aplicación permite categorizar transacciones, establecer presupuestos mensuales, visualizar tendencias de gasto y recibir alertas cuando se acerca a los límites establecidos.

El objetivo principal de FinTrack es ofrecer una herramienta sencilla pero poderosa que permita a cualquier persona tomar el control de su economía personal de forma intuitiva, sin necesidad de conocimientos contables avanzados.

| Campo            | Detalle                                              |
|------------------|------------------------------------------------------|
| Nombre           | FinTrack                                             |
| Plataforma       | Android (API 24+, Android 7.0 en adelante)           |
| Lenguaje         | Kotlin / Java con Android Studio                     |
| Categoría        | Finanzas Personales / Productividad                  |
| Público objetivo | Adultos entre 18 y 55 años                           |

---

## Exposición del Problema

Una gran parte de la población no lleva un registro ordenado de sus gastos personales. Según estudios de educación financiera en América Latina, más del 60% de los adultos afirma no tener claridad sobre en qué gasta su dinero mensualmente. Esta falta de control genera problemas como el sobreendeudamiento, la incapacidad de ahorrar y el estrés financiero.

**Deficiencias de las soluciones actuales:**

- Las hojas de cálculo (Excel, Google Sheets) requieren configuración manual y conocimiento técnico.
- Las aplicaciones bancarias solo muestran movimientos, pero no ofrecen análisis ni categorización.
- Muchas apps de finanzas disponibles son complejas o requieren suscripciones costosas.
- La mayoría no están optimizadas para el contexto latinoamericano (monedas locales, hábitos regionales).

**Solución:** FinTrack resuelve este problema con una aplicación ligera, gratuita y fácil de usar que permite registrar una transacción en menos de 5 segundos y visualizar reportes claros para tomar mejores decisiones financieras.

---

## Plataforma

- **Sistema Operativo:** Android 7.0 Nougat (API 24) o superior
- **Cobertura estimada:** ~95% de dispositivos Android activos

| Tecnología        | Uso                                         |
|-------------------|---------------------------------------------|
| Kotlin            | Lenguaje principal de desarrollo            |
| Android Studio    | IDE oficial para desarrollo Android         |
| Room Database     | Almacenamiento local de datos (SQLite)      |
| MVVM Architecture | Patrón de diseño Model-View-ViewModel       |
| MPAndroidChart    | Biblioteca para gráficos y visualización    |
| GitHub            | Control de versiones y repositorio          |

---

## Interfaz de Usuario e Interfaz de Administrador

### Interfaz de Usuario (UI)

Diseñada bajo los principios de **Material Design 3**, asegurando una experiencia visual moderna, accesible y consistente.

**Pantallas principales:**

- **Dashboard / Inicio:** resumen del mes, saldo disponible y últimas transacciones.
- **Registro de Transacción:** formulario rápido para ingresar monto, categoría, fecha y nota.
- **Historial:** lista filtrable por fecha, categoría y tipo (ingreso/gasto).
- **Presupuestos:** visualización del progreso de cada categoría respecto al límite definido.
- **Reportes y Gráficos:** gráficas de pastel y barras para análisis mensual.
- **Configuración:** moneda, notificaciones, categorías personalizadas y copia de seguridad.

### Interfaz de Administrador

Panel web interno (back-office) para gestión técnica y operativa de la aplicación.

**Funcionalidades:**

- Gestión de usuarios registrados y estadísticas de uso (anónimas y agregadas).
- Administración de categorías predeterminadas de gastos e ingresos.
- Monitoreo de errores y reportes de fallos (crash reports).
- Publicación de actualizaciones y notificaciones push masivas.
- Gestión de contenidos educativos (consejos financieros dentro de la app).

---

## Funcionalidad

### Funcionalidades Principales

| # | Funcionalidad             | Descripción                                                                 |
|---|---------------------------|-----------------------------------------------------------------------------|
| 1 | Registro de transacciones | Agregar ingresos y gastos con monto, categoría, fecha y descripción.        |
| 2 | Categorización automática | Clasificación inteligente basada en palabras clave y aprendizaje del usuario.|
| 3 | Presupuestos por categoría| Definir límites de gasto mensuales y recibir alertas al superarlos.         |
| 4 | Reportes visuales         | Gráficos de barras, pastel y líneas con tendencias de gasto.                |
| 5 | Alertas y notificaciones  | Avisos cuando el gasto supera el 80% y el 100% del presupuesto.             |
| 6 | Múltiples monedas         | Soporte para COP, USD, EUR y otras monedas con conversión.                  |
| 7 | Copia de seguridad        | Exportar datos a CSV o hacer respaldo en Google Drive.                      |
| 8 | Modo oscuro               | Interfaz adaptable a las preferencias del sistema.                          |

### Funcionalidades Futuras (v2.0)

- Sincronización con cuentas bancarias mediante Open Banking API.
- Módulo de metas de ahorro con seguimiento de progreso.
- Presupuestos compartidos con pareja o familia.
- Integración con asistente de voz para registro por voz.

---

## Diseño — Wireframes
<img width="1845" height="1028" alt="image" src="https://github.com/user-attachments/assets/20360a15-a17d-4732-a40e-e38cf5cb86d5" />
