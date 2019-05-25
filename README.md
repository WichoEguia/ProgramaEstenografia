# Esteganografía

Este proyecto se conforma por dos programas que se encargan de escribir y ocultar mensajes dentro de una imagen.

### esteganografia_ocultar.py

Este es el programa encargado de escribir mensajes en la imagen, para ejecutarlo se usa el siguiente comando:

```
python esteganografia_ocultar.py [mensaje a ocultar] [path de la imagen]
```

**La imagen generada se guardará en formato PNG y agregando "-salida" en el nombre.**

## esteganografia_leer.py

Este es el programa encargado de leer el mensaje oculto en la imagen, para ejecutarlo se usa el siguiente comando:

```
python esteganografia_leer.py [path de la imagen con mensaje oculto]
```

**En caso de pasar como parametro una imagen sin mensaje se retornará una serie de caracteres ilegibles. :D**
