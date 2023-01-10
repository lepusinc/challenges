# オブジェクト指向プログラミングを用いた円生成クラスの実装

## 概要
引数で指定された半径の円を作成する Circle クラスを実装してください。Circle クラスには、面積を計算する `getArea()` `(PI*r^2)` と周囲 (円周) を計算する `getPerimeter()` `(2*PI*r)` を実装します。

## Examples
```
$circle = new Circle(11);
$circle->getArea();

// 期待される戻り値: 380.132711084365

$circle = new Circle(4.44);
$circle->getPerimeter();

// 期待される戻り値: 27.897342763877365
```

## Notes
* PHPバージョンは 8.0+ にて実装してください。
* 浮動小数点の精度にはこだわる必要はありません。