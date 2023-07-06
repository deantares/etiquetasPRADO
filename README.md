# etiquetasPRADO
Durante mucho tiempo he usado estas mismas etiquetas HTML para PRADO en las distintas asignaturas, dejándolas como "legado" en los departamentos y asignaturas por las que he ido pasando. Las pongo en el repositorio actualizadas para los nuevos colores

Visión de escritorio

![Previsualización](/img/Preview.PNG)

Visión de móvil

![Previsualización](/img/PreviewMobil.PNG)

Visión de tablet

![Previsualización](/img/previewIPAD.PNG)

## Secciones

Sirven para poder divir un tema por medio de un bloque con un elemento de apertura y cierre.

En el bloque de apertura se puede poner una descripción:

![Previsualización](/img/previewSeccion.PNG)

```
<h4 style="text-align: left; border: solid #CB2C30; background-color: #CB2C30; color: white; padding: 5px; border-radius: 20px 20px 0px 0px;margin-top:30px;padding-left:20px;">Sección 1: Lo que sea que haya que poner</h4>
```

El bloque de cierre sirve para delimitar visualmente el fin de la sección:

![Previsualización](/img/previewSeparador.PNG)

```
<h2 style="border: solid #CB2C30; background-color: #CB2C30; color: #CB2C30; padding: 1px; border-radius: 0px 0px 20px 20px; margin-bottom: 10px; height: 5px;"></h2>
```

## Subsecciones

Las subsecciones permiten incluir un anidamiento adicional o destacar algún elemento.

También hay dos elementos de importancia, con un elemento con color relleno:

![Previsualización](/img/previewSubSeccionFill.PNG)

```
<h5 style="width:50%; text-align: left; border: solid #CB2C30; background-color: #CB2C30; color: white; padding: 5px; border-radius: 0px 20px 20px 0px;margin-top:30px;">&nbsp; &nbsp; &nbsp;3.1: Sub-sección</h5>
```

Y el mismo bloque con el fondo claro:

![Previsualización](/img/previewSubSeccion.PNG)

```
<h5 style="width:50%; text-align: left; border: solid #d34e51; background-color: #fdf7f7;; color: #CB2C30; padding: 5px; border-radius: 0px 20px 20px 0px;margin-top:30px;">&nbsp; &nbsp; &nbsp;3.1: Sub-sección</h5>
```

## Bloque adicional

Útil para realizar una división adicional. Yo lo suelo emplear para separar el contenido obligatorio del contenido adicional. Se puede personalizar la descripción:

![Previsualización](/img/PreviewAdicional.PNG)

```
<p style="color: #CB2C30">Material adicional</p>
<h2 style="border: dashed #CB2C30;color: #CB2C30;margin-top:-10px;margin-bottom: 10px;height: 0px;margin-top: -15px;"></h2>
```




# Como añadir las etiquetas a PRADO

Para añadir una etiqueta, se tiene que activar el modo edición y añadir el recurso etiqueta

![Previsualización](/img/step1.PNG)

Pulsamos en el botón de __Mostrar más botones__.

![Previsualización](/img/step2.PNG)

Y pulstamos el botón de incorporar código HTML.

![Previsualización](/img/step3.PNG)

Eliminamos el código que se genera por defecto.

![Previsualización](/img/step4.PNG)

Copiamos el código HTML de la etiqueta del repositorio y la pegamos en el cuadro de texto.

![Previsualización](/img/step5.PNG)

Cuando guardemos los cambios podremos editar la etiqueta por medio del editor visual. Esto es muy útil si duplicamos la etiqueta para reutilizarla

![Previsualización](/img/step6.PNG)
