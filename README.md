## prototype

> JavaScript は、 Java や C++ のようなクラスベースの言語を経験した開発者にとってやや紛らわしく、class というキーワードが予約語で、変数名に用いることができないにもかかわらず class の実装が提供されません。

> ただし、 JavaScript には 1 つだけオブジェクトの継承に関する概念があります。オブジェクトはプロトタイプと呼ばれる、他のオブジェクト（または null ）への内部的な繋がりを持っています。このプロトタイプオブジェクトは、あるオブジェクトがそのプロトタイプとして null を持つまで、プロトタイプを継承します。このような、オブジェクトが他のオブジェクトのプロトタイプとなる連鎖を、プロトタイプチェーンと呼びます。

[継承とプロトタイプチェーン - JavaScript | MDN](https://developer.mozilla.org/ja/docs/Web/JavaScript/Guide/Inheritance_and_the_prototype_chain)

## __proto__

> 1. prototype と __proto__ は別物
> 1. いわゆる "プロトタイプチェーン" は __proto__ プロパティで実現されている
> 1. オブジェクトを new するとき, コンストラクタ関数の prototype プロパティが指しているオブジェクトが, 生成されるオブジェクトの __proto__ に代入される

[prototype と __proto__ - フリーフォーム フリークアウト](http://d.hatena.ne.jp/cou929_la/20100929/1285770930)

## constructor

> オブジェクトの初期化で使用されたコンストラクタ関数を参照するconstructorプロパティ。
> constructorプロパティはコンストラクタのprototypeのプロパティであり、インスタンスからはprototypeを通じてアクセスすることができる。
> コンストラクタのprototypeにプロパティ/メソッドを追加する方法によってconstructorプロパティに入る値が変わるので注意。

[JavaScript - constructorプロパティについて - Qiita](http://qiita.com/orangemittoo/items/6ebdf028730bc2ecca7a)
