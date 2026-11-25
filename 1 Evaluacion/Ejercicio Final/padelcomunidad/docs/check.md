# A1 : COLOR Y TIPOGRAFIA

```cs
--paso-0: clamp(1rem, 0.9583rem + 0.185vw, 1.125rem);
```
**1ra RESPUESTA:** 

El tamaño minimo en px es `1rem` = `16px` y `1.125rem` = `18px`.
`REM` es obligatorio ya que es mas eficiente a la hora de acoplar el tamaño de `escritorio` y `movil`.

**2ra RESPUESTA:** 

```scss
color:var(--color-acento)
```

Esto lo que hace es darle color a el texto de una propiedad por ejemplo un `(p)`, es decir, `p` tendra el color de texto de color acento que es una variable que se coje del archivo `estilos.css`.

# A2 : TECNOLOGIAS DE DISEÑO

- Utiliazria `PHP` ya que te permite guardar las sesiones, usuarios, BD, etc...

- Tambien utilizaria `JS` ya que te permite dar dinamismo a la pagina o generar procesos mas comodamente.

# A3 : PREPROCESADORES

- 1
```css
--color-acento: light-dark(#850099, #eb66ff);
```

Esta linea pasa por los documentos: `tokens.sss, base/_elementos.scss, components/_boton.scss , components/_guia.scss, components/invitados.scss y todos los .html`

- 2 
  
**@FORDWARD** porque carga una hoja de estilo Sass y hace que sus mezclas, funciones y variables estén disponibles.
**@USE** porque carga mixins, funciones y variables de otras hojas de estilo Sass.

- 3
#### FALSO 

# A4 : NAVEGACION DE LA PAGINA NUEVA

1. Se llega desde el < header > y luego dentro de < nav > con un `a href`.
2. Pues desde la navegacion a el enlace a inicio.
3. Seria : 
   - desde inicio -> navegacion -> incidencidias
   - desde normas -> navegacion -> incidencidias
   - mis-turnos -> navegacion -> incidencias
Y al reves igual, si no lo entiendes, te invito a que habras index y lo pruebes.
4. Si si que debe de ir ya que es un apartado importante y se debe poder acceder desde cualquier sitio principal.