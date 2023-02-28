# インストール方法
ここでは、歩行シミュレーションのソースコード編集のためのファイルインストール方法を記載します。

## 動作環境、前提ソフトウェア、必要ライセンス
### 動作環境
- [artisoc Cloud](https://mas.kke.co.jp/artisoccloud/)のインストールが閲覧に必要となります。

- artisoc Cloudの使用マニュアルは、artisoc Cloudログイン後、取得することが可能です。
- また、[artisoc Cloudのチュートリアル資料](https://mas.kke.co.jp/howto/artisoc-cloud-%e5%88%9d%e7%b4%9a%e3%83%81%e3%83%a5%e3%83%bc%e3%83%88%e3%83%aa%e3%82%a2%e3%83%ab)をWeb上に公開していますので、併せてご参照ください。

### 必要ライセンス
- artisoc Cloudでのシミュレーション実行のみ：
    - artisoc Cloud player ライセンス以上で可能
    - この場合、player ライセンスを登録のうえ、artisoc Cloudにアクセスし、ご覧ください。なお、実行のみの場合、結果ファイルを取得することはできません。
- artisoc Cloudでのソースコード閲覧、編集：
    - artisoc Cloud standard ライセンスで可能
- ソースコード（python）のみの閲覧
    - 誰でも利用可能
    - ただし、ソースコードはartisoc Cloud専用でのソースコードとなっており、pythonファイルをそのまま実行しても動作しないものとなります。
### 参考資料
- artisoc Cloud HP([https://mas.kke.co.jp/artisoccloud/](https://mas.kke.co.jp/artisoccloud/))

## インストール手順
1. 本リポジトリ内のあるファイル一式を「Code」> 「Download Zip」からダウンロードします。
![](../images/download-zip.png)

2. ダウンロードされた「PLATEAU-UC22-023-Pedestrian-Simulation-Model.zip」ファイルを解凍し、「model.json」ファイルを取得します。
![](../images/get-model.png) 

3. [artisoc Cloud](https://artisoc-cloud.kke.co.jp/)にアクセスします。
![](../images/artisoc-cloud-open.png)

4. 右上の「ログイン」ボタンから、ログインを行います。
![](../images/artisoc-cloud-login.png)

5. ログイン後、右上のボタンから「モデルをアップロード」を選択します。その後、モデルをアップロードできる画面に移るので、ドラッグアンドドロップにより、取得した「model.json」ファイルをアップロードします。これにより、インストール完了となります。
![](../images/push-model-upload.png)

![](../images/model-upload.png)