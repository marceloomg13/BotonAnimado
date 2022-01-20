# Librerias
> Boton animado que aumenta levemente su tamaño durante unos instantes para luego volver a su tamaño original
~~~python
from PySide6.QtWidgets import QPushButton
~~~
Para el diseño del botón
~~~python
from PySide6.QtCore import (
    QPropertyAnimation, QRandomGenerator, QSequentialAnimationGroup, QPoint, QSize, Property)
import random
~~~
Utilizados en la animación y color del botón
~~~python
import unittest,pytest
~~~
Librerias utilizadas para el testeo del componente