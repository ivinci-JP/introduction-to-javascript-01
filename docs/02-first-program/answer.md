# 答え合わせ

1. プログラムの出力は次のようになります。
```
1
2
3
```

2. プログラム内のコードは次のようになります。
```js
function main() {
    console.log("I'm")
    console.log("learning")
    console.log("Kotlin!")
}
```

3. プログラムの正しいコードは次のとおりです。
```js
function main() {
    console.log("Monday");
    console.log("Tuesday");
    console.log("Wednesday");
    console.log("Thursday");
    console.log("Friday");
}
```

4. プログラムの 3 行目に、main 関数の関数本体の終了を示す閉じ中かっこがありません。
```js
function main() {
    console.log("Tomorrow is rainy");
}
```

5. プログラムを実行すると`TypeError: console.logs is not a function`というエラーが表示されます。これは、`console.logs`がJavaScriptでは認識されない関数であるためです。関数名を`console.log`に変更することでエラーが解消されます。
```js
function main() {
    console.logs("There is a chance of snow");
}
```

6. プログラムを実行すると`SyntaxError: Unexpected identifier`というエラーが表示されます。このメッセージでは、問題を解決するための方法が直接示されていません。これは、エラーのトラブルシューティングを行う場合によくあることで、予期しない動作を解決するためにコードを詳しく調べる必要があります。

よく見ると、コードの2番目の`console.log`の呼び出しにマークが付いており、この部分に問題があることがわかります。
これはJavaScriptでは各行に1つのステートメントのみが記述されていることが想定されているためです。
この場合、2番目と3番目の`console.log`関数呼び出しを別々の新しい行に移動することで、問題を解決できます。
```
/workspace/Main.js:5
    console.log("Cloudy") console.log("Partly Cloudy") console.log("Windy")
                          ^^^^^^^
```
正しいコード:
```js
function main() {
    console.log("Cloudy");
    console.log("Partly Cloudy");
    console.log("Windy");
}
```

7. プログラムを実行すると`SyntaxError: Unexpected token '('`というエラーが表示されます。
関数本体は、丸括弧`()`ではなく波括弧`{}`で囲む必要があります。
```js
function main() {
    console.log("How's the weather today?");
}
```
