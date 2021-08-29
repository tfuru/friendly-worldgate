# friendly-worldgate
触れた途端にワールド移動するゲートはちょっと不親切なので、  
転送先のワールドサムネイルを表示してから転送されるゲート が作れる  
Unity エディタ拡張

# 使い方
1. unitypackage を 設置したいワールドへインポートする
2. メニューに World-Creator-Support -> FriendlyWorldGate が追加されている
3. FriendlyWorldGate を選択して起動
4. ワールドURLを設定して作成ボタンを押す
5. Hierarchy に FriendlyWorldGate が追加される
6. `FriendlyWorldGate` を 右クリック Unpack Prefab で　カスタマイズする

#  仕組み
1. Unity 上でワールドのサムネイル画像をダウンロード
2. 元になるPrefabに画像を設定する
3. Hierarchyに設置
