---
layout: post
title:  "Estructuras de Control"
date:   2018-03-31 14:49:12 -0300
categories: python
lang: es
ref: 2018-03-31-control-structures
---

## Condicionales
* Sentencias condicionales: Permiten que comprobar condiciones y que el programa se comporte
de una manera u otra, de acuerdo a esa condición.
* Python para evaluar las condiciones utiliza la evaluación con circuito corto

### if
{% highlight python %}
if condición:
    sentencia1
    sentencia2
    ...
    sentenciaN
{% endhighlight %}

### if-else
Permite ejecutar ciertas órdenes en el caso que se cumpla y que no se cumpla la condición

{% highlight python %}
if condición:
    sentencia1
    ...
    sentenciaN
else:
    sentencia1
    ...
    sentenciaN
{% endhighlight %}

### if-elif-else
El **elif** permite anidar condicionales. Támbien reemplazaría el condicional else if

{% highlight python %}
if condición:
    sentencia1
    ...
    sentenciaN
elif condición:
    sentencia1
    ...
    sentenciaN
else:
    sentencia1
    ...
    sentenciaN
{% endhighlight %}

### inline condition
Las condiciones en linea sirven para hacer mas legible el código

{% highlight python %}
value = "a_value" if True else "another_value"
print(value)
{% endhighlight %}

## Bucles
Los bucles permiten ejecutar cierto código un número reiterado de veces hasta que se cumpla una
condición.
