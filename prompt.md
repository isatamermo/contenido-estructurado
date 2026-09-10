# Prompt maestro · Información estructurada

Este archivo contiene una instrucción base para utilizar IA como apoyo
en la investigación, organización y transformación de información.

La idea no es pedir directamente una página terminada.

El flujo de trabajo es:

```text
INFORMACIÓN
↓
MARKDOWN
↓
HTML SEMÁNTICO
↓
CSS
```

---

# Prompt base

Quiero construir un documento digital sobre:

**[TEMA]**

Necesito organizar información sobre:

**[TIPO DE CONTENIDO O COLECCIÓN]**

Antes de generar HTML, investiga y estructura la información.

## Objetivo

Construye un documento de información estructurada que pueda utilizarse
posteriormente para generar una página web.

## Estructura

Cada elemento debe incluir los siguientes campos:

- [CAMPO 1]
- [CAMPO 2]
- [CAMPO 3]
- [CAMPO 4]
- [CAMPO 5]

Todos los elementos deben mantener exactamente la misma estructura.

## Reglas

- Organiza la información de manera consistente.
- No inventes datos.
- Si un dato no está disponible, indícalo.
- Mantén una jerarquía clara.
- Utiliza títulos y subtítulos cuando sea necesario.
- Utiliza listas cuando exista información repetitiva.
- Conserva enlaces a fuentes o recursos relevantes cuando corresponda.
- Prioriza fuentes confiables.
- No agregues diseño.
- No agregues CSS.
- No agregues JavaScript.
- Entrega el resultado en formato Markdown.

---

# Addon 01 · Orden y jerarquía

Agrega estas instrucciones cuando el contenido necesite un orden específico.

```text
Ordena los elementos utilizando el siguiente criterio:

[CRITERIO DE ORDEN]

Ejemplos:

- cronológico;
- cronológico descendente;
- alfabético;
- por categoría;
- por relevancia;
- por tamaño;
- por ubicación.

Define claramente:

1. título principal;
2. introducción;
3. grupos o secciones;
4. elementos individuales;
5. información secundaria;
6. fuentes o enlaces.
```

---

# Addon 02 · Markdown → HTML

Utiliza este addon después de revisar y aprobar el archivo Markdown.

```text
Utiliza `base.html` como estructura base del documento.

Utiliza `[ARCHIVO].md` como única fuente de contenido.

Convierte la información a HTML semántico.

Reglas:

- Conserva la estructura general de `base.html`.
- Mantén `header`, `main` y `footer`.
- Organiza el contenido dentro de `main`.
- Utiliza `section` para grupos temáticos.
- Utiliza `article` cuando exista una unidad de contenido independiente.
- Utiliza encabezados de acuerdo con su jerarquía.
- Utiliza `p` para párrafos.
- Utiliza listas cuando corresponda.
- Utiliza `a` para enlaces.
- Utiliza `img` para imágenes.
- Conserva la información y el orden definidos en Markdown.
- No inventes contenido.
- No agregues CSS nuevo.
- No agregues JavaScript.
- No agregues estilos inline.
- Conserva el enlace a `style.css`.
- Devuelve un documento HTML completo y válido.
```

---

# Ejemplo de definición de estructura

Antes de investigar podemos definir la forma de los datos.

```text
COLECCIÓN
│
├── ELEMENTO
│   ├── título
│   ├── fecha
│   ├── descripción
│   ├── imagen
│   └── enlace
│
├── ELEMENTO
│   └── ...
│
└── ELEMENTO
    └── ...
```

El tema puede cambiar.

La estructura debe ser consistente.

---

# Regla de trabajo

No pedir:

> Hazme una página sobre [tema].

Separar el problema:

1. definir qué información necesitamos;
2. estructurarla;
3. revisar el Markdown;
4. transformar esa estructura a HTML;
5. aplicar CSS después.

La IA ayuda a procesar y transformar información.

La estructura y las decisiones del proyecto siguen siendo responsabilidad
de quien diseña.

Prompt 1: me puedes dar una lista de peliculas y documentales acerca de tiburones. dame el genero de cada uno, duracion, director y productor, de que año es, descripcion de que va el documental o pelicula, deja un espacio para que yo ponga observaciones, cuanto costo hacerlo. si no tienes esos datos no inventes solo ponle que no encontraste el dato. pon tambien los links de donde verlo si es que loe tienes. te voy a mandar unos que ya vimos por ejemplo: megalogon, sharknado, demonio negro

Prompt 2: que sea formato markdown. que digas si en la pelicula hay mujeres en traje de baño como victima y si el tiburon del que se habla es hombre o mujer si se sabe que el titulo principal sea "peliculas y documentales acerca de tiburones"

Prompt 3: puedes resumir, en si, no, muchas pocas por ejemplo en la parte de si hay mujeres en traje de baño o no. la unica que es necesaria que te extiendas es en descripcion de la pelicula y representacion del tiburon. quita todas las partes que digas tu opinion no hables asi. si no hay el dato solo pon un guion - . y especifica si este pelicula o documental entra en el genero de sharksplotaition

Prompt 4: es cierto que existen más de 180 pelis de tiburones, ayudame a pensar en sub categorías según las características en cada película, como comedia o cómo se representa al tubirón

Prompt 5: te voy a mandar una lista de categorias y luego te mando la lista del markdown pero NO CAMBIES NADA mas que añadir categoria

Prompt 6: Subcategoría	Característica	Ejemplos
🦈 Tiburón depredador	El tiburón como amenaza animal "realista"	Jaws, The Reef, The Shallows
🏊 Supervivencia / encierro	Humanos atrapados con tiburones	47 Meters Down, The Requin, Open Water
🔬 Tiburón científico / mutante	Experimentos, inteligencia aumentada, modificaciones	Deep Blue Sea, Shark Night
🦖 Monstruo gigante	El tiburón como criatura monstruosa	The Meg, Megalodon
🧬 Híbridos	Tiburón + otra criatura/objeto	Sharktopus, Mega Shark vs. Giant Octopus
🌪️ Catástrofe / absurdo	Tiburones en situaciones imposibles	Sharknado, Sky Sharks
👻 Sobrenatural	Tiburones poseídos, fantasmas, maldiciones, etc.	Ghost Shark, Ouija Shark, Shark Exorcist
🧟 Terror de explotación	Producciones de bajo presupuesto que explotan el concepto del tiburón asesino	Sharkansas Women's Prison Massacre, Cocaine Shark
😂 Comedia / parodia	Se apropian del imaginario del tiburón para hacerlo absurdo	Sharknado, Bad CGI Sharks
🌱 Eco-horror	Tiburón como consecuencia de contaminación, explotación o alteración ambiental	The Black Demon, Toxic Shark
🧠 Psicológico / thriller	El tiburón funciona también como generador de paranoia o tensión	The Shallows, 47 Meters Down
📺 Documental	Tiburones desde una perspectiva científica o naturalista	Sharkwater, Sharksploitation
