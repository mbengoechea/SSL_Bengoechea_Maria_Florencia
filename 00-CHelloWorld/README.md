# TP0: Hello, world! 

Objetivos:

• Configurar el entorno de desarrollo para la cursada.

• Tener un primer contacto con las herramientas necesarias para abordar la
resolución de los trabajos propuestos en el curso.

• Demostrar capacidad para editar, compilar, y ejecutar programas C mediante
el desarrollo de un programa simple.

• Crear repositorio personal git.

• Armar de equipo de trabajo.


## Consignas

Indique en el readme.md

A. El compilador seleccionado.

B. La versión de ese compilador.

C. La versión de C que el compilador compila.


## Resolución

A- Compilador: MinGW

B- Versión del compilador: 15.2.0

C- Versión de C: C23

## Pasos para la obtención de la verción de C que el compilador compila

```
int main ()
{
    printf ("Version del estandar de C: %id\n", __STDC_VERSION__);
}
```
Al buscar el número que imprime, obtuve que versión de C estaba compilando.
