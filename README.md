POV-Ray-sublime
===============

A Sublime Text 2 package for the POV-Ray.  
* MacOSX:Syntax highlight, more snippets, rendering
* Windows:Syntax highlight, more snippets  
MacOSXでは編集とレンダリングを行うことができます。Windowsでは編集のみ行うことができます。

POV-Ray: [http://povray.org/](http://povray.org/)

##準備:

Windows : 必要ありません

MacOSX : ソースコードをビルドするか、MacPortsやhomebrewを利用してインストールしてください。ビルドされたpovray実行ファイルが配置されているディレクトリをPATHに追加するか、PATHが既に指定されているディレクトにエイリアスを作成してください。

##インストール
###Gitを利用する
ターミナルでSublime Text 2の`Pakages`へ移動し、以下のコマンドを実行してください。  
`git clone https://github.com/cho-design-lab/POV-Ray-sublime "POV-Ray"`  

###手動
1. 本リポジトリの右側にある`Download Zip`からファイルをダウンロード
2. Zipファイルを解凍
3. ディレクトリ名を`POV-Ray`へ変更する
4. Sublime Text 2のPackageディレクトリの中に移動する (Prefarence -> Browse Packages...)

##レンダリング(MacOSXのみ)
###INIファイルの準備
POV-Rayのレンダリングの設定(解像度など)は`povray.ini`に記述されています。  
標準の`povray.ini`を変更するのは危険なので、作業するディレクトリへコピーします。  
copy `ex. (using homebrew) ~/.povray/3.6/povray.ini` to `woking directory`

###レンダリング開始
作業ディレクリにPOV-Rayシーンファイルを作成し、`*.pov`で保存します。  
レンダリングは`tool -> bulid` or `command + B`で行います。  
