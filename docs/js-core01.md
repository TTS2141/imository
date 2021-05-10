## 変数を使う

*JavaScript*  
*2021.5.10* 

---

### 変数とは？

プログラミングでは、電卓で計算するときのように数値（123など）を直接入力するのでなく、**変数**としてあつかうことが多いです。**変数は値を指し示す名前**です。

変数を使うと、値を参照することができるので、何度も繰り返し使ったり、値を入れ替えたりすることができます。また、変数の名前で値が示す内容がわかりやすくなります。  
JavaScriptで扱える値（型）として、数値、文字列、配列などがあります。


### 変数の使い方
変数を宣言する（使い始める）には、`let`や`const`を使います。
`let`のかわりに`var`でも大丈夫です。`const`は値を変更しない場合に使います。
```
let x;
```

値を変数に代入（入れる）には`=`を使います。
```
X = 10;
```
数学で使う`=`と少し違って、右の値を左の変数xに代入するという意味です。

変数を宣言すると同時に値を入れることもできます。
```
let X = 10;
```

変数には、数値だけでなく、文字列の値も代入できます。
```
let name = "美樹さやか";
```

### コンソールで変数を使う
ブラウザのコンソール画面を出して、変数を操作してみます。
Cromeで複数行を入力するときは、`Shift`+`Enter`を押します。

```
> let x=10;         // 変数xを宣言して、10を代入
  console.log(x);   // コンソールにxの値を出力
  10                // 出力結果
```
文字列を入力するときは、文字列を " または ' でかこみます。　　
```
> let name = "美樹さやか";  // 変数nameを宣言して、"美樹さやか"を代入
  console.log(name);       // コンソールにnameの値を出力
  美樹さやか                // 出力結果
```

---
[Topに戻る](../index.html) 
