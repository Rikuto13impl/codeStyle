# Android Style Guide
[ルール](#rule)<br/>
[命名](#name)<br/>
[関数について](#method)
## 目的
- 一貫した書き方にすることで可読性をあげて誰でも見やすいコードになる
- バグの発生を防止。
- 迷いをなくす。スタイルガイドが決まっていることで少しでも悩む時間を減らす。

## ルール
<a name="rule"></a>
- オーブンブラケット ←`{` は同じ行に記述する
 ```java
// bad
if (isEnable) 
{
}

private void something()
{
}

// good
if (isEnable) {
}

private void something() {
}
```
- `if`の後ろには空白を入れる 
```java
// bad
if(isEnable) {

}else{

}

// good
if (isEnable) {

} else {

}
```
- `,`の後には空白を入れる
```java
// bad
private void something(String beforeString,String afterText) {}

// good
private void something(String beforeString, String afterText) {}
```
## 命名
<a name="name"></a>
命名はコードにおいて非常に重要です。一番と言ってもいいです(個人的には)。<br>
適切な命名を心がけることでチーム開発を円滑に進めることができます。

命名は具体的であるほどいいです。
省略は避けましょう。`Button`を`Btn`にするなど

具体的にしたら変数名が長くなってしまいますが大丈夫です。どうせ補完で出てくるので気にしないでください。
なんの変数なのかわからないよりは100倍マシです。ChatGPTを活用するもの良いでしょう。<br>
ここでは押下したらユーザーの情報を取得するボタンの命名を考えて見ましょう。
```java
// bad
private Button getBtn

// good
private Button getUserInfoButton
```
このように具体的であることでなんのボタンなのかを一発でわかるようにしましょう。
「具体的で誤解(意味を勘違い)しない命名」を心がけてください
### 変数
camel記法で命名する
基本的には名詞を使用して命名する。
しかし、ボタンなどの特定のアクションをトリガーする場合は動詞を含めることもある
### 関数
camel記法
動詞から始める。

## 関数(メソッド)について
<a name="method"></a>
### 単一責任の原則
一つのタスクを任せる。
複数のタスクを任せると行数も長くなり可読性や保守性に影響を与える。

処理に沿った命名にする。
逆に命名がうまくできない時には処理の切り分けがうまくできていないと考える
## 最後に
- 実装などで迷ったら臆さずに聞いてください。
- 時間を奪ってしまうなどは考える必要はないです。
もちろん自分で考えることは必要ですが。
- 提案なども積極的にして頂いて大丈夫です。
