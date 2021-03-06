＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃
＃
＃　　さとりすとの説明書
＃
＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃＃


■注意■
未知のバグにより編集中のファイルが壊れる場合がありますので、
必ずバックアップをとってから使ってください。

satori_editor_temp フォルダには、一時ファイルの設定が含まれていますので、
大きくなっていたらまめに削除するといいかもしれません。
（さとりすとを起動しているときは消さないでください。）


□これは何？□
伺かゴーストの「里々」辞書を編集するエディタです。
自動的にイベント名でリストアップしたりメモ帳とは違った編集ができます。

□つかいかた□
「ヘルプ」→「さとりすとwiki（公式ヘルプ）」
でさとりすとwikiのマニュアルを確認できます。

さとりすとwiki
http://wikiwiki.jp/satolist/


□使えるゴースト□
次の点に当てはまるゴーストは、正しく読み込むことができます。
・栞に「里々（satori.dll）」を使っていること
・文字セットがShift_JISであること
・辞書が暗号化されていないこと（.txt ファイルであること）
・（ゴーストフォルダ）/ghost/master/ 階層にsatori.dll が配置されていること



□利用規約・著作権意識□ (2014.12.15 版)
■さとりすとで作成したものについて
・「さとりすと」で作成したあなたのゴーストを含むすべてのコンテンツは100%あなたのものです。
・「さとりすと」を使用したからといって何かしなければならないことは全くありません。
・もし紹介してくれるならとても嬉しいです。（義務ではありません。）
　そのときは「さとりすとwiki」か作者ブログトップか配布ページへリンクをお願いします。
　配布ページにはバナーも置いていますので、良かったらダウンロードしてつかってください。

■さとりすとで作成したものを、対価を得て頒布・販売する場合について
・前項に記載のとおり、100%あなたものもですから対価を要求することはありません。
・「もしよかったら」無料にて、その頒布・販売物を作者にプレゼントしていただけますと
　これ以上なく嬉しいです。「もしよかったら」ご検討ください。

■「さとりすと」について
　（禁止ではありません。サンプルゴースト・テンプレート配布などに使っても良いです。）
　ただし、対価を得て「さとりすと」本体または「さとりすと」をメインコンテンツとするものの頒布・販売は禁止します。
・使用ライブラリのライセンスが絡んでくるので一部のみの配布はしないでください。
・このプログラムは無保証です。（使用ライブラリの利用規約による表示義務）

■これ以外で不明なことがあれば
・迷ったらそのまま使って頂いてかまいません。もちろん、相談いただいてもかまいません。
・明らかに禁止してることでなければ、大丈夫です。


□作者連絡先□
作者：ななっち
サイト:http://nanachi.sakura.ne.jp/index.html
メール：nanachi[at]hotmail.co.jp


□引用□
Ukadoc Project
https://code.google.com/p/ukadoc/
http://ssp.shillest.net/ukadoc/manual/index.html

□ありがとう□
アイコンと、色分けのデータ、surfaces.txt変換マクロ「SERIKO1to2」は もっしょくしさんが提供してくださいました。
http://gallnuts.webcrow.jp/index.shtml

「コンソールれしば」を使わせていただきました。
http://faerie.sakura.ne.jp/

「里々」を使わせていただきました。
http://ms.shillest.net/

「Azukiテキストエディタエンジン」を使わせていただきました。
http://sgry.b.sourceforge.jp/

