# ExpCircle
指数関数的に増大する半径の円を描画できるスクリプトです。

現在は **version 1.0** が最新です。

![thumbnail](https://github.com/Aodaruma/expcircle/blob/main/expcircle.png)

以下のスクリプトが備わっています。

## ExpCircle.obj

以下はパラメーターの説明です。

- **トラックバー/チェックボックス**
  - cx
    - 円の中心のX座標を設定します
  - cy
    - 円の中心のY座標を設定します
  - rotation
    - 中心からの回転を設定します
  - radius(pow)
    - 円の半径の指数を指定します。指定した値は、`powbase ^ radius(pow)`として半径に設定されます
    
  
- **ダイアログ**

  - divnum
    - 分割数を設定します
  - color
    - 円の色を指定します
  - error(pow)
    - ポリゴンのカリングの許容値を設定します。あまり大きい値だと動作が重くなります。
  - powbase
    - 半径の底を設定します。

    

## 導入方法 / how to install

[ここ](https://github.com/Aodaruma/Aodaruma-AviUtl-Script)を参照してください。


## バグ・意見 / how to report bugs

バグや意見等については、Twitter の DM に送るか、issue を立ち上げてください。

## 変更履歴 / change log

- v1.0 - 正式配布
