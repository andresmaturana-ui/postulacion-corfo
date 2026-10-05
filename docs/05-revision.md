# Revisión crítica de la postulación

El documento base es sólido: el instrumento es correcto, el presupuesto suma bien ($15 M + $5 M = $20 M, dentro de los topes indicados) y los riesgos están bien identificados. Estos son los puntos que un evaluador podría cuestionar, ordenados por impacto en el puntaje.

## 1. Equipo de una persona (afecta el 30 % de la nota)
Es la debilidad más grande. Capacidad (20 %) y compromiso (10 %) dependen de que haya al menos 2 personas. Si no aparece un cofundador antes de diciembre:
- consigue al menos un **asesor veterinario con carta** y nombre propio;
- en el presupuesto, mueve el segundo sueldo de socio a "personal nuevo" con un perfil concreto (por ejemplo, "ejecutiva comercial a media jornada, con experiencia en ventas a municipios").

## 2. La cifra de precisión necesita un criterio claro
"El 96 % de las mascotas llegó a su dueño" es ambiguo para un evaluador técnico. Conviene decir exactamente qué se midió (¿el perro correcto está entre los primeros *k* resultados? ¿supera el umbral de aviso?) y aclarar que es una **prueba de laboratorio** en una base pública con fotos frontales y bien encuadradas. En la calle el resultado será menor. Presentarlo así refuerza el criterio "no exagerar" y justifica el objetivo de validación técnica. Ya ajusté el texto en [02-respuestas-formulario.md](02-respuestas-formulario.md); falta confirmar el criterio.

## 3. Falta un hito de validación en terreno
Los hitos 3 y 6 miden el modelo, pero no queda claro con qué datos. Propuesta: medir el acierto con mascotas reales registradas en las clínicas piloto (ver la sugerencia en [03-hitos-presupuesto-riesgos.md](03-hitos-presupuesto-riesgos.md)).

## 4. Ojo con las "ventas" accidentales
El modelo de negocio incluye placas de collar y publicidad. Antes de postular **no se puede vender ninguna placa ni cobrar ningún aviso**, aunque sea simbólico. Las 500 placas de los pilotos deben ser regaladas.

## 5. Licencias
- Detector entrenado con software AGPL: ya está en los riesgos y tiene su hito (mes 3). Bien.
- DINOv2: Meta lo publicó con licencia Apache 2.0, que permite uso comercial. Conviene mencionarlo para mostrar que el tema está revisado.
- DogFaceNet: confirma bajo qué licencia se distribuye la base y cítala como fuente de evaluación, no de entrenamiento comercial, salvo que la licencia lo permita.

## 6. Competencia
Existen apps extranjeras de reconocimiento facial de mascotas. Si el texto dice "Kiltrazo es el único", un evaluador que las encuentre en Google le restará puntos. Es mejor nombrarlas y explicar la diferencia: funciona en el navegador sin app nativa, integra clínicas y municipios, y está pensado para el contexto chileno (Ley Cholito y Registro Nacional de Mascotas).

## 7. Mercado sin números
La sección de mercado todavía no tiene cifras. Las más importantes son el **número de clínicas veterinarias en Chile** y el **precio por clínica**, porque de ahí sale un mercado alcanzable creíble (por ejemplo, "N clínicas × $X al mes × 12").

## 8. Ley 21.719
Las caras de las mascotas no son datos personales, pero los datos del tutor (nombre, teléfono, ubicación de la casa y las alertas por radio de 5 km) sí lo son. La ubicación es lo más delicado. Basta una frase en la solución: "la ubicación del tutor nunca se muestra; las alertas usan una zona aproximada".

## 9. "Construido con IA en pocas semanas"
Puede leerse como capacidad de ejecución (bien) o como poca profundidad técnica (mal). Por eso ajusté el texto para destacar lo que se construyó, incluido el modelo y su evaluación, antes de mencionar cómo se hizo.
