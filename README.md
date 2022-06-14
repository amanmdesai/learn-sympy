# learn-sympy

First all the symbols, x/y/etc.

``` x =   Symbol('x') ```

Using expand command to expand the expressions

```expand(expr*x)```

## Integration

``` 
integrate(expr,x) 

integrate(sin(x**2), (x, -oo, oo))

```
## Matrix

```Matrix([[1,2],[2,1]]).eigenvals()```

## Functions 

```f, g = symbols('f g', cls=Function) ```

## Differential Equations

diff(x,x)

dsolve
