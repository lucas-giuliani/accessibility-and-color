# El color no es neutral

Usamos el color para ordenar, destacar, advertir, confirmar, vender y construir identidad. Está tan integrado a la experiencia que muchas veces dejamos de verlo como una decisión y empezamos a tratarlo como una verdad universal.

Verde significa que algo salió bien.  
Rojo significa error.  
Amarillo significa atención.  
Gris significa que algo no está disponible.

El problema aparece cuando toda la información depende de esa asociación.

## El punto de partida

En diseño solemos discutir qué color representa mejor una marca, qué combinación genera más impacto o qué paleta transmite determinado atributo.

Pero hay una pregunta anterior:

**¿Qué pasa cuando una persona no percibe esos colores como nosotros suponemos?**

No todas las personas distinguen los mismos tonos de la misma manera. Y aun entre quienes no tienen una deficiencia en la percepción del color, el contexto, la iluminación, la pantalla y el contraste pueden modificar bastante la experiencia.

El color no desaparece por eso. Sigue siendo una herramienta valiosa. Lo que conviene revisar es cuánto estamos haciendo depender de él.

## Cuando el color se convierte en información

Hay una diferencia entre usar color para acompañar un mensaje y usarlo como único mensaje.

Por ejemplo:

- un campo marcado solamente con borde rojo;
- un gráfico cuyos datos se distinguen solo por el color;
- un estado activo indicado únicamente en verde;
- una alerta representada solo con amarillo;
- botones habilitados y deshabilitados sin otra diferencia visible;
- mapas, calendarios o tableros que dependen por completo de una leyenda cromática.

Para una parte de las personas, esas diferencias pueden ser difíciles de detectar o directamente desaparecer.

La interfaz sigue estando ahí, pero parte de la información deja de estar disponible.

## Daltonismo no significa ver en blanco y negro

Una idea bastante extendida es que las personas con daltonismo ven el mundo sin color. En la mayoría de los casos no ocurre así.

Las diferencias aparecen en la manera de distinguir ciertas gamas.

### Deuteranopía

Afecta principalmente la percepción de verdes. Algunos verdes, rojos, marrones y naranjas pueden resultar difíciles de diferenciar entre sí.

### Protanopía

Afecta la percepción de rojos. Algunos tonos pueden verse más oscuros y confundirse con verdes o marrones.

### Tritanopía

Es menos frecuente y afecta principalmente la distinción entre azules y amarillos.

Estas categorías ayudan a estudiar el problema, pero no representan una única experiencia idéntica para todas las personas.

## La accesibilidad no consiste en eliminar el color

Diseñar de forma accesible no implica convertir todo en gris ni renunciar a una identidad visual fuerte.

El objetivo es que la información siga siendo comprensible aunque el color cambie, se perciba de otra manera o no pueda distinguirse.

Algunas decisiones posibles:

- acompañar el color con texto;
- sumar íconos con significado claro;
- utilizar patrones o texturas;
- trabajar con diferencias de forma;
- agregar etiquetas directamente sobre los datos;
- asegurar contraste suficiente;
- revisar estados de foco, selección y error;
- no confiar solamente en rojo y verde;
- probar las pantallas con simuladores.

La redundancia, en estos casos, no es ruido. Es una forma de evitar que una señal dependa de un único canal visual.

## El contraste también forma parte del problema

Dos colores pueden parecer diferentes al observarlos en una paleta y perder esa diferencia cuando se aplican en una interfaz real.

Influyen:

- el tamaño del texto;
- el grosor tipográfico;
- el fondo;
- la luminosidad;
- el brillo de la pantalla;
- la distancia de lectura;
- el estado del componente;
- el entorno en el que se usa el producto.

Validar contraste no reemplaza una revisión completa de accesibilidad, pero permite detectar problemas que a simple vista pueden pasar inadvertidos.

## No alcanza con cumplir una proporción

Las herramientas automáticas son útiles, aunque también pueden generar una falsa sensación de seguridad.

Que una combinación apruebe una validación técnica no significa necesariamente que toda la experiencia sea clara.

Un componente puede tener buen contraste y seguir dependiendo de una diferencia cromática demasiado sutil. Un gráfico puede cumplir con ciertos valores y continuar siendo difícil de interpretar. Un error puede verse correctamente y, aun así, no explicar qué debe hacer la persona para resolverlo.

La accesibilidad no termina en un número. El criterio sigue siendo necesario.

## Diseñar para distintas percepciones

Cuando una interfaz funciona sin depender exclusivamente del color, generalmente mejora para más personas de las que imaginamos.

También ayuda en situaciones bastante comunes:

- pantallas con poco brillo;
- uso bajo el sol;
- proyectores con mala calidad;
- monitores descalibrados;
- impresiones en escala de grises;
- personas cansadas o apuradas;
- entornos donde la atención está dividida.

Diseñar para una condición específica muchas veces revela fragilidades que afectan a una experiencia mucho más amplia.

## Una exploración visual

Como parte de este proyecto voy a comparar una misma imagen bajo distintas simulaciones de percepción del color.

La intención no es mostrar una representación exacta de cómo “ve” cada persona. Los simuladores son aproximaciones. Sirven para detectar dependencias, contrastes débiles y decisiones que podrían fallar.

El ejercicio parte de una misma composición visual y la observa bajo diferentes filtros:

- visión sin simulación;
- deuteranopía;
- protanopía;
- tritanopía.

Ver las versiones juntas permite entender algo que una tabla de valores no siempre consigue mostrar: una paleta que parece muy variada puede reducirse drásticamente cuando cambia la percepción.

## Preguntas para revisar una interfaz

Antes de dar por terminada una pantalla, puede servir preguntarse:

- ¿Se entiende el estado sin mirar el color?
- ¿Un error tiene texto o solamente un borde rojo?
- ¿Las series de un gráfico tienen etiquetas?
- ¿La selección se reconoce por forma, posición o contenido?
- ¿Los botones deshabilitados conservan suficiente legibilidad?
- ¿La información funciona en escala de grises?
- ¿Probamos la experiencia con alguna simulación?
- ¿El contraste fue validado en el contexto real del componente?

No todas las respuestas tienen que resolverse del mismo modo. La revisión sirve para detectar cuánto depende la experiencia de supuestos visuales que quizás no se cumplen.

## Próximos contenidos

Este repositorio va a incorporar progresivamente:

- una comparación visual de distintos tipos de daltonismo;
- ejemplos de interfaces problemáticas;
- criterios para gráficos y visualización de datos;
- herramientas de simulación;
- una checklist práctica;
- reflexiones sobre color, percepción y decisiones de producto.

## Sobre esta exploración

No busco construir una guía técnica exhaustiva sobre accesibilidad visual.

Me interesa observar cómo una decisión que suele parecer estética también puede afectar comprensión, autonomía y capacidad de acción.

El color puede enriquecer una experiencia. También puede ocultar información cuando asumimos que todas las personas lo perciben igual.

---

**Autor:** Lucas Giuliani  
**Temas:** color, accesibilidad visual, percepción, daltonismo, UX y Product Design
