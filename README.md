# TPI - Módulo de Adaptación Inteligente de Mods por IA - Larian Studios

**Alumna:** Morena Loggia
**Materia:** Organización Empresarial - Tecnicatura Universitaria en Programación (UTN)

## Descripción del Sistema
Este proyecto documenta el diseño de un módulo de software basado en Inteligencia Artificial para Larian Studios. Su objetivo es adaptar mods creados en PC para que puedan ser ejecutados de forma segura en consolas (PlayStation y Xbox), automatizando la traducción de código y sanitizando los paquetes para cumplir con las normativas de las plataformas.

## 📊 Indicadores de Control y Estándares de Desempeño
*   **Tiempo de Adaptación:** ≤ 15 minutos por mod.
    *   *Fórmula:* (Suma del tiempo de procesamiento de todos los mods) / (Total de mods procesados).
    *   *Frecuencia:* Medición diaria.
*   **Tasa de Aprobación en QA:** ≥ 95% de éxito.
    *   *Fórmula:* (Mods aprobados en primera instancia / Total de mods evaluados) * 100.
    *   *Frecuencia:* Medición semanal.
*   **Tasa de Rechazo de Consolas:** ≤ 5%.
    *   *Fórmula:* (Mods rechazados por Sony/Microsoft / Total de mods enviados) * 100.
    *   *Frecuencia:* Medición mensual.
*   **Tiempo de Resolución de Tickets:** ≤ 24 horas.
    *   *Fórmula:* Promedio de tiempo entre la apertura del ticket y su cambio a estado "Resuelto".
    *   *Frecuencia:* Monitoreo continuo (en tiempo real).

## 📋 Backlog Ágil (Historias de Usuario)
*   **HU1 (Modder):** Como creador de contenido, quiero subir mi mod de PC y que la IA lo adapte automáticamente, para poder ofrecer mi contenido a los jugadores de consola sin tener que aprender lenguajes de programación específicos.
    *   *Criterio de aceptación:* El mod debe procesarse en menos de 15 minutos. El sistema debe notificar al modder por correo si la validación es exitosa o si fue rechazada.
*   **HU2 (Ingeniero QA):** Como Ingeniero de Control de Calidad, quiero visualizar un reporte detallado de los errores detectados por la IA, para asegurar que el mod no romperá la estabilidad del juego antes de enviarlo a aprobación final.
    *   *Criterio de aceptación:* El reporte debe detallar el tipo de error, la línea de código afectada y el nivel de severidad. Debe permitir exportar el reporte en formato PDF.
*   **HU3 (Líder de Proyecto):** Como Líder de Proyecto, quiero acceder a un panel de control con las métricas de tiempo y tasa de aprobación, para verificar el rendimiento del sistema y tomar decisiones estratégicas.
    *   *Criterio de aceptación:* El panel debe actualizarse en tiempo real. Debe incluir filtros por fecha, tipo de mod y consola de destino.

## 🤖 Declaración de Uso de IA
Para la confección de este trabajo, se utilizaron herramientas de Inteligencia Artificial Generativa (Gemini, Claude y DeepSeek) como asistentes para la estructuración de textos, la optimización de la redacción técnica y la sugerencia de layouts para el diagrama BPMN. 

**Prompts utilizados:** Se emplearon instrucciones específicas para que la IA actuara como experta en BPMN 2.0, identificando Pools, Lanes, compuertas exclusivas y eventos de mensaje, así como para estructurar el Backlog Ágil con Historias de Usuario bajo el formato formal.

**Responsabilidad y Corrección Humana:** Asumo la plena responsabilidad intelectual sobre el contenido aquí presentado. Todas las sugerencias de la IA fueron revisadas, validadas y adaptadas por mi criterio profesional. Se auditó que la lógica del proceso, los indicadores y la estructura de datos coincidan con las entregas anteriores y con la bibliografía de la cátedra. Se corrigieron manualmente las imperfecciones generadas por los modelos y se ajustó la redacción para asegurar la coherencia conceptual.
