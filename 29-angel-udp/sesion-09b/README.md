# sesion-09b

viernes 15-05-2026

## Apuntes

El chip Dip-16: número de patas

W7.62 mm: ancho de patas

Repaso en KiCad después de realizar la tarea

Y enseña a cómo realizar cambios en cuanto a las huellas mientras se va actualizando ida y vuelta reiteradamente

Y también se pueden editar los componentes en cuanto a nombres, colores o partes de esta, como agregar o quitar patitas del chip en caso de que se pueda

### Botones

Están los switch y los temporales

Temporary - Pulsadores - Pushbuttons - Timbres, tienen un sentido que es: Normalmente abierto NO y Normalmente cerrado NC

Una cosa es el Polo: físicamente hay una conexión

El Throw: en qué lugares puede caer

Y el Single: tiene un lugar donde caer

Y una Com (común) para decidir a dónde va y se llama single porque en la carcasa solo hay una

El que usamos es el pushbutton que en el esquemático tiene 2 patas porque están duplicadas (mecánicamente hay 4 pero eléctricamente hay 2, creo que esto está para mejorar la estabilidad). Huella SW_PUSH_6mm

### Interruptores

Hay de 2 patas y también pushbutton de 2 patas en el esquemático, así que ninguno me dice si es switch o no

SPDT: SW_SPDT (lo vamos a usar generalmente para prender y apagar)

Tal como editamos los símbolos, podemos editar la huella manualmente

Hay componentes de placa y componentes de panel

---

**los de panel** Son los que van en las carcasas

Se puede conectar por medio de palabras que evitan un cableado directo, sino que sería conceptual

A la izquierda hay opciones para sacar la visualización de Tierra o GND

Todo el GND debe estar completo y no generar "islas aisladas" que no tengan toda la conexión con ground porque puede no funcionar el circuito

Con la letra F se pasan los componentes para atrás y con la letra R se acomodan en el mismo punto en el que estaban

En propiedades de las huellas se puede cambiar el modelo 3D para ajustar la posiciónn

**Como expoertar vista 3D de KiCad**

Cad assistance, programa para ver modelos 3D

Sitio web:

- Hackday.com
- (Logic noise sweet oscilator sounds)
