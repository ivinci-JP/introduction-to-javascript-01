# 初めてのプログラムを実行する

![alt text](image-1.png) をクリックするとプログラムが実行されます。
コードエディタの下部にあるペインに、プログラムの出力（結果）が以下のように表示されるはずです。

```
Hello, world!
```
この出力からわかるとおり、このプログラムは Hello, world! というメッセージを出力（表示）することを目的としています。
JavaScriptは通常、1行目から順番に1行ずつ実行されます。

先頭の2行はおまじないなので気にしなくて良いです。・
```js
process.stdin.resume();
process.stdin.setEncoding('utf8');
```

この行によって'Hello, world!'というメッセージが出力されています。
```js
console.log('Hello, world!');
```

次に、関数について見ていきましょう。
