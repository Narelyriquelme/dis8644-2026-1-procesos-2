# examen-grupo-05

#Sistema Modular — [Nombre del instrumento]

## Integrantes

| Nombre            | Cuenta de GitHub |
| ----------------- | ---------------- |
| Luisa Toro        |30-Luisaatoro9    |
| Antonia Améstica  |04-antoniaamc     |
| Sebastián Guevara |14-sebastianguevaralarotta|
| Catalina Jeria    |15-catalinajeria  |
| Catalina Balboa   |05-Catabalboa     |

---

# Criterios de diseño del sistema

El sistema fue concebido como un instrumento modular donde cada placa representa un universo independiente que, al conectarse con las demás, forma un ecosistema sonoro completo. Desde el inicio del proyecto buscamos que el diseño no fuera únicamente funcional, sino también narrativo, permitiendo que cada módulo aportara una identidad propia al conjunto.

El criterio principal consistió en comprender que un sintetizador modular no es una pieza única, sino un sistema compuesto por diferentes procesos electrónicos que interactúan entre sí. Esta lógica fue trasladada a la propuesta formal, donde cada módulo conserva su autonomía visual pero adquiere un nuevo significado al integrarse con los demás.

---

# Inspiración

La inspiración surgió durante las conversaciones del grupo acerca de nuestros intereses personales. Descubrimos que gran parte de ellos coincidían en universos de ciencia ficción presentes en películas y series.

La principal referencia fue la saga **Star Wars**, donde distintos planetas, personajes y tecnologías funcionan de manera independiente, pero forman parte de un mismo universo. Esta idea fue el detonante conceptual del proyecto: entender que cada placa electrónica corresponde a un "planeta" con una función específica y que, al conectarse entre sí, construyen un instrumento modular completo.

Nuestro aporte corresponde al módulo de filtro, concebido como una nave que viaja entre estos mundos sonoros e interviene el flujo del sonido antes de continuar hacia el siguiente proceso.

---

# Contexto de diseño

El proyecto fue desarrollado desde Chile considerando la disponibilidad de materiales accesibles y técnicas de fabricación de bajo costo.

Para construir la carcasa general se recurrió a materiales como alambre, arcilla y sistemas simples de ensamblaje manual, buscando demostrar que es posible desarrollar propuestas expresivas utilizando recursos fácilmente disponibles.

La carcasa adopta la forma de una geoda o un pequeño planeta cristalino. Los cristales representan la energía y la luz producida por el funcionamiento simultáneo de los distintos módulos electrónicos. Dentro de esta estructura aparece la carcasa del filtro, representada como una nave que atraviesa este planeta y completa el recorrido del sonido.

---

# Nombre del sistema

**________________________________________**

---

# Placas construidas

| Módulo              | Grupo     | Función       |
| ------------------- | --------- | ------------- |
| Chirigüe mecanizado | Grupo 4   | Oscilador     |
| Lub-dub             | Grupo 6   | Percutor      |
| ALO HOUSTON         | Grupo 5 | Filtro pasivo |
| PARLA               | LID     | Parlante de audio |
---

# Principio de funcionamiento

## Chirigüe mecanizado — Oscilador

El oscilador constituye la fuente principal de señal del sistema. Su función consiste en generar una señal eléctrica periódica cuya frecuencia determina la altura del sonido. Esta señal sirve como punto de partida para el resto de los módulos.

**Recibe:** alimentación eléctrica.

**Entrega:** señal de audio oscilante hacia el resto del sintetizador.

---

## Lub-dub — Percutor

El módulo percutor genera impulsos rítmicos o envolventes que permiten producir patrones repetitivos y eventos sonoros de carácter percusivo.

**Recibe:** alimentación y señales de sincronización.

**Entrega:** pulsos o señales rítmicas que modulan otros módulos del sistema.

---

## ALO HOUSTON — Filtro

El filtro pasivo modifica el contenido espectral de la señal proveniente del oscilador. Mediante dos controles variables (RV1 y RV2) atenúa determinadas frecuencias, alterando el color o timbre del sonido sin generar señal propia.

**Recibe:** señal de audio proveniente del oscilador.

**Entrega:** señal filtrada hacia la salida del sintetizador o hacia otros módulos posteriores.

---

# Flujo general del sistema

```text
Oscilador
      │
      ▼
Filtro
      │
      ▼
Percutor / Modulación
      │
      ▼
Salida de audio
```

---

# Lista de materiales

| Material | Cantidad | Costo |
| -------- | -------- | ----- |
|          |          |       |
|          |          |       |
|          |          |       |
|          |          |       |
|          |          |       |

**Tiempo total de soldadura**

---

---

# Carcasa del filtro

## Concepto

La propuesta no corresponde simplemente a una carcasa de acrílico. Se plantea como una estructura cuya función es proteger, organizar, revelar y comunicar el funcionamiento interno del instrumento.

En lugar de ocultar la electrónica, la estructura la exhibe como parte esencial de la identidad visual del objeto.

---

## Decisiones materiales y formales

La estructura está conformada por dos placas de acrílico cortadas mediante láser siguiendo exactamente el contorno de la PCB, respetando la silueta inspirada en un tocadiscos presente en el diseño original de la placa.

