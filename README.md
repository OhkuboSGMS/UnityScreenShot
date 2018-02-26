# UnityScreenShot
Super Small UnityPackage for ScreenShot
UniRxとシングルトンを用いたScreenShotのスクリプトです  

### 依存関係
 * UniRX
# How To Use
ScreenShot.unitypackageをUnityのプロジェクトを開いた状態で、クリックして開いてください、Import画面が出ます
.unitypackage内に　サンプルシーン[Sample]がありますのでそちらの方を参照してください

![inspector](http://i.imgur.com/bT7n8xd.jpg)

Screen Shot(Script)

* Main Code :主キーこれを一回押すと画像が１枚取得
* Sub Code :主キーの前に押して置かなければならないキー
* Is Debug :trueだとDebugに詳細表示
* FileName :ファイルの先頭につける名前
* StartIndex:連番の最初の値

画像の例だと Shift + S でスクショ撮影  
ファイル名は　test_0.png から始まる　次は,test_1.png

