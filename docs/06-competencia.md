# Competencia: reconocimiento de mascotas por imagen

Investigación de octubre de 2026. **Antes de postular, conviene abrir cada app y confirmar su estado y si opera en Chile**: varias de estas fuentes son notas de prensa.

## Registro Nacional de Mascotas (SUBDERE): el sistema público de referencia

Creado por la Ley 21.020 (Ley Cholito); funciona en [registratumascota.cl](https://registratumascota.cl). La inscripción es gratuita y obligatoria y la validan los municipios.
- **Reportar una pérdida:** el tutor entra con ClaveÚnica → "Mis Mascotas" → "Reportar Extraviado". La ley también obliga a avisar al municipio dentro de 3 días hábiles.
- **Buscar una mascota encontrada:** [consulta pública](https://registratumascota.cl/consultas.xhtml) **solo con el número de microchip** (15 dígitos) u otro identificador externo. Sin un lector de chip, quien encuentra al animal no puede usarla.
- **Resultados publicados por SUBDERE:** 6.173 alertas activadas (5.463 por extravío y 710 por robo), de las cuales 1.531 terminaron con el animal devuelto (≈25 %). ⚠️ La cifra viene de un balance de SUBDERE a los tres años de la ley, así que es antigua: hay que buscar una más reciente o citarla con su fecha.
- Según SUBDERE, hay **más de 2 millones** de animales inscritos [confirmar la fecha de la cifra].

**Cómo presentarlo:** como un **complemento**, no como competencia. El registro tiene la identidad legal del animal (el chip), y Kiltrazo agrega la búsqueda por la cara para quien no tiene lector. El módulo municipal ya ayuda a inscribir mascotas en el registro. A futuro, se podría proponer a SUBDERE vincular ambos sistemas mediante el número de chip.

**Ojo:** también existen sitios privados con nombres parecidos, como "SOS Mascotas · Registro Nacional" (sosmascota.cl), que no son el registro oficial.

## Resumen

| Competidor | Origen y mercado | Cómo identifica | Modelo de negocio | ¿Opera en Chile? |
|---|---|---|---|---|
| **PetLoc** | 🇨🇱 Chile (Francisco Cerda) | Fotos de perdidos y encontrados en un mapa; [verificar si hace *matching* automático por imagen] | Gratis; comunidad, campañas solidarias, buscador de veterinarias y tiendas | **Sí: es el competidor local directo** |
| **Petnow** | 🇰🇷 Corea del Sur; Asia y ahora EE.UU. | Huella de la nariz (perros) y cara (gatos); dice alcanzar 99 % de precisión | App para tutores + venta al sector público (en 2025 firmó un acuerdo para licitaciones municipales en EE.UU., empezando por Nueva York) | No encontré evidencia |
| **Petco Love Lost** (incluye Finding Rover, que compró) | 🇺🇸 EE.UU. | *Matching* de fotos con más de 500 marcadores visuales | Gratis, financiado por la fundación Petco Love; integra más de 3.000 refugios, Nextdoor y Ring | No |
| **Ring Search Party** (Amazon) | 🇺🇸 EE.UU. (2025; abierto a todos desde febrero de 2026) | IA en las cámaras de los vecinos que detecta al perro reportado | Gratis, para atraer clientes a sus cámaras | No |
| **NOSEiD** (Iams / Mars) | EE.UU. | Huella de la nariz con la cámara del celular | Gratis, como marketing de una marca de alimento | [verificar si sigue activa] |
| **PiP** | Canadá / EE.UU. | Reconocimiento facial | Suscripción pagada por el tutor | [verificar] |

## Qué nos dice esto (útil para la postulación)

1. **La demanda está validada afuera.** Petco Love Lost dice haber reunido más de 100.000 mascotas con sus dueños, y Ring, más de un perro al día. Es un argumento para el criterio de *relevancia del problema*: no es una idea no probada, sino algo que todavía no existe bien resuelto en Chile.
2. **El canal municipal también está validado.** Petnow apuesta por las licitaciones públicas en EE.UU. Eso respalda el módulo Kiltrazo Municipal.
3. **Ningún competidor internacional integra el software de la clínica.** Todos dependen de que el tutor registre a su mascota por su cuenta, o de grandes redes (refugios en EE.UU., cámaras Ring). Kiltrazo resuelve ese problema de arranque con las clínicas y los municipios, y eso conviene explicarlo.
4. **Nariz vs. cara.** Petnow y NOSEiD usan la nariz: es más precisa, pero exige una foto de cerca con el animal quieto, algo difícil cuando quien lo encuentra es un perro asustado en la calle. La cara se puede fotografiar a distancia. Hay que tratarlo como una decisión de diseño y no decir que es "mejor" sin datos.
5. **PetLoc es el riesgo real.** Es chileno, gratis y ya tiene comunidad y buscador de veterinarias. Antes de postular, instálalo y revisa qué hace exactamente. La diferencia de Kiltrazo debería estar en el reconocimiento automático con precisión medida y en el software de gestión para clínicas y municipios. No hay que decir que PetLoc "no tiene IA" sin haberlo comprobado.

## Texto propuesto para el formulario (sección Competencia)

> Fuera de Chile, el reconocimiento de mascotas por imagen ya demostró que funciona: Petco Love Lost (EE.UU.) dice haber reunido a más de 100.000 mascotas con sus familias, Petnow (Corea) identifica perros por la huella de la nariz y ya vende a gobiernos locales, y Ring (Amazon) usa las cámaras de los vecinos para buscar perros perdidos. Ninguno opera en Chile, y todos dependen de grandes redes propias (refugios, cámaras) o de que el tutor registre a su mascota por su cuenta.
>
> En Chile, las alternativas son el Registro Nacional de Mascotas de SUBDERE (registratumascota.cl), que permite reportar una mascota extraviada, pero quien la encuentra solo puede buscarla con el número de microchip, lo que exige un lector, los grupos de Facebook e Instagram, las placas QR y apps comunitarias de perdidos y encontrados como PetLoc [ajustar tras revisarla]. El software veterinario disponible, como [1 o 2 nombres], no se conecta con las mascotas perdidas.
>
> Kiltrazo es la única solución que encontramos que une el reconocimiento facial desde cualquier navegador (sin app ni hardware), con precisión medida, y el software de gestión de clínicas y municipios. Esto resuelve el principal problema de estas plataformas, que es conseguir que se registren mascotas: cada atención en una clínica y cada operativo municipal suman una mascota reconocible.

## Fuentes
- [Registro Nacional: consulta de animales encontrados](https://registratumascota.cl/consultas.xhtml) · [24horas: ¿qué hago si se perdió mi mascota?](https://www.24horas.cl/tendencias/mascotas/que-hago-si-se-perdio-mi-mascota) · [SUBDERE: balance a 3 años de la ley](https://www.subdere.gov.cl/sala-de-prensa/programa-mascota-protegida-hace-positivo-balance-de-los-tres-a%C3%B1os-de-la-ley-de) · [SUBDERE: más de 2 millones registrados](https://www.subdere.gov.cl/sala-de-prensa/aniversario-de-%E2%80%98%E2%80%99ley-cholito%E2%80%99%E2%80%99-m%C3%A1s-de-2-millones-de-animales-de-compa%C3%B1%C3%ADa-han-sido)
- [PetLoc – sitio](https://petloc.cl/) · [24horas: app creada por chileno](https://www.24horas.cl/tendencias/redes-sociales/aplicacion-creada-por-chileno-permite-encontrar-mascotas-perdidas) · [Google Play](https://play.google.com/store/apps/details?id=com.petloc.app)
- [Petnow](https://www.petnow.io/en) · [TechCrunch sobre Petnow (2023)](https://techcrunch.com/2023/09/20/petnow-claims-to-be-able-to-identify-dogs-and-cats-from-their-snouts) · [Acuerdo de Petnow para el sector público de EE.UU. (2025)](https://finance.yahoo.com/news/petnow-forms-u-partnership-advance-140000442.html)
- [Cómo funciona Petco Love Lost](https://support.lost.petcolove.org/hc/en-us/articles/1500007704782-How-does-Petco-Love-Lost-work) · [CBS News](https://www.cbsnews.com/news/ai-lost-pets-petco-love-facial-recognition/) · [AAHA](https://www.aaha.org/trends-magazine/publications/how-ai-facial-recognition-is-bringing-lost-pets-home/) · [CB Insights: Finding Rover](https://www.cbinsights.com/company/finding-rover)
- [Amazon: Ring Search Party](https://www.aboutamazon.com/news/devices/ring-search-party-for-dogs-united-states-missing-pets) · [TechCrunch, febrero de 2026](https://techcrunch.com/2026/02/02/ring-brings-its-search-party-feature-for-finding-lost-dogs-to-non-ring-camera-owners/)
- [NOSEiD (DPReview)](https://www.dpreview.com/news/8131379955/noseid-app-helps-reunite-lost-dogs-with-their-owners-using-photos-of-their-noses)
- [Slate: Finding Rover y PiP (2019)](https://slate.com/technology/2019/07/dog-facial-recognition-privacy-finding-rover-megvii.html)
