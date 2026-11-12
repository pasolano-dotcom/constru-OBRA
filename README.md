# CONSTRUOBRA 🏗️📐

**Calculadora de Cantidades, Materiales y Presupuestos para Estudiantes de Ingeniería Civil**

CONSTRUOBRA es una aplicación web responsiva e interactiva diseñada especialmente para estudiantes de los primeros semestres de Ingeniería Civil. Facilita el cálculo rápido, ordenado y libre de errores de volúmenes de concreto, dosificaciones de mezcla, cantidades de ladrillos, áreas, excavaciones con esponjamiento y presupuestos de materiales para proyectos y talleres académicos.

---

## 📌 Problema que resuelve
Durante la formación académica en ingeniería civil, los estudiantes deben calcular repetidamente cantidades de obra para ejercicios de clase, talleres de materiales y proyectos de construcción. Al hacerlo de forma manual con calculadoras convencionales y hojas dispersas:
- Se pierde tiempo valioso en operaciones repetitivas.
- Se cometen errores aritméticos en la conversión de unidades o factores de desperdicio.
- Se dificulta la estructuración rápida de presupuestos estimativos.

**CONSTRUOBRA** centraliza todas estas herramientas en una interfaz visual, pedagógica y adaptable a computadores y teléfonos móviles.

---

## 🚀 Funcionalidades Principales

1. **Calculadora de Concreto por Elemento Estructural:**
   - Cálculo de volumen en $m^3$ para columnas (rectangulares y circulares), vigas, placas/losas (macizas y aligeradas con casetón) y zapatas.
   - Multiplicador de elementos idénticos.
   - Factor de desperdicio ajustable (0% a 15%).
   - Envío directo de resultados al módulo de dosificación.

2. **Dosificación Técnica de Mezclas (Concreto y Mortero):**
   - Dosificaciones normalizadas según resistencia f'c aproximada:
     - **1:2:2** (~28 MPa / 4000 PSI) - Elementos de alta exigencia.
     - **1:2:3** (~21 MPa / 3000 PSI) - Estándar para vigas, columnas y losas.
     - **1:2:4** (~17.5 MPa / 2500 PSI) - Pisos, zapatas y contrapisos.
     - **1:3:3** (~14 MPa / 2000 PSI) - Muros de contención sencillos y pavimentos.
     - **1:3:6** (~10.5 MPa / 1500 PSI) - Solados y ciclópeos.
     - Morteros de pega y pañete (1:3, 1:4, 1:5).
   - Desglose en sacos de cemento (50 kg o 42.5 kg), arena ($m^3$), grava ($m^3$) y agua (litros).
   - Equivalencias prácticas para obra (carretillas de 0.05 $m^3$ y baldes de 19 L).
   - Traspaso automático de insumos al presupuesto.

3. **Cálculo de Mampostería (Ladrillos y Mortero de Pega):**
   - Cálculo por área neta de muro con descuento de vanos (puertas y ventanas).
   - Presets de ladrillos estándar (Tolete, Bloque No. 4, Bloque No. 5, Bloque Concreto, Personalizado).
   - Tipos de aparejo (Soga, Tizón/Cabeza, Pandereta).
   - Cálculo del volumen de mortero de pega entre juntas y sus respectivos materiales.

4. **Geometría de Obra, Áreas y Excavaciones:**
   - Áreas de terrenos, pisos y muros (rectángulo, triángulo, trapecio, círculo, forma en L).
   - Excavaciones en zanjas, pozos cilíndricos y taludes.
   - Factor de esponjamiento según tipo de suelo (común, arcilla, roca).
   - Estimación de viajes de volqueta (camiones de 6 $m^3$, 8 $m^3$, etc.).

5. **Presupuesto Integrado de Materiales:**
   - Consolidación automática de materiales calculados en otros módulos.
   - Creación y edición de partidas personalizadas con precios unitarios.
   - Cálculo de subtotal, porcentaje de imprevistos/contingencia y costo total estimado.
   - Selector de moneda (COP, USD, MXN, EUR, etc.).
   - Exportación e impresión de informe técnico académico listo para entregar.
   - Almacenamiento local (LocalStorage) en el navegador.

---

## ⚠️ Alcance y Limitaciones (Lo que NO hace)
Para mantener la integridad académica y profesional:
1. **No realiza diseños estructurales** de edificios, puentes o viviendas (cálculos de acero de refuerzo, cuantías o momentos flectores superan el alcance de la herramienta).
2. **No determina si una construcción es segura ni evalúa normas técnicas de diseño sismorresistente** (como NSR-10 u otras normas locales), ya que esto exige un profesional calificado.
3. **No realiza análisis de resistencia de materiales**, pues estos requieren ensayos destructivos de laboratorio y probetas normalizadas.
4. **No genera planos arquitectónicos ni estructurales**, enfocándose estrictamente en cómputos métricos y presupuestos estimativos.
5. **No realiza compras ni transacciones de pago a proveedores**.

---

## 💻 Tecnologías Utilizadas
- **HTML5 semántico** y **CSS3** moderno con variables y soporte de impresión.
- **Tailwind CSS** (vía CDN) para diseño responsivo mobile-first.
- **JavaScript Moderno (ES6+)** modular sin dependencias de backend.
- **Lucide Icons** para iconografía de ingeniería civil.
- **Chart.js** para gráficos interactivos de desglose de costos y materiales.

---

## 🏃 Modo de Uso
1. Abre el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Firefox, Edge, Safari) en tu celular o computador.
2. Navega entre las pestañas según el cálculo que necesites realizar.
3. Ingresa las dimensiones solicitadas y visualiza inmediatamente las fórmulas y resultados.
4. Envía los materiales calculados al **Presupuesto** para obtener el costo global del ejercicio.
5. Imprime o guarda tu informe en PDF usando la función de impresión del navegador.
