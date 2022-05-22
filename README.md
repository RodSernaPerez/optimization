# Teoría Convexidad

## Convexo

$f$ es convexa si $f(\lambda x + (1- \lambda) y) \leq \lambda f(x) + (1-y) f(y))$ para todo $x, y$ en $(a, b)$

Interpretación: Si coges dos puntos $x, y$ y los unes con un segmento, la curva en los puntos entr $x$ y $y$ tocan al segmento o quedan por debajo.

## Estrictamente convexo

$f$ es estrictamente convexa si $f(\lambda x + (1- \lambda) y) < \lambda f(x) + (1-y) f(y))$ para todo $x, y$ en $(a, b)$

Interpretación: Si coges dos puntos $x, y$ y los unes con un segmento, la curva en los puntos entr $x$ y $y$ quedan por debajo del segmento.

## Cusiconvexo

$f$ es cuasiconvexa si $f(\lambda x + (1- \lambda) y) \leq max(f(x), f(y))$ para todo $x, y$ en $(a, b)$

Interpretación: El máximo entre $x$ y $y$ se alcanza en uno de los extremos


## Estrictamente Cusiconvexo

$f$ es estrictamente cuasiconvexa si $f(\lambda x + (1- \lambda) y) < max(f(x), f(y))$ para todo $x, y$ en $(a, b)$ con $f(x) \neq f(y) $

Interpretación: El máximo entre $x$ y $y$ se alcanza en uno de los extremos de forma estricta

## Fuertemente Cuasiconvexo

$f$ es fuertemente cuasiconvexa si $f(\lambda x + (1- \lambda) y) < max(f(x), f(y))$ para todo $x, y$ en $(a, b)$

## Pseudoconvexa

$f$ es pseudoconvexa si $\Delta f^t(x)(y -x) \geq 0 -> f(y) \geq f(x)$

Interpretación: Si te mueves en una dirección en la que el gradiente decrece, entonces solo encuentras valores menores o iguales

## Estrictamente pseudoconvexa

$f$ es pseudoconvexa si $\Delta f^t(x)(y -x) < 0 -> f(y) \geq f(x)$

Interpretación: Si te mueves en una dirección en la que el gradiente decrece, entonces solo encuentras valores menores.

## Relaciones 

Estrictamente Convexa -> Estrictamente Pseudoconvexa -> Fuertemente Cuasiconvexa - > Cuasiconvexa

Estrictamente Convexa -> Convexa -> Pseudoconvexa -> Estrictamente Cuasicvonvexa -> Cuasiconvexa

* Para que un mínimo local también sea global, debe ser **fuertemente cuasiconvexa**.

