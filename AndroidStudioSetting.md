# Android Studioのおすすめ設定
Android Studioのversionによって差異あり<br><br>
[Match case](#matchCase)<br>
[auto import](#autoImport)<br>
[show whitespace](#whitespace)<br>

## match case
<a name="matchCase"></a>
**preference > Editor > General > Code Completion**<br>

補完を出す時に大文字小文字を区別しないようにする。<br>
- [ ] `Match case`
 
のチェックを外す。<br>
デフォルトの設定だと、型の`Button`を出す時に`b`と打っても出てこない。`B`と打たないと出てこない。<br>

## auto import
<a name="autoImport"></a>
**preference > Editor > General > Auto Import**<br>

自動でimportを書いてくれる。不要なimportは自動で消してくれる
- [x] Add unambiguous imports on the fly
- [x] Optimize imports on the fly<br>
 
上記のチェックを入れる。

## show whitespace
<a name="whitespace"></a>
**preference > Editor > Appearance**

- [x] Show whitespace

のチェックを入れる
