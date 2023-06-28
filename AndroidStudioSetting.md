# Android Studioのおすすめ設定
Android Studioのversionによって差異あり<br><br>
- [Match case](#matchCase)<br>
- [auto import](#autoImport)<br>
- [show whitespace](#whitespace)<br>
- [実機のスクショを撮る](#screenShot)<br>

## :tada: match case
<a name="matchCase"></a>
補完を出す時に大文字小文字を区別しないようにする。
```
preference > Editor > General > Code Completion
```
- [ ] Match case
 
のチェックを外す。<br>
デフォルトの設定だと、型の`Button`を出す時に`b`と打っても出てこない。`B`と打たないと出てこない。<br>

## :tada: auto import
<a name="autoImport"></a>
自動でimportを書いてくれる。不要なimportは自動で消してくれる
```
preference > Editor > General > Auto Import
```

- ✅ Add unambiguous imports on the fly
- ✅ Optimize imports on the fly<br>
 
上記のチェックを入れる。

## :tada: show whitespace
<a name="whitespace"></a>
```
preference > Editor > Appearance
```

- ✅ Show whitespace

のチェックを入れる

## :tada: 実機のスクショを撮る
<a name="screenShot">
Logcatのサイドバーにあるカメラマークを押すと実機のスクショが撮れる<br><br>
<img width="400" src="https://i.gyazo.com/fe2b32ee9984164a6c1e80448a6137bc.png">
