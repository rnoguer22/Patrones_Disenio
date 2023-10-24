# Patrones_Disenio

[Link del repositorio](https://github.com/rnoguer22/Patrones_Disenio.git)

---

## Indice

- [Factory Method](#1)
- [Abstract Factory](#2)
- [Builder](#3)
- [Prototype](#4)

---

## <a name="1" href="FactoryMethod/factorymethod.py">Factory Method</a>

---

## <a name="2" href="AbstractFactory/abstractfactory.py">Absract Factory</a>

Tenemos una tienda de muebles, silla sofa y mesilla, y cada producto tiene las variantes ArtDecó, Victoriana y Moderna.

<p align="center">
  <img src="https://github.com/rnoguer22/Patrones_Disenio/blob/main/img/Abstract%20Factory.PNG" width=400px height=auto>
</p>

---

## <a name="3" href="Builder/builder.py">Builder</a>

Permite construir objetos complejos (una pizza es un objeto complejo)

Imagina que estamos construyendo una casa prefabricada, que sera nuestro modelo base. Y en base a esta casa podemos ampliarla, añadiendo piscina, garaje, jardín, etc.

Construimos la casa inicial y a partir de ahi creamos los modulos

---

## <a name="4" href="Prototype/prototype.py">Prototype</a>

Tenemos clones y queremos hacer una copia

Hacemos clones y cada clon tiene su autonomia, 

No le gusta al ticher. Cierta incongruencia a la hora de clonar, ya que se copia todo sin saber lo que hay dentro
