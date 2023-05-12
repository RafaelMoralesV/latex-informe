# Repositorio - Template informe

Este repositorio contiene mi informe para trabajo de título.
Se basa en un [template creado por Pablo Pizarro R.](https://latex.ppizarror.com/informe).

Muchas gracias al autor de este template por su trabajo.

## Instrucciones para compilar

Lo que más cómodo me ha resultado es utilizar `latexmk` para el compilado continuo de este proyecto.

```shell
$: latexmk -pdf -pvc -jobname=target/main main
```

Este comando produce un pdf de nombre 'main.pdf' en el directorio `target/`, a partir del archivo `main.tex`.

Es posible que falle si no se encuentra el directorio `target/`, por lo que recuerda crearlo antes de lanzar este comando!
