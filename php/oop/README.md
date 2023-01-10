# Make a Circle class with OOP

## Overview
Your task is to create a Circle constructor that creates a circle with a radius provided by an argument. The circles constructed must have two getters `getArea()` `(PI*r^2)` and `getPerimeter()` `(2*PI*r)` which give both respective areas and perimeter (circumference).

## Examples
```
$circle = new Circle(11);
$circle->getArea();

// Should return 380.132711084365

$circle = new Circle(4.44);
$circle->getPerimeter();

// Should return 27.897342763877365
```

## Notes
* PHP 8.1+ required.
* Don't worry about floating point precision.