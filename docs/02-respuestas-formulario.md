# Respuestas para el formulario

Textos para copiar y pegar. Los corchetes `[ ]` se completan con datos reales.
Las partes marcadas con ✏️ se ajustaron según la [revisión](05-revision.md).

### Nombre del proyecto
Kiltrazo: reconocimiento facial de mascotas para devolverlas a casa y conectar a sus familias con veterinarias y municipalidades.

### Resumen (una línea)
Kiltrazo devuelve a casa a perros y gatos perdidos reconociendo su cara con cualquier celular, sin lector de chip, y financia el servicio gratuito con software para clínicas veterinarias y municipalidades.

### Problema
Cuando una mascota se pierde en Chile, quien la encuentra casi nunca puede saber de quién es: las placas con datos se caen o no existen, y leer el microchip exige un lector que solo tienen algunas clínicas y municipios. Los dueños dependen de carteles y grupos de Facebook, y muchas mascotas terminan en la calle o en refugios. Al mismo tiempo, la Ley 21.020 (Ley Cholito) obliga a los municipios a registrar y controlar mascotas, y muchos no tienen herramientas digitales simples para hacerlo. Las clínicas veterinarias pequeñas y los veterinarios a domicilio gestionan su agenda en cuadernos, WhatsApp o planillas.

✏️ El Registro Nacional de Mascotas tiene un sistema de alertas por extravío, pero la búsqueda depende del microchip. Según SUBDERE, de 6.173 alertas activadas solo 1.531 terminaron con el animal devuelto (≈25 %) [actualizar con una cifra reciente o citar la fecha del balance].

[Agregar 1 o 2 cifras oficiales: hogares con mascotas, animales sin dueño o con extravío, según la encuesta de SUBDERE, con la fuente y el año.]

### Solución
Kiltrazo es una app web instalable (funciona en iPhone y Android sin pasar por las tiendas) con tres módulos sobre la misma base de datos:

1. **App para tutores (gratis):** el tutor registra a su mascota grabando un video corto de su cara. Si alguien encuentra un perro o un gato, usa el reconocimiento facial para devolverlo a casa: la app lo compara con todas las mascotas registradas y avisa al dueño al instante, sin mostrar sus datos personales. Incluye alertas a vecinos en un radio de 5 km, una placa de collar con QR y la opción de pedir hora al veterinario.
2. **Kiltrazo Clínica:** agenda, fichas clínicas, vacunas, reservas online, modo para veterinarios a domicilio, página pública y buscador de veterinarios. Cada paciente que la clínica atiende queda registrado y protegido.
3. **Kiltrazo Municipal:** operativos de chip y vacunación con reserva online, registro de animales con su estado (comunitario, en adopción, etc.), tablero de perdidos y encontrados de la comuna y apoyo para inscribirlos en el Registro Nacional de Mascotas.

### Innovación y diferenciación
- **No necesita hardware:** basta la cámara de un celular. El chip requiere un lector y la placa se pierde, pero la cara siempre está.
- **Tecnología propia:** detector de cabezas entrenado por Kiltrazo, modelo de visión por computador DINOv2 y búsqueda vectorial. Funciona dentro del navegador, sin descargar una app.
- ✏️ **Resultado medido, no prometido:** en una prueba con 1.393 perros de la base pública DogFaceNet (Mougeot, Li y Jia, 2019), el perro correcto apareció en primer lugar en el 92,9 % de las búsquedas, y en el 96 % de los casos el dueño correcto habría recibido el aviso [precisar el criterio, por ejemplo "entre los 5 primeros resultados"]. Es una prueba de laboratorio; la validación en terreno es uno de los objetivos del proyecto.
- **Privacidad desde el diseño:** quien encuentra la mascota nunca ve los datos del dueño, y los consentimientos se registran según la Ley 21.719.
- **Efecto red:** cada clínica y municipio que usa Kiltrazo registra mascotas, y cada mascota registrada hace más útil el reconocimiento para todos.

