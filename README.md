# 🥗 KcalFlow v2

Calculadora de calorías todo en uno: **comidas, ejercicio, suplementos y peso corporal** en una sola app web, sin instalación, sin cuentas y sin servidor.

## ✨ Funciones

- **Hoy:** anillo con las kcal que te quedan (comidas + suplementos − ejercicio) y barras de proteína, carbohidratos y grasas.
- **Comidas:** desayuno, almuerzo, merienda, cena y snack con kcal y macros. Si solo pones macros, calcula las kcal (4·P + 4·C + 9·G).
- **Ejercicio:** 8 actividades. Las kcal se estiman con MET × peso × tiempo.
- **Suplementos:** accesos rápidos (whey, creatina, cafeína, BCAA…) o personalizados.
- **Peso corporal:** registro diario y gráfica de los últimos 14 registros.
- **Perfil y objetivo:** gasto diario con la fórmula Mifflin-St Jeor y objetivo de −500 a +500 kcal.
- **Historial:** gráfica de 7 días, resumen mensual y detalle por día.
- **Análisis con IA** (solo dentro de claude.ai; se oculta sola en otros hostings): consejos sobre qué mejorar en alimentación y ejercicio.
- Modo claro/oscuro automático, diseño adaptado a móvil y PC, y animación de apertura de 1 segundo.

## 🆕 Novedades de la v2

- Fechas en hora local (antes UTC) y cambio de día automático.
- Nombres de comidas escapados (sin inyección de HTML) y sin cifras negativas.
- Datos guardados corruptos o incompletos ya no rompen la app.
- Carga protegida sin `eval`, compatible con más hostings.
- Sin zoom al tocar campos en iOS y animación de apertura de 1 s.

## 🚀 Cómo subirla

Es un único archivo estático. Sube `index.html` y `LICENSE` a la raíz de cualquiera de estos servicios:

- **Netlify:** arrastra la carpeta a *app.netlify.com/drop*.
- **GitHub Pages:** sube los archivos a un repositorio y activa *Settings → Pages*.
- **Vercel / Cloudflare Pages:** crea un proyecto estático con la carpeta.

No necesita compilación ni dependencias.

## 💾 Datos y privacidad

Todo se guarda en el `localStorage` del navegador de cada persona. No se envía nada a ningún servidor. Si se borran los datos del navegador, se pierde el historial.

## ⚠️ Aviso

Las cifras son estimaciones orientativas y no sustituyen el consejo de un médico, nutricionista o entrenador.

## 🧪 Pruebas

Se comprobaron la carga, el cálculo del gasto (TDEE), comidas, ejercicio, suplementos, peso, borrado, historial, escape de HTML y el cambio de día en distintas zonas horarias.

## 📄 Licencia

[MIT](LICENSE) © 2026 RamiOO7