Una pieza funciona como base y la otra como panel superior. Ambas permanecen separadas mediante pernos M3 de aproximadamente 15 a 20 mm de altura.

Esta solución genera un volumen liviano donde la placa permanece suspendida entre ambas piezas, permitiendo observar completamente el circuito desde la parte superior y desde los laterales.

La transparencia del acrílico transforma al circuito en el principal protagonista visual del instrumento.

---

# Inspiración y referentes

Uno de los principales referentes fue **Bleep Labs**, fabricante de sintetizadores experimentales cuya filosofía consiste en comprender la electrónica como parte del lenguaje visual del instrumento.

Más que reproducir la apariencia de sus productos, se tomó como referencia la idea de que el circuito deje de ser un componente oculto y pase a convertirse en un elemento visible que comunica el funcionamiento del instrumento y fortalece la relación entre el usuario, la electrónica y el sonido.

---

# Composición

La composición de la carcasa también toma como referencia las ideas desarrolladas por **Yoko Ono** sobre la participación activa del usuario frente al objeto.

En sus obras e instrucciones artísticas, el valor no reside únicamente en el objeto físico, sino en la experiencia que genera durante su utilización.

Siguiendo esta lógica, el sintetizador no busca esconder su funcionamiento detrás de una caja cerrada. Al contrario, expone el circuito para invitar al usuario a comprender cómo se produce el sonido y cómo cada componente participa en dicho proceso.

La carcasa deja de ser un simple contenedor y se transforma en un elemento de comunicación entre la electrónica y quien interpreta el instrumento.

---

# Partitura experimental

## ONDAS INVISIBLES

**Instrumento:** sintetizador conectado al filtro pasivo de dos controles (RV1 y RV2).

**Duración:** 5 a 10 minutos.

1. Comienza con una única nota sostenida.
2. Gira RV1 lentamente desde el mínimo hasta el máximo durante un minuto completo.
3. Escucha únicamente los cambios de color del sonido. No cambies la nota.
4. Cuando percibas una frecuencia que te recuerde un lugar, mantén esa posición durante diez segundos.
5. Cambia a otra nota. Puede ser más aguda o más grave. No debe seguir ninguna escala.
6. Mueve RV2 muy lentamente hasta que el sonido parezca respirar.
7. Introduce silencios. Los silencios deben durar más de lo que resulte cómodo.
8. Repite una nota tres veces. Cada repetición debe ser más suave que la anterior.
9. Lleva ambos controles al extremo opuesto.
10. Toca una última nota.
11. Espera a que desaparezca completamente.
12. No hagas nada durante treinta segundos.

**Fin.**

---

# Operación de la partitura

La partitura fue diseñada para facilitar la interacción de personas sin experiencia previa con sintetizadores modulares. En lugar de exigir conocimientos musicales o técnicos, propone acciones sencillas que permiten descubrir progresivamente el comportamiento del filtro mediante la escucha.

Cada instrucción invita al intérprete a prestar atención a pequeñas variaciones del sonido, promoviendo una experiencia basada en la exploración más que en la ejecución correcta.

---

# Proceso de creación

La partitura surge de la intención de transformar la primera interacción con el sintetizador en una experiencia abierta y accesible.

Al mismo tiempo, incorpora momentos de incomodidad deliberada —como silencios prolongados o la ausencia de referencias tonales tradicionales— para invitar al intérprete a abandonar expectativas convencionales y construir una interpretación propia.

De esta forma, el usuario deja de reproducir una pieza musical y comienza a descubrir nuevos paisajes sonoros mediante la experimentación.

---

# Referentes

La estructura de instrucciones se inspira en las **Instruction Pieces** de **Yoko Ono**, donde la obra se activa únicamente cuando el participante ejecuta una serie de acciones propuestas por la autora.

Asimismo, la exploración libre del sonido toma referencias de la música experimental y de la práctica de improvisación característica de los sintetizadores modulares.

---

# Simbología

La partitura reemplaza la notación musical tradicional por acciones e instrucciones.

Cada movimiento de los controles representa una exploración del espacio sonoro; los silencios funcionan como parte activa de la composición; y la ausencia de una melodía predeterminada convierte cada interpretación en una experiencia única e irrepetible.

El resultado final depende completamente de las decisiones tomadas por quien interactúa con el instrumento, haciendo que cada ejecución construya un nuevo recorrido dentro del universo modular propuesto.



PAUTA: / imaenes + funcionamiento detallado . 
## integrantes

nombre - [cuenta-github](https://github.com/bla)

## criterios de diseño del sistema

inspiración para construir, desde donde partieron

contexto desde Chile, desde nuestra disponibilidad material

nombre de sistema/instrumento construido por medio de módulos

## placas soldadas

nombres de placas armadas

principio de funcionamiento de cada una

qué tipo de señal entrega a la salida, qué recibe

lista de materiales con costos. Incluir tiempo de soldadura

## carcasa

decisiones materiales y formales de la carcasa

inspiración y referentes (con cita)

## composición

partitura e interpretación

detallar operación de la partitura, como se creó, cuales fueron los referentes (citando), cual es la simbología

## bibliografía
