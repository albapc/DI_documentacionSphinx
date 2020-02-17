
=====================
Isto é unha cabeceira
=====================

Cabeceira h1
************

Título h2
=========

Título h3
---------

Título h4
+++++++++


Marcado dentro de texto
+++++++++++++++++++++++
Escribimos texto en varias liñas e isto forma un parágrafo.
Lembrade que o tabulado é importante para que o entenda sphynx. Dentro do texto podemos resaltar
mediante *cursiva*, ou **negriña** e ``dobres comiñas para código``.


Listas non numeradas
++++++++++++++++++++
* Podemos facer listas.
* De distintos elementos.
  Utilizando o * .

Listas numeradas
++++++++++++++++
1. Outra lista numerada
2. utilizando o número seguido do punto

#. Seguimos numerando listas
#. Neste caso utilizamos #.

Cun novo paragrafo no medio comeza a numeración?

#. Nova lista


Sublistas
+++++++++
* Lista
* con elementos

    * En novas sublistas
    * Con distintos niveis


* E subniveis

Definicións
+++++++++++

Término
    Definición do término, mediante tabulación.

    Pode ter varios parágrafos.

Outro término.
    Coa súa definición.


Saltos de liña
++++++++++++++

| Estas liñas se mostrarán
| un texto máis grande
| cos saltos de liña marcados
| de forma exacta.


Bloques de texto literales
++++++++++++++++++++++++++

O texto normal de parágrafo. O texto que se mostra a
continuación sería un bloque literal::

    import sys

    class MinhaClase:
        # Por facer

Continuamos o texto o mesmo nivel de parágrafo a continuación.

>>> 2 + 2
4

Táboas
++++++

+---------------------------+---------------+---------------+---------------+
| Cabeceira fila, columna 1 | cabeceira 2   | Cabeceira 3   | Cabeceira 4   |
| Pode usar varias liñas    |               |               |               |
+===========================+===============+===============+===============+
| Fila 1, columna 1         | Fila 1, col2  |               |               |
+---------------------------+---------------+---------------+---------------+
|                           |               |               |               |
+---------------------------+---------------+---------------+---------------+

Listas
++++++

==========      ==========      ==========
Lista 1         Lista 2         Lista 3
==========      ==========      ==========
Elemento 1      Elemento 2      Elemento 3
Elemento 4      Elemento 5      Elemento 6
Elemento 7      Elemento 8      Elemento 9
==========      ==========      ==========


Enlaces
+++++++

.. _cfr Daniel Castelao: http://www.danielcastelao.org

Os enlaces non é necesario marcalos http://www.danielcastelao.org salvo que queiramos poñerlle unha
etiqueta para o enlace ao `cole <http://www.danielcastelao.org/>`_

Outra forma de acceder ao `cfr Daniel Castelao`_. En calquera sitio que apareza `cfr Daniel Castelao`_.

Outra forma de acceder ao `cfr Daniel Castelao`_. Outra forma de acceder ao `cfr Daniel Castelao`_.
Outra forma de acceder ao `cfr Daniel Castelao`_.

Enlace a listas numeradas `Listas non numeradas`_

.. figure:: _static/museo.png
    :align: center

    Este é o pe da imaxe

:download: `Báixate o exemploSphynx.rst <source/exemplo.rst>`_

.. note::
    Isto é unha nota

.. warning::
    Coidado coa advertencia!

.. versionchanged::

    0.0.1.

Si queremos resaltar un comando como ``sphinx-quickstart`` para configurar o ficheiro *conf.py*



