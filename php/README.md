# Lepus Inc. Backend/PHP Challenges
## OverView

* We prefer well-thought-out solutions over the quick-and-dirty kind. So take your time, if you need it.
* Implement your code under the `src` directory as `Challenges` namespace. Implement the unit tests under the `tests` directory as `Tests` namespace.
* PHP 8.1+ required.

## Task 1: Make a Circle class with OOP

### Requirement
* Create a `Circle` constructor that creates a circle with a radius provided by an argument. (`php/src/Task1.php`)
  * The circles constructed must have two getters `getArea()` `(PI*r^2)` and `getPerimeter()` `(2*PI*r)` which give both respective areas and perimeter (circumference).
  * Don't worry about floating point precision.
* Please consider and implement unit tests that verify the basic requirements of each methods. (`php/tests/Task1Test.php`)

### Examples
```
$circle = new Circle(11);
$circle->getArea();

// Should return 380.132711084365

$circle = new Circle(4.44);
$circle->getPerimeter();

// Should return 27.897342763877365
```


## Task 2: Create a function to mask digits of a credit card number

### Requirements
* Create a function `maskCardDigits` to mask digits of a credit card number with `*`. (`php/src/Task2.php`)
  * Do not mask the first digit and the last four digits.
  * Do not mask non-digit chars like `-`.
  * Do not mask if the input is less than 6.
  * Return `''` when input is empty.
* Implement the unit tests to verify the requirements above. (`php/tests/Task2Test.php`)


## Task 3: Phrase or Word Inverse

### Requirements

* Create a function `invert` that inverts words or the phrase depending on the value of parameter type. (`php/src/Task3.php`)
  * A "P" means to invert the entire phrase, while a "W" means to invert every word in the phrase.
  * The first character of the returned string should be in uppercase and the rest are in lowercase.
  * There will be no empty strings as inputs. Punctuation marks, though quite important for grammatical correctness, are discounted in the input phrases.
* Implement the unit tests to verify the requirements above. (`php/tests/Task3Test.php`)


### Example

```
invert("This is Apple", "P") ➞ "Apple is this"

invert("One fine day to start.", "W") ➞ "Eno enif yad ot trats"

invert("Division by powers of three", "P") ➞ "Three of powers by division"

invert("", "P") ➞ ""
```