### Competencia
✏️ Ver el análisis completo en [06-competencia.md](06-competencia.md).

Fuera de Chile, el reconocimiento de mascotas por imagen ya demostró que funciona: Petco Love Lost (EE.UU.) dice haber reunido a más de 100.000 mascotas con sus familias, Petnow (Corea) identifica perros por la huella de la nariz y ya vende a gobiernos locales, y Ring (Amazon) usa las cámaras de los vecinos para buscar perros perdidos. Ninguno opera en Chile, y todos dependen de grandes redes propias (refugios, cámaras) o de que el tutor registre a su mascota por su cuenta.

En Chile, las alternativas son el Registro Nacional de Mascotas de SUBDERE (registratumascota.cl), que permite reportar una mascota extraviada, pero quien la encuentra solo puede buscarla con el número de microchip, lo que exige un lector, los grupos de Facebook e Instagram, las placas QR y apps comunitarias de perdidos y encontrados como PetLoc [ajustar tras revisarla]. El software veterinario disponible, como [1 o 2 nombres], no se conecta con las mascotas perdidas.

Kiltrazo es la única solución que encontramos que une el reconocimiento facial desde cualquier navegador (sin app ni hardware), con precisión medida, y el software de gestión de clínicas y municipios. Esto resuelve el principal problema de estas plataformas, que es conseguir que se registren mascotas: cada atención en una clínica y cada operativo municipal suman una mascota reconocible.

### Clientes y mercado
- **Usuarios (gratis):** hogares con perros o gatos en Chile. [Cifra oficial de la Encuesta Nacional de Tenencia Responsable de SUBDERE.]
- **Clientes que pagan:** clínicas veterinarias y veterinarios a domicilio (suscripción mensual), municipalidades (convenio anual; hay 346 comunas en Chile) y marcas del rubro (publicidad en el buscador de veterinarios).
- **Mercado inicial:** Región Metropolitana; después regiones y Latinoamérica (la app ya funciona en cualquier navegador).
- ✏️ [Agregar el número de clínicas veterinarias en Chile, con su fuente: es el dato que más sostiene los ingresos.]

### Modelo de negocio
Kiltrazo es gratis para los tutores, lo que hace crecer la base de mascotas. Los ingresos vienen de la suscripción a Kiltrazo Clínica [precio: $X al mes por clínica], el convenio municipal anual, la publicidad segmentada en el buscador y las placas de collar. Las promociones a tutores se envían solo con su permiso expreso, y la base de datos nunca se vende.

### Escalabilidad
El costo por usuario es casi cero porque el reconocimiento corre en el celular de cada usuario. Un municipio o una clínica puede sumarse por su cuenta, desde el navegador y sin instalar nada. La misma plataforma sirve para cualquier país hispanohablante cambiando los códigos de teléfono y los mapas, y después en portugués para Brasil.

### Estado de avance
Producto funcionando en kiltrazo.cl con los tres módulos, notificaciones push, manuales en PDF para clínicas y tutores, y acuerdos de piloto listos (3 meses gratis). Mascotas registradas: [ ]. Clínicas en piloto: [ ]. Municipios interesados: [ ].

### Impacto
Menos mascotas en la calle y en refugios, apoyo a los municipios para cumplir la Ley Cholito y digitalización de clínicas pequeñas. Encaja en los focos de ciudades sostenibles, salud ("Una Salud": control de zoonosis y vacunación) y gobierno digital.

### Equipo
Andrés Maturana, fundador: [experiencia, estudios y por qué él]. ✏️ Diseñó y construyó el producto completo (tres módulos, modelo de reconocimiento y evaluación técnica) en pocas semanas, apoyándose en herramientas de IA para programar, lo que demuestra capacidad de ejecución a bajo costo. [Agregar a un socio o asesor veterinario y a un asesor comercial o municipal, aunque sea con carta de compromiso.]
