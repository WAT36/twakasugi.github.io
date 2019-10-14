---
title: "標準出力"
date: 2019-10-12T17:19:30+09:00
categories: [ "プログラミング" ]
tags: [ "java", "python", "標準出力"]
---

# 標準出力

標準出力について。

{{< tabs "standard_output" >}}
{{< tab "Java" >}}

クラスはここではMain.javaとする

```java
class Main{
    public static void main(String args[]){
        //出力後、改行したい時
        System.out.println(変数もしくはデータ);

        //出力後、改行したくない時
        System.out.print(変数もしくはデータ);
    }
}
```

javaで画面に出力したい時は **System.out.println()** を利用する。<br>
引数には画面に出力したい変数またはデータを入れる。
出力後改行したくない時は System.out. **print()** を使う。

{{< /tab >}}
{{< tab "Python" >}}

```python
x=(変数もしくはデータ)
print(x)        # xを画面に出力して改行する
print(x,end="") # xを画面に出力して改行しない
```

Pythonでコンソール画面への出力を扱うには組み込み関数の **print()** を使う。<br>
基本、入力された引数を画面に出力する。<br>
改行したくない場合はprint()のendパラメータに""を指定。<br>
詳しくは以下の公式ドキュメント参照。<br>
https://docs.python.org/ja/3/library/functions.html#print

{{< /tab >}}
{{< /tabs >}}