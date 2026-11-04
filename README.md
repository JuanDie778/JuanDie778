# ¡Hola! Soy Juan Diego 👋
**Quantitative Systems Developer & High-Agency Technical Builder**  
*Valencia, Spain • Specializing in Scientific Machine Learning (SciML), Stochastic Systems & FinTech Architectures*

Me apasiona hacer fácil lo difícil. Utilizo una mentalidad analítica influenciada por la rigurosidad de la física, las matemáticas aplicadas y la perspectiva de la filosofía para modelar sistemas complejos y tomar decisiones óptimas basadas en datos. 

Mi aprendizaje es completamente autónomo y nace de un entusiasmo genuino por la tecnología y la resolución de problemas reales. No espero a que me enseñen las soluciones; investigo los primeros principios y construyo la infraestructura matemática y de software para encontrarlas.

---

## 🏆 Proyecto Insignia: KineTopus-Engine (SciML Research)

### 🔬 **[KineTopus-Engine — Descubrimiento de Ecuaciones Diferenciales Estocásticas (SDEs)](https://github.com/JuanDie778/KineTopus-Engine)**
> *Mi principal proyecto de investigación en física computacional aplicada a series temporales complejas y mercados dinámicos.*

* 📄 **Preprint Científico en SSRN:** [SSRN Abstract 7431018](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7431018)
* 🚀 **Demostrador en Vivo:** Desplegado en Hugging Face Spaces con telemetría interactiva.
* **¿Qué problema resuelve?**  
  Los indicadores técnicos clásicos (medias móviles, osciladores) siempre van con retraso (*lag*) y las redes neuronales opacas suelen fallar ante cambios de régimen. KineTopus descubre analíticamente la "ecuación física gobernante" que describe la dinámica del dato en tiempo real.
* **Aspectos Técnicos Destacados:**
  * Inferencia ultra-rápida en CPU (vectorizada en NumPy puro, sin requerir GPUs costosas).
  * Rigor causal estricto mediante particionado *Walk-Forward* (cero sobreajuste temporal).
  * 0.0% de singularidades numéricas evaluadas bajo simulaciones de Monte Carlo.

---

## 🛠️ Motores Sectoriales de Código Abierto (Open Source Sectorial Engines)

*Colección de librerías y soluciones de software diseñadas para resolver ineficiencias críticas en industrias clave:*

### 🏦 **[crossborder-fx-reconciliation — Pagos Internacionales y FinTech](https://github.com/JuanDie778/crossborder-fx-reconciliation)**
* **El Problema:** En transferencias internacionales B2B (universidades, comercio exterior), los bancos intermediarios suelen deducir comisiones opacas no notificadas (*fee-skimming* de 15€–35€) y los tipos de cambio fluctúan mientras el dinero viaja, provocando que lleguen facturas incompletas y descuadres contables que exigen semanas de revisión manual.
* **La Solución:** Un motor de conciliación bancaria automatizada con un libro mayor inmutable de partida doble (encadenamiento SHA-256). Prohíbe el uso de números flotantes para evitar errores de céntimos y simula el riesgo cambiario mediante procesos estocásticos de reversión a la media (Ornstein-Uhlenbeck) con métricas de $\text{VaR}_{99\%}$.
* **¿Dónde se aplica?** Pasarelas de pago transfronterizas (Flywire, Wise, Stripe) y departamentos de tesorería corporativa.

### ⚙️ **[whitebox-dyn-discovery — Mantenimiento Predictivo e Industria 4.0](https://github.com/JuanDie778/whitebox-dyn-discovery)**
* **El Problema:** En maquinaria industrial crítica (compresores de frío, turbinas, motores), las redes neuronales estándar son "cajas negras": no pueden explicar por qué fallan y requieren hardware muy caro para correr en la fábrica.
* **La Solución:** Identifica la ecuación matemática exacta del desgaste físico usando técnicas de SciML (SINDy y regularización polinómica Savitzky-Golay $C^2$ que filtra $4.7\times$ el ruido de los sensores). Realiza pronósticos en **0.32 milisegundos en CPU estándar**, permitiendo anticipar averías directamente en el microcontrolador de la máquina.
* **¿Dónde se aplica?** Gemelos digitales, plantas industriales, monitorización de flotas y robótica.

### 🥬 **[perishable-flow-engine — Retail, Supermercados y Dark Stores](https://github.com/JuanDie778/perishable-flow-engine)**
* **El Problema:** Vender productos frescos (fruta, verdura, carne) en e-commerce tiene una trampa matemática asimétrica: si compras de más, la comida caduca y se tira a la basura (pérdida directa de margen); si compras de menos, el cliente recibe el pedido incompleto y se va a la competencia.
* **La Solución:** Un motor estocástico de inventario que simula miles de escenarios de demanda y retrasos de proveedores bajo rotación FEFO estricta (*First Expired, First Out*). Encuentra el punto exacto de reposición para maximizar el margen neto, logrando más del 99% de disponibilidad con 0% de comida desperdiciada.
* **¿Dónde se aplica?** Cadenas de supermercados (Mercadona Tech, Consum, Carrefour), dark stores de delivery rápido y distribución farmacéutica perecedera.

### 🎟️ **[event-yield-manager — Ticketing, Conciertos y Ocio Nocturno](https://github.com/JuanDie778/event-yield-manager)**
* **El Problema:** Los eventos masivos pierden miles de euros fijando precios estáticos de entradas (o cobrando demasiado pronto o dejando salas medio vacías). Además, en la puerta de acceso el internet móvil suele colapsar por saturación de red, provocando colas interminables o tickets duplicados por fraude.
* **La Solución:** Un sistema integral que ajusta los precios en tiempo real según el ritmo de venta deseado (+8.5% de recaudación optimizada) y un motor de validación de entradas fuera de línea mediante algoritmos distribuidos (**CRDTs G-Set** con firmas HMAC-SHA256 en 17 microsegundos), permitiendo escanear accesos sin internet y sin riesgo de duplicidad.
* **¿Dónde se aplica?** Plataformas de venta de entradas (Fourvenues, Ticketmaster, DICE), festivales y recintos de ocio.

---

## 💡 Mindset Operativo & Filosofía de Ingeniería
* **Primeros Principios:** Abordo la computación y las matemáticas no como utilidades aisladas, sino como el instrumental para modelar el orden y el caos en sistemas complejos.
* **Cero Placeholders (*Zero Placeholders*):** Rechazo el código cosmético o superficial. Todo modelo cuenta con suites de pruebas completas, validación causal y fundamentación algebraica reproducible.
* **Alta Agencia Ejecutiva:** Capacidad probada para definir arquitecturas técnicas, aprender dominios complejos con rapidez y entregar código en producción sin requerir supervisión paso a paso.

---

## 📬 Contacto & Disponibilidad
* 📍 **Ubicación:** Valencia Capital, España (Disponibilidad Presencial / Híbrida)
* 💼 **LinkedIn:** [linkedin.com/in/juan-diego-ussa-aponte-20152924a](https://www.linkedin.com/in/juan-diego-ussa-aponte-20152924a/)
* 📧 **Email:** [ussaapontejuandiego@gmail.com](mailto:ussaapontejuandiego@gmail.com)
* 📄 **Preprint SSRN:** [SSRN: 7431018](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7431018)
