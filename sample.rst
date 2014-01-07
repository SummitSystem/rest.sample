.. role:: font-tiny
.. role:: font-small
.. role:: font-medium
.. role:: font-large
.. role:: font-huge

.. role:: text-white
.. role:: text-black
.. role:: text-red
.. role:: text-green
.. role:: text-blue
.. role:: text-yellow

.. role:: back-black
.. role:: back-red
.. role:: back-green
.. role:: back-blue
.. role:: back-yellow
.. role:: back-cyan

.. role:: red-yellow
.. role:: yellow-red
.. role:: blue-red-huge
.. role:: yellow-red-huge

.. role:: strike
.. role:: strike-gray
.. role:: underline

.. role:: redtext

.. header:: rst2pdf sample
.. footer::  － ###Page###/###Total### －

.. |spc| unicode:: U+00A0

.. |title| replace:: PDF FONT装飾サンプル


=======
|title|
=======

|

.. section-numbering::

:text-red:`SIZE`
================

----

This font is :font-tiny:`TINY`.

This font is :font-small:`SMALL`.

This font is :font-medium:`MEDIUM`.

This font is :font-large:`LARGE`.

This font is :font-huge:`HUGE`.

|

----


|

:text-blue:`Color`
====================


*  :underline:`Foreground`

   I like color :text-red:`red`.

   I like color :text-blue:`blue`.


|

*  :underline:`Background`

   I like color :back-yellow:`yellow`.

   I like color :back-cyan:`cyan`.

|

* :underline:`Both`

   I like color :red-yellow:`yellow`.

   I like color :yellow-red:`yellow/red`.

   I like color :yellow-red-huge:`yellow/red`.

   |

   I like color :blue-red-huge:`yellow/red`.



.. raw:: pdf

   PageBreak


:underline:`Other`
==================



----

これは :underline:`下線`.

これは :strike:`打ち消し線`.

これは :strike-gray:`打ち消し線`.

|

通常は、複数のスペースは１つにまとめる ... hoge   hoge   hoge

複数のスペースを挿入してみる  ... hoge |spc| |spc| |spc| |spc| hoge |spc| |spc| |spc| |spc| hoge

----

|


「以上」を右詰めで出力

|

   |

   -- 以上