□更新履歴□
2014.2.20 ファイルリストの廃止。ゴーストプロパティの追加。
2014.3.16 バグの修正。辞書ファイル追加機能の追加。
2014.3.21 「SAORIリスト」「セーブデータ初期化リスト」のsatori_conf.txtエディタ機能の追加。
2014.4.1　名前を「さとりすと」に決定。本公開バージョン。文字置換リストの追加。
2014.4.6　それっぽいファイルのウインドウD＆Dで読み込めるように。「表示」に簡易な色分け機能を追加。
2014.4.9　アプリケーションアイコンを設定。ダイアログのウインドウサイズを固定に。
2014.4.17 「リロード」「外部エディタで開く」をファイルイベントツリーの右クリックメニューに追加。
　　　　　検索機能の追加。文と単語群で表示を分けるようにしました。色分けでタブ文字に対応。
　　　　　一部のダイアログでEnter決定、Escキャンセルができるように。
　　　　　一部のメニューバーの項目にショートカットキーを追加しました。
2014.4.20 テキストエディタの入力補助の機能を追加しました。Ctrl+Spaceで表示できます。
2014.4.21 入力補助を自動表示に。新しいトーク作成でも入力補助を使えるように。
　　　　　入力補助の内容に里々のキーワードを追加。
　　　　　characters.ini エディタを追加。
　　　　　「ファイルイベントツリー」に「トーク数の確認」を追加。条件別のトーク数を確認できます。
2014.4.23 「れしばイベントログ」を追加。れしばのログをリスト化して確認できます。
2014.5.3   1.1.0 イベントエディタに「ゴーストに送信」ボタンを追加。バージョン情報の表示を追加。
2014.5.4　1.1.1 ファイルイベントツリーを右クリックでイベントの位置移動が可能に。
　　　　　　　　　ファイルイベントツリーを右クリックでも項目を選択できるようにしました。
2014.5.5　1.1.2 色分け機能を「オプション」に移動。
2014.5.5　1.1.3 テキストエディタ機能を変更。テキストエディタの右クリックメニューにテキストエディタ機能を追加。
2014.5.6　1.1.4 イベントエディタを閉じるショートカットキー追加。文字置換リストの右クリックメニューが無い問題を修正。
2014.5.7　1.1.5 検索機能に置換機能を追加しました。
2014.5.7　1.1.6 検索ウインドウのタブオーダーを調整。れしばの無視リストを保存するように。
2014.5.9　1.1.7 全角括弧の対応関係が怪しい場合の警告表示を追加。編集中のゴーストにのみスクリプトを送信するオプションを追加。
2014.5.15 1.1.8 デバッグにイベント名やReferenceをつきで確認できる「イベントを送信」を追加。デバッグ辞書を使ったデバッグ機能を追加。 
2014.5.17 1.1.9 デバッグの「変数を設定する」を「変数の設定と確認をする」に変更して変数を確認できるようにしました。
2014.5.23 1.1.10 「単語・文リスト」の右クリックに「項目を無効化」をつけました。無効化すると保存時に目印を付けて里々に実質的に呼び出されないようにします。
2014.5.29 1.1.11 スタートアップメニューの追加・コメントアウト機能の追加。
2014.6.1   1.1.12 スタートアップメニューの最近編集したゴーストを固定する機能を追加。サーフェスビューワ（ベータ版）追加。
2014.6.2   1.1.13 ドッキングパネルのレイアウトを保存するようにしました。
2014.6.5   1.1.14 ゴーストをリロードする機能が動かない問題を修正しました。
2014.6.7   1.1.15 イベントエディタのフォント設定を追加、れしば機能でOnで始まらないイベントを無視する機能を追加、ウインドウサイズなどを保存するようにしました。
2014.6.10  1.1.16 バグの修正。「開く」にスタートメニューを追加。ファイルイベントツリーのクリック時、単語群・文リストに同じファイル上のイベントのみ表示する設定を追加。
2014.6.15  1.1.17 インラインイベントをファイルイベントツリーに表示するようにしました。イベントエディタの右クリックメニューに「挿入」を追加。オプションから内容の編集ができます。
2014.6.18  1.1.18 バグの修正。ファイルイベントツリーの右クリックメニューに「リスト化を無効」を追加しました。
2014.6.21  1.1.19 ファイルイベントツリーの右クリックメニューに「辞書の設定」を追加。各種設定にデフォルトでリスト化を解除して読み込む機能を追加。検索機能にテキスト検索を追加。
2014.6.24  1.1.20 最近開いたゴーストの右クリックと「開く」メニューにそれぞれゴーストフォルダをエクスプローラで開く機能を追加しました。オプションが一部保存されない問題を修正しました。
2014.6.28  1.1.21 イベントエディタに「選択部をゴーストに送信」を追加。「条件」「名前」の間にサイズ変更のやつを追加。いくつかのバグの修正と外観の調整。
2014.7.3    1.1.22 「インストール設定」を追加。ゴーストを読み込んでいない場合に一部機能を使えないように設定。characters.iniのみを編集して閉じようとした場合保存しますかが表示されない問題を修正。
2014.7.6    1.1.23 「更新除外設定」を追加。nar作成、ねとわく更新情報作成、更新アップロード機能（テスト版）を追加しました。全イベントリストをクリックしても単語群・文リストに表示されない問題を修正しました。
2014.7.12  1.1.24 項目の追加ダイアログに設定項目を追加。サーフェスビューワにダブルクリックでサーフェス変更をイベントに挿入できる機能を追加。アクティブなイベントエディタのタイトルに「#」を表示するように調整。
2014.7.17  1.1.25 サーフェスパレットの機能を追加。タスクバーのジャンプリストに対応。
2014.7.21  1.1.26 参照リスト、文・単語群リスト、検索結果のカラムをクリックするとソートするように。里々以外のSHIORIもプレーンテキストとして編集できるようにするいくつかの設定を追加。
2014.8.3   1.1.29 リスト化解除のエディタで文単位でゴーストに送信する機能を追加。
2014.8.3   1.1.30 オプションのいくつかの項目を「テキストエディタ」「イベントエディタ」タブに独立。テキストエディタまわりの設定項目を追加。
2014.8.11  1.1.31 「拡張辞書デバッガ」を廃止。代わりに拡張辞書不要の「起動している編集中のゴーストを操作」を追加しました。
2014.8.13 1.1.32 「新しい項目」ダイアログにSHIORI Event一覧の機能を追加。
2014.8.17 1.1.33 「れしばイベントログ」にゴーストに接続ボタンを追加。さわり判定用の座標の作成機能を追加。サーフェスビューワにさわり判定表示機能を追加。サーフェスビューワにさわり判定のみのリロードを追加。その他、各種調整。
2014.8.??  1.1.34 サーフェスビューワが簡単なきせかえの切り替えに対応
2014.8.31  1.1.35 「ファイル」からゴーストを起動できるように。「外部テキストエディタで開く」・「全イベントリスト」を非推奨機能として非表示に。ゴーストを編集中に他のゴーストを開き直すと、一部設定ファイルの上書きが必要とされる問題を修正。「高度」オプションを追加
2014.9.1   1.1.36 予期しないエラーが発生した場合にダイアログの表示とエラーログ「error_log.txt」の出力をするようにしました。ファイル構成をすこし変更。
2014.9.4  1.1.37 サーフェスビューワにsurfaces.txtの倍率変更ツールを追加。サーフェスビューワに表示倍率の変更を追加。触り判定箇所の作成機能に倍率変更機能を追加。辞書内の置換機能にチェックボックスによる安全ロックを追加。
2014.9.6 1.1.38 「サーフェスビューワ」で触り判定領域を表示する際に、表示している着せ替えパーツについた触り判定も表示するようにしました。
2014.9.8 1.1.39 「辞書の検索」で非リスト化辞書とテキストファイルを検索対象に含めるようにしました。「検索結果」「参照リスト」「単語群・文リスト」に項目数を表示するようにしました。
2014.9.10 1.1.40 「SHIORI イベントのリファレンス」の追加。里々の内部関数の色分けが情報取得関数と同じになっていた＋足りてなかった問題を修正しました。
2014.9.14 1.1.41 「辞書の設定」に「辞書の自動テキストレイアウト」と追加。いくつかの設定でデフォルト値を変更。サンプルゴーストの更新のためのさとりすと側の対応。
2014.9.23 1.1.42  「スクリプトパッケージ」規格バージョン１のインポートに対応。ファイルの削除機能を追加。
2014.9.24 1.1.43 内蔵ブラウザを廃止しました。windows XP（.NET Framework4）用のエディションも公開しました。
2014.9.27 1.1.44 サーフェスパレットのオプションに無効化する設定を追加しました。surfaces.txtのさとりすと対応用記述に表示の有無の設定を追加しました。詳しくはreadme_surfacepalette.txt
2014.10.9  1.1.45 各種設定に、リスト化した辞書ファイルの項目間に空白行を自動挿入する機能を追加しました。
2014.10.20 1.1.46 ゴーストの新規作成・テンプレートを使用したゴーストの新規作成の機能を追加しました。
2014.10.28 1.1.47 ファイルイベントツリーの右クリックメニューに「辞書ファイルの名前変更・場所移動」・「項目名の一括変更」を追加しました。
2014.11.30 1.1.48 「スクリプト送信結果」を追加。多分「さとりて」のスクリプト表示と同じ。
2014.12.18 1.1.50 外部サイト「ukadoc」移転に伴いリンク先を変更。アップロード機能に差分アップロードを追加してテスト版の表示を外しました。
2015.1.1    1.1.51 色分け有効時に演算子を含む文字列を変数に【タブ】で代入しようとしている場合、警告として波線を表示するように。サーフェスパレットの起動中にゲージを出すように。
2015.1.6    1.1.52 「ゴミ箱」を追加。リストから削除されたイベントがテキストとしてさとりすと終了時まで一時的に配置されます。
2015.1.31　 1.1.53 「ファイル」メニューに「起動中のゴーストを開く」を追加。当たり判定作成機能でマウス座標の表示を追加。里々以外のゴーストを読もうとするとエラーになる問題を修正。サーフェスパレットの読み込み中ダイアログを消せてその場合におかしくなる問題を修正。
2015.2.1    1.1.54 「更新除外設定」の右クリックメニューに複数ファイルの追加機能を追加。「更新除外設定」の編集ダイアログをファイルドロップに対応。
2015.3.1    1.1.55 ファイルイベントツリーの右クリックメニューにイベントのソートを追加。ファイルイベントツリーのイベントをD&Dで移動できるように。その他ベータ版のデバッグ機能を公開。
2015.3.3    1.1.56 サーフェスビューワのオプションに描画領域の変更を追加。
2015.3.10   1.1.57 アップロード機能に自動リトライ回数を表示・キャンセルクリック時、リトライのタイミングでもキャンセルされるように。ゴースト新規作成時、マスターシェルの選択が可能に。
2015.3.14   1.1.58 「ファイルイベントツリー」の右クリックメニューに、更新がアップロードされていないファイルをマークする機能を追加。検索ウインドウの常に手前に表示を無効化。
2015.3.16   1.1.59 「ヘルプ」に「フィードバックの送信」と「オンラインアップデート（ベータ版）」を追加。
2015.3.22   1.1.60 更新ファイル作成時に未保存の変更があると警告するようにしました。アップロード機能の調整。
2015.3.24   1.1.61 各種設定に「半角スペースを見えるようにする」を追加。
2015.3.25   1.1.62 更新設定の操作性を向上。更新設定でFTP使用時、SSLを使用してFTPSによる送信を追加。パッシブモードを使用する設定を追加。サーフェスビューワのツールに「surfaces.txt を旧定義から新定義に変換する機能」を追加。
2015.3.25   1.1.63 初回起動時に、リスト化モードかリスト化解除モードか選択するようにしました。
2015.3.25   1.1.64 「各種設定」の「イベントエディタ」「テキストエディタ」でメニューバーを表示する設定を追加。「ファイルイベントツリー」の右クリックメニューに辞書ファイル単体を上書き保存する機能を追加。
2015.3.28   1.2     ネットワークアップデートをデフォルト有効に設定。参照リストの調整と呼び出し元の表示を追加。いくつかの操作をゴーストごとに記憶するように。
2015.4.8    1.2.1  色分け設定で背景色や通常文字色の変更を可能に。リストを表示する機能の右クリックメニューにダブルクリック時の操作を追加。イベントエディタを開いた時、本文にフォーカス・カレット位置を先頭にするように調整。
2015.4.11   1.2.2  色分け設定を強化、自作の正規表現も使用できるようになりました。
2015.5.1    1.2.3  色分け設定で、正規表現でないキーワードの色分けを追加。
2015.5.5    1.2.4  色分けにreplace/replace_afterの記述を追加。スタートメニューの履歴消去を右クリックメニューに追加。れしばを強化。アップロード機能でアップロードしたファイルを表示するように。
2015.7.18   1.2.9 サーフェスビューワでseriko.use_self_alpha,1 の場合に左上透過しないように。animation.option,background単体指定に対応。プラグインインターフェース変更。「オプション」にさとりすとフォルダを開くボタン設定。「ゴーストに送信」機能の里々への通信で、SecurityLevel: localに設定。
2015.7.21   1.2.10 設定に「Owned SSTPでスクリプトを送信」を追加。
2015.8.3    1.2.11 イベントエディタ・テキストエディタの「選択部分をゴーストに送信」が動かないことがある問題を修正・ショートカットキーを変更。トークの送信がトランスレートしたりしなかったりする問題を修正し、各種設定にオプションを追加。「高度」設定にイベントエディタ・テキストエディタにShioriEchoで送信するメニューを追加。
2015.10.18  1.2.12 辞書の全角（）の対応関係を検証の機能を強化し、辞書の簡易エラーチェック機能に名称変更。起動中のゴーストを開くダイアログのリストをダブルクリックでも開けるように調整。計算式の【タブ】による代入エラーのチェック精度を向上。
2015.11.10  1.2.13 ななろだ version2へのアップロードに対応。アップロード先選択に、FTP、ななろだ、ななろだversion2の選択肢を追加。　アップローダクライアントバージョンを1.1.0に。
2016.7.25   1.2.14 「さとりてウインドウ」機能を追加。辞書にファイルをたさなくても喋らせるだけ喋らせられるようになりました。
2016.7.30   1.2.15 当たり判定領域の作成機能で、多角形の場合は「Ctrl+左ドラッグ」で頂点を移動できるようになりました。
2016.10.9	1.2.16 サーフェスパレットの設定がsurfaces.txtにない場合、できれば顔っぽいっぽいところを表示するよう修正。挿入パレットのショートカットキーでShiftのみの設定は使えなかったのでその旨を付記＆落ちないよう修正。
2016.12.20	1.2.18 イベントを送信する機能にシチュエーション選択を追加。ひとまず初回起動だけいれてみる。
2017.6.18 1.2.20 「ジャンプ先の見つからないジャンプと選択肢を検索」ベータ版を追加。更新除外設定の問題を修正。nar作成で日本語ファイルの文字化けを修正。
2017.7.23 1.2.21 試験的に作者にゴーストアーカイブを送信する機能を追加
2017.7.30 1.2.22 「ファイル」に編集中のゴーストにbatやexeなどが入っていたらそれを実行できるようショートカットの機能を追加。作業フォルダは対象ファイルのあるフォルダになります。
2017.9.27 1.2.23 サーフェスビューワとサーフェスパレット、サポートへの送信にシェルのアップロードと更新ファイルの作成を可能に。読み込んだシェルのファイルをロックしないように修正。
2018.6.23 1.2.24 入力候補機能と入力候補の自動表示を非推奨機能に変更。代わりに入力候補検索ウインドウをCtrl+Spaceで出せるようにしたのと、Ctrl+Alt+SpaceでSHIORIイベントリストを出すようにしました。SHIORIイベントリストの検索機能を追加しました。更新ファイルとnarの作成・アップロードができるコマンドラインツール cmdtool.exe を追加しました（上級者向け）。
2018.7.7 1.2.25 スタートアップメニューのゴースト表示数を３０まで拡張。（windowsのジャンプリストの表示数は上位１０のままです。）スタートアップメニューからゴーストを右クリックで「編集中のゴーストのファイルを実行」と同じことができるようになりました。
2018.9.8 1.2.26 ななろだ、ななろだversion2でhttpsでのアップロードに対応しました。更新されたアップローダホストを使うのをおすすめします。
2018.11.17 1.2.27 「辞書の簡易エラーチェック」で辞書内の文・単語群・変数の名前被りをチェックするようにしました。
2019.1.6 1.2.28 OnSatolistBootイベントのReference2にさとりすとの本体パスを通知するように機能追加。
2019.1.12 1.2.29 更新データのアップロード機能で一度にNARとアップデートの両方をアップロードできるように改善。cmdtoolでアップロード機能のリトライが機能しない問題を修正。

2019.6.2 1.3.0　 細かい変更を色々。内部的な整理も少し。
・一部の非推奨機能を削除。内容を整理した際に障害になったためです。「全イベントリスト」「外部エディタで開く機能」「（古い）入力候補機能」
・一部の機能を単体のウインドウからドッキングウインドウに変更。「変数スナップショット」「変数の設定と確認」「イベントを送信」
・タイトルバーの表示をゴースト名を先に書くように変更
・「起動中のゴーストを開く」機能でゴーストが１体しか起動していなければ選択ウインドウを省略してそのまま開くよう変更。
・スタートメニューのゴースト右クリックから直接SSPを開けるように変更。
・「新しい項目」「新しいファイル」「辞書」を「辞書」メニュー内に集約。
・挿入メニューの機能でユーザ設定とさとりすとのデフォルト表示を両方表示する設定を追加。

2019.12.29 1.3.1　入力候補機能にプレビューを表示する機能追加。

