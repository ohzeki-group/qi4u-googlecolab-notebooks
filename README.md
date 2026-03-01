# qi4u-googlecolab-notebooks

## 目的
ドキュメントストレージにGoogleColabを表示させるためのもの。

ドキュメントストレージ： https://qi4u-materials.onrender.com/

## 使い方
1. 追加したいipynbファイルをこのリポジトリに追加する。
2. ipynbファイルのURLを取得する。
3. ストレージ側の`EmbedColab`コンポーネントを利用して、取得したURLを貼る。

ipynbファイルのURLは、
```
https://github.com/{owner}/{repo}/blob/{branch}/{path}.ipynb
```
形式を想定しています。