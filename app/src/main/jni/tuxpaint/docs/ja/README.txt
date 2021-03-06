                                   Tux Paint
                                  バージョン 0.9.25

  子供向けのシンプルなお絵かきプログラム

          Copyright 2002-2020 by various contributors; see AUTHORS.txt
                            http://www.tuxpaint.org/

                        June 14, 2002 - August 25, 2020

     ----------------------------------------------------------------------

   +------------------------------+
   |目次                            |
   |------------------------------|
   |  * Tux Paintについて             |
   |  * Tux Paintの使い方             |
   |       * Tux Paint の起動        |
   |       * 起動画面                 |
   |       * メインの画面               |
   |       * 各種のツール               |
   |            * 描画ツール           |
   |            * そのほかの操作         |
   |  * 他の画像の Tux Paint への読み込み    |
   |  * その他のドキュメント                |
   |  * お問い合わせ先                   |
   +------------------------------+

     ----------------------------------------------------------------------

                                 Tux Paintについて

'Tux Paint' とは？

       　Tux Paint
       は、３歳以上の小さな子供向けにデザインされたフリーのお絵かきソフトです。シンプルで使いやすい操作方法と楽しい効果音を備え、マスコットキャラクターが子供たちの案内役を務めます。空っぽのキャンバスと様々な描画ツールが、子供たちの創造力をかき立てます。

ライセンス:

       　Tux Paint
       は、オープンソースのプロジェクトで、GNUの一般公衆利用許諾（GPL）基づき公開されているフリーソフトウェアです。このソフトウェアは無料で、プログラムのソースコードが利用可能です。（これにより、誰でも、機能を追加したり、不具合を修正したり、プログラムの一部を自分のGPLソフトウェアに使用することができます。）

       　ライセンスの全文は、GNU 一般公衆利用許諾契約書 をお読みください。

目指していること:

       簡単に、そして楽しく
               　Tux Paint
               は、一般向けの描画ツールではなく、小さな子供のためのシンプルなお絵かきソフトとなることを目指して、楽しく容易に使えるように作られています。効果音とマスコットキャラクターが、プログラムの操作をわかりやすく教えてくれるとともに、ユーザーを楽しませてくれます。また、大きくて見やすいイラスト調のマウスポインターを採用しています。

       拡張性
               　Tux Paint
               は、機能を拡張することができます。「ふで」や「はんこ」は、追加や削除が可能です。例えば、授業では、様々な生き物の画像を追加しておいて、生徒に生態系を描かせるといったことができます。それぞれの「はんこ」には、選択時に流れる音声、表示される説明文を設定できます。

       移植性
               　Tux Paint は、Windows, Macintosh, Linux
               など、様々なプラットフォームに移植されており、どのプラットフォームでも見た目や使い方は変わりません。Tux Paint
               は、Pentium 133のような旧式のシステムでもうまく動作し、さらに遅いシステムでも動作するように構築することもできます。

       簡単な操作
               　ユーザーは、コンピューターの複雑な機能に直接触れる必要がありません。描画中の作品は、プログラム終了時に保存され、再開時に表示されます。作品を保存するために、ファイル名をつけたりキーボードを使う必要はありません。保存された作品は、縮小画像の一覧から選択するだけで読み込むことができ、コンピューターの他のファイルにアクセスすることはありません。

     ----------------------------------------------------------------------

                                 Tux Paint の使い方

Tux Paint の起動

  Linux または Unix のユーザー

         　KDE あるいは GNOME のメニューの「グラフィックス」以下に、起動アイコンが設定されているはずです。

         　その他、シェルプロンプトで次のコマンドを実行する方法があります。

           $ tuxpaint

         　エラーが発生した場合は、端末にその内容が表示されます。

     ----------------------------------------------------------------------

  Windows のユーザー

                                                                    [アイコン]    
                                                                   Tux Paint  

         　インストーラーを用いて Tux Paint
         をインストールする際、スタート・メニューやデスクトップにショートカットを作成するかどうかが選択できます。ショートカットを作成していれば、これらのアイコンから簡単に
         Tux Paint を起動できます。

         　ZIP ファイルをダウンロードして Tux Paint
         をインストールした場合や、インストーラーでショートカットを作成しなかった場合は、「Tux Paint」のフォルダにある
         "tuxpaint.exe" のアイコンをダブルクリックします。

         　インストーラーを用いた場合、「Tux Paint」のフォルダは、通常、"C:\Program Files\"
         に配置されます。（インストール時に、これを変更することもできます）

         　ZIP ファイルを用いた場合、「Tux Paint」のフォルダは、任意の場所に配置できます。

     ----------------------------------------------------------------------

  macOS のユーザー

         　"Tux Paint" のアイコンをダブルクリックします。

     ----------------------------------------------------------------------

起動画面

       　Tux Paint を起動すると、タイトル画面が表示されます。

                                    [タイトル画面]

       　プログラムの読み込みが完了すると、何かキーを押すかマウスのクリックにより次に進みます。（タイトル画面は、約30秒後に自動的に閉じます）

     ----------------------------------------------------------------------

メインの画面

       　メインの画面は、次の各部に分けられます。

       　左側: ツールバー「どうぐ」

               　ツールバーには、描画や編集を行うためのアイコンがあります。

[どうぐ: ふで, はんこ, せん, かたち, もじ, まほう, ラベル, とりけし, やりなおし, けしゴム, さいしょから, ひらく, セーブ, いんさつ,
                                      やめる]

       中央部: 描画キャンバス

               　中央部の最も広い領域が描画キャンバスです。ここが絵を描く部分になります！

                                   [キャンバス部分]

               注: 描画キャンバスのサイズは、Tux Paint のウィンドウサイズに応じて変わります。Tux Paint
               のウィンドウサイズは、Tux Paint 設定ツールを用いて変更できます。その他の方法については、オプションについてのドキュメントを参照してください。

       　右側: セレクタ

               　セレクタに表示される内容は、使用しているツールに応じて変わります。例えば、「ふで」ツールでは、様々な種類の筆が表示され、「はんこ」ツールでは、はんこの画像が表示されます。

                             [セレクタ - ふで、もじ、かたち、はんこ]

       　下部: カラーパレット「いろ」

               　キャンバスの下側には、描画色を選択するためのカラーパレットがあります。

          [いろ - いろ - くろ、しろ、あか、ぴんく、おれんじ、きいろ、みどり、みずいろ、あお、むらさき、ちゃいろ、はいいろ]

               　右端には色についての２つの特別なオプションがあります。スポイトの形をした「カラーピッカー」は描いている絵の中から色を選ぶことができます。また、「レインボーパレット」では、何千もの色から描画色を選ぶことができます。

               注: カラーパレットの色は好みに応じて変更できます。変更方法については、オプションについてのドキュメントを参照してください。

       　最下部: ヘルプエリア

               　画面の一番下の部分では、Linux ペンギンの「Tux」が、様々なヒントや関連情報をご提供します。

                              「かたち」ツールの使い方を説明している例

     ----------------------------------------------------------------------

各種のツール

  描画ツール

         ペイントブラシ「ふで」

                 　右側のセレクタから筆の種類を、下のパレットから色を選んで、フリーハンドで描画します。

                 　ボタンを押したままマウスを動かすと、描画できます。

                 　描画中にはサウンドが流れます。筆の大きさが大きいほど、低い音になります。

     ----------------------------------------------------------------------

         「はんこ」ツール

                 　「はんこ」ツールは、スタンプやステッカーを集めたようなものです。馬や木、月など、あらかじめ用意された様々な写真やイラストを絵に貼り付けることができます。

                 　マウスのカーソル動きに応じて画像の輪郭が表示され、貼り付け位置と大きさがわかります。

                 　スタンプは、動物、植物、宇宙、乗り物、人物といった多くのカテゴリに分類されています。セレクタの左右の矢印のボタンを使ってカテゴリを切り替えることができます。

                 　スタンプを絵に貼り付ける前に、様々な効果を適用することができます（スタンプの種類によって異なります）。

                    * スタンプには色をつけることができるものがあります。その場合、カラーパレットが有効になり、スタンプを絵に貼り付ける前に色を選ぶことができます。
                    * スタンプは、右下の三角形のバーの中をクリックすることで、縮小・拡大することができます。
                    * 多くのスタンプは、右下の操作ボタンを使って、上下・左右に反転させることができます。

                 　個々のスタンプごとに効果音を設定することができます。画面下部の左側にあるボタンを押すと、効果音を再生することができます。

                 (注: "nostampcontrols"
                 オプションが設定されると、スタンプの拡大・縮小、反転が無効になります。詳しくはオプションについてのドキュメントを参照してください。)

     ----------------------------------------------------------------------

         「せん」ツール

                 　様々な種類の筆と好きな色を使って直線を描くツールです。

                 　直線を描き始める位置でマウスをクリックして、そのままマウスを動かすと、描かれる直線が、「ゴム紐」のような薄い色の線で表示されます。

                 　マウスを放すと、バネのような効果音とともに線が描画されます。

     ----------------------------------------------------------------------

         「かたち」ツール

                 　簡単な図形を描きます。

                 　まず、描きたい図形を、右側のセレクタから選択します。

                 　右下のオプションボタンで「かたち」ツールの動作を選択します。

                      　真ん中から広げる
                              　最初にクリックした位置を中心として図形を拡大します。（Tux Paint バージョン
                              0.9.24 までは、この動作しかありませんでした。）

                      　角から広げる
                              　最初にクリックした位置を左上の角として図形を拡大します。これは、他の多くのお絵かきソフトの標準的な動作です。（Tux Paint
                              バージョン 0.9.25 以降で追加されたオプション）

                 　注: "--noshapecontrols"
                 オプションをつけて起動するなどして、「かたち」ツールの動作の制御を無効にした場合、オプションボタンは表示されず、真ん中から図形を広げる動作になります。

                 　図形を描くには、キャンバス上でマウスをクリックし、そのままマウスを動かして図形を広げます。楕円や長方形のように縦横比を変えられる図形と、正方形や円のように縦横比を変えられない図形があります。

                 　マウスを放すと、図形の形と大きさが決まります。

                      　通常の動作

                              　通常の動作では、上記の後、マウスを動かして図形を回転させます。

                              　最後にもう一度マウスをクリックして、図形が完成します。

                      　簡易図形モード
                              　簡易図形モード("--simpleshapes"
                              オプション)が設定されている場合、図形を回転させる手順は省略され、マウスを放した時点で図形が描画されます。

     ----------------------------------------------------------------------

         「もじ」ツール、「ラベル」ツール

                 　まず、右側のセレクタからフォントを、下部のパレットから色を選択します。画面をクリックするとカーソルが表示され、文字を入力することができます。

                 　[Enter]キー、または[Return]キーを押すと文字が描画され、カーソルが次の行に下がります。

                 　[Enter] /
                 [Return]キーの代わりに[Tab]キーを押すと、文字が描画された後、カーソルは、次の行ではなく、右側に移動します。このように、１行の中で、異なったフォント、字体、フォントサイズ、色などを混在させたい場合に便利な方法です。

                 　文字の入力中に別の場所をクリックすると、入力内容を維持したまま、文字を貼り付ける位置をクリックした位置に移動させ、文字入力を続けることができます。

                      「もじ」ツールと「ラベル」ツールの違い

                              　「もじ」ツールは、Tux Paint
                              に以前からある、文字入力ツールです。このツールで入力した文字列は、絵と一体化するため、後から文字列の内容を編集したり、動かしたりすることはできません。一方、絵と一体化することで、上から塗りつぶしたり、「よごす」「そめる」「うきぼり」といった「まほう」ツールの効果で修正を加えることができます。

                              　Tux Paint バージョン 0.9.22
                              で追加された「ラベル」ツールでは、文字は絵から「浮いて」おり、文字列の内容、位置、フォント、色などの情報は個別に記録されます。これにより、「ラベル」は後から移動や編集が可能です。

                              　「ラベル」ツールは、Tux Paint 設定ツールや、"--nolabel"オプションにより、無効にすることができます。

                      多言語文字入力

                              　Tux Paint
                              では、様々な言語の文字を入力することができます。たいていのラテン文字（A-Z, ñ, è
                              など）は、直接入力できます。また、いくつかの言語では、入力モードを切り替えて、複数のキーの組み合わせを用いて文字を入力する必要があります。

                              　Tux Paint
                              が、個別の入力モードがサポートされている言語に設定されている場合、特定のキーを押下することで、入力モードを切り替えることができます。

                              　個別の入力モードがサポートされている言語と、入力モード切替キーの一覧 　注:
                              大抵のフォントには全ての言語の全ての文字は含まれていません。このため、入力したい文字が含まれるフォントに変更する必要がある場合があります。

                                 * 日本語— ローマ字入力方式のひらがな、カタカナ— 右 [Alt] キー
                                 * ハングル— 2-Bul入力方式— 右 [Alt] キー または 左 [Alt] キー
                                 * 繁体中文— 右 [Alt] キー または 左 [Alt] キー
                                 * タイ語— 右 [Alt] キー

     ----------------------------------------------------------------------

         「ぬる」ツール

                 　「ぬる」ツールは、絵の中の連続した領域を、選んだ色で塗りつぶします。

                 　注: Tux Paint バージョン 0.9.24
                 までは、このツールは「まほう」ツールのひとつでした。（「まほう」ツールについては、以下をご覧ください）

     ----------------------------------------------------------------------

         「まほう」ツール（特殊効果）

                 　「まほう」ツールは、様々な特殊なツールを集めたものです。右側のセレクタで、「まほう」の効果を選択することができます。効果を適用する方法は、クリック＋ドラッグ、単なるクリックなど、ツールごとに様々です。

                 　クリック＋ドラッグを使用するツールの場合、右側のセレクタの下部左側にある「描画」を表すボタンが有効になります。１クリックで画面全体に効果を及ぼすツールの場合、右側の「画面全体」を表すボタンが有効になります。

                 　「magic-docs」フォルダ内のドキュメント「まほう」ツールの一覧もお読みください。

     ----------------------------------------------------------------------

         けしゴム

                 　このツールは「ふで」ツールに似ています。クリック（または、クリック＋ドラッグ）をした部分が消されます。（消した部分は、白あるいはその他の色、また、レイヤーキャンバスなど、絵によって異なる状態に戻ります。）

                 　いくつもの大きさの正方形と円形の消しゴムがあります。

                 　正方形の輪郭がマウスカーソルの位置に表示され、絵のどの部分が消されるかを示します。

                 　消している間、「キュッキュッ」と擦って消す効果音が流れます。

     ----------------------------------------------------------------------

  そのほかの操作

         「とりけし」

                 　このツールをクリックすると、直前に行った操作が取り消されます。いくつもの操作をさかのぼって取り消すことができます。

                 　注: キーボードで [Control]-[Z] を押しても取り消しできます。

     ----------------------------------------------------------------------

         「やりなおし」

                 　このツールをクリックすると、「とりけし」ボタンで取り消した操作を元に戻すことができます。

                 　「とりけし」操作の後、描画を行っていなければ、取り消した全ての操作を元に戻せます。

                 　注: キーボードで [Control]-[R] を押しても元に戻せます。

     ----------------------------------------------------------------------

         「さいしょから」

                 　「さいしょから」のボタンを押すと、新規に絵を描き始めることができます。ダイアログ画面が表示され、キャンバスの背景色やレイヤー画像（後述）を選べます。

                 　注: キーボードで [Control]-[N] を押しても、新規作成が行えます。

                 レイヤー画像

                   　レイヤー画像には、塗り絵のページのようなもの（白黒の線で描かれ、色を塗ることができる）や、前景レイヤーと背景レイヤーに挟まれた部分に絵を描ける３Ｄ画像のようなものがあります。

                   　また、このほかに、背景レイヤーだけの画像も用意されています。

                   　「消しゴム」ツールを使用すると、元のレイヤー画像が消されずに残ります。また、マジックツールの「反転」と「ミラー」は、レイヤー画像も反転させます。

                   　レイヤー画像は、その上に絵を描いて保存すると新しい絵として保存され、元々のレイヤー画像自体は上書きされないので、後で（「さいしょから」ダイアログからアクセスして）何度でも使うことができます。

     ----------------------------------------------------------------------

         「ひらく」

                 　「ひらく」をクリックすると、保存されている全ての作品のリストが表示されます。リストが画面に収まりきらない場合は、上下の矢印のボタンでリストをスクロールできます。

                 　まず、絵をクリックして選択します。

                      * 　左下にある緑色の「ひらく」ボタンで、選択した作品を読み込みます。

                        　(または、開きたい作品をダブルクリックします）

                      * 　右下にある茶色の「けす」(ゴミ箱)
                        ボタンで、選択した作品を削除します。(本当に削除して良いか確認されます)

                        　注: バージョン 0.9.22
                        以降では、削除した作品は、デスクトップのゴミ箱に移動します（Linuxのみ）

                      * 　「かきだす」のボタンをクリックすると、ユーザーの標準の画像フォルダ（例："~/Pictures/TuxPaint/")に画像を出力します。

                      * 　左側の一番下にある青色の"スライドショー" のボタンを押すと、スライドショーモードになります。詳しくは
                        "スライドショー" をごらん下さい。

                      * 　右下にある赤色の "もどる" ボタンを押すと、絵を描く画面に戻ります。

                 　絵を開く時に、それまで描いていた絵が保存されていなければ、保存するかどうかを確認します。("セーブ" をご覧下さい。)

                 　注: キーボードで [Control]-[O] を押しても「ひらく」ダイアログを表示できます。

     ----------------------------------------------------------------------

         「セーブ」

                 　描画中の作品を保存します。

                 　一度も保存していない作品の場合、作品のリストに新しく追加されます。(つまり、新しいファイルを作成します)

                 　注: ファイル名の入力などを求めることはなく、カメラのシャッター音の効果音とともに、単に作品を保存します。

                 　一度保存した作品を「ひらく」コマンドから読み込んで修正した場合、以前の作品を上書きするか、新しく追加して保存するかを確認します。

                 　(注: "saveover" オプション、または "saveovernew"
                 オプションが設定されている場合は、確認せずに上書きします。詳しくは
                 オプションについてのドキュメントを参照してください。)

                 　注: キーボードで [Control]-[S] を押しても、保存操作が行えます。

     ----------------------------------------------------------------------

         　「いんさつ」

                 　このボタンを押して作品を印刷します！

                 　多くのプラットフォームでは、[Alt] key (Mac では [Option] キー)
                 を押しながら「いんさつ」ボタンを押すと、プリンターの設定画面が開きます。この機能は、フルスクリーンモードでは動作しない点に注意して下さい。

                      　印刷の無効化

                              　Tux Paint の設定ファイルで "noprint=yes"
                              と指定したり、コマンドラインで "--noprint"
                              オプションを指定すれば、"noprint" オプションが設定され、印刷が無効になります。

                              　(詳しくは オプションについてのドキュメント を参照して下さい。)

                      　印刷の制限

                              　Tux Paint の設定ファイルで "printdelay=秒数"
                              と指定したり、コマンドラインで "--printdelay=秒数"
                              を指定すれば、"printdelay" オプションが有効になり、印刷実行後 秒数
                              で指定した時間が経過するまで、次の印刷ができなくなります。

                              　例えば、"printdelay=60" とした場合、1分ごとに1度だけ印刷できます。

                              　(詳しくは オプションについてのドキュメント を参照して下さい。)

                      　印刷コマンド

                              (Linux 及び Unix のみ)

                              　Tux Paint は、PostScript
                              形式の印刷データを作成し、外部プログラムに渡して印刷を行います。標準の設定では、

                                lpr

                              　が外部プログラムとして使用されます。このコマンドは、設定ファイルの"printcommand"
                              変数に値を設定することで変更できます。

                              　フルスクリーンモードでなければ [Alt]
                              キーを押しながら「いんさつ」ボタンを押すと、別のプログラムが起動されます。標準の設定では、KDE
                              のグラフィカルな印刷ダイアログ

                                kprinter

                              　が使用されます。このコマンドは、設定ファイルの "altprintcommand"
                              変数に値を設定することで変更できます。

                              　印刷コマンドの変更方法の詳細については、オプションについてのドキュメント を参照して下さい。

                      　プリンターの設定

                              (Windows 及び macOS)

                              　標準の設定では、「いんさつ」ボタンを押すと、通常使うプリンターに出力されます。

                              　フルスクリーンモードでなければ、[Alt] (または [Option])
                              キーを押しながら「いんさつ」ボタンを押すと、印刷ダイアログが表示され、出力先などの設定を変更することができます。

                              　"printcfg"
                              オプションを用いて、プリンターの設定を保存することができます。このオプションは、コマンドラインで
                              "--printcfg" を指定するか、設定ファイルで "printcfg=yes"
                              を指定することで有効になります。

                              　"printcfg" オプションが有効な場合、プリンターの設定は、ユーザーの個人フォルダの
                              "print.cfg" から読み込まれ、設定を変更すると、このファイルに保存されます。

                              　(詳しくは オプションについてのドキュメント を参照して下さい。)

                      　印刷ダイアログのオプション

                              　標準の設定では、印刷ダイアログは、[Alt] キー (または [Option])
                              キーを押しながら「いんさつ」ボタンを押した場合にのみ表示されます（Linux/Unixでは、"lpr"
                              の代わりに "kprinter"が起動します。）

                              　この印刷ダイアログの動作は、設定により変更できます。毎回必ず印刷ダイアログを表示させるには、コマンドラインで
                              "--altprintalways"
                              を指定するか、設定ファイルで"altprint=always"
                              を指定します。また、"--altprintnever" オプション、または
                              "altprint=never" を指定することで、[Alt] キー (または
                              [Option]) の効果を無効にできます。

                              　(詳しくは オプションについてのドキュメント を参照して下さい。)

     ----------------------------------------------------------------------

         　「スライドショー」

                 　「スライドショー」機能は、「ひらく」ダイアログから利用できます。タックスペイントの中で簡単なアニメーションを再生したり、画像のスライドショーを再生したりすることができます。また、選択した画像を元にアニメーションGIFを書き出すこともできます。

                      　画像を選ぶ

                              　「スライド」セクションに入ると、「ひらく」ダイアログと同じように、保存したファイルの一覧が表示されます。

                              　次に、スライドショーで表示したい作品を、一つずつクリックして選択します。それぞれの画像の上に、スライドショーで表示される順番を表す数字が示されます。

                              　選択された画像をもう一度クリックすると、選択を解除し、スライドショーから除外します。同じ画像もう一度クリックすると、をリストの最後に追加できます。

                      　再生スピードの設定

                              　画面左下「かいし」の隣にあるのスライドバーで、スライドショーやアニメーションGIFのスピードを調節できます。
                              スライドバーを一番左に設定すると、Tux Paint
                              内でのスライドショーの自動進行が無効になり、次のスライドに進むにはクリックが必要になります。（以下をご確認下さい）

                              　注:
                              最も遅いスピードに設定するとスライドの自動進行が無効になります。１枚ずつ手動でスライドを進めたい場合に、この設定を用いてください。（この動作はアニメーションGIFには適用されません）

                      　Tux Paint 上での再生

                              　Tux Paint上でスライドショーを再生するには、「かいし」ボタンをクリックして下さい。(注:
                              作品を一つも選択していない場合、全ての作品が表示されます。)

                              　スライドショーの実行中は、[Space] キー、[Enter] キー、[Return]
                              キー、右矢印 キー、画面左下の "つぎへ"
                              ボタンのいずれかを押せば、手動で次のスライドに進みます。左矢印
                              キーで、前のスライドに戻ります。

                              　[Escape]
                              キーを押すか、右下の「もどる」ボタンをクリックすると、スライドショーを終了し、作品選択の画面に戻ります。

                      　アニメーションGIFの書き出し

                              右下の「かきだす」ボタンをクリックすると、選択した画像を元にアニメーションGIFファイルを生成します。

                              　注:
                              少なくとも２つの画像を選択する必要があります。（画像を１枚だけ書き出す場合は、「ひらく」ダイアログの「かきだす」オプションを用います）。１枚も画像を選択していない場合は、アニメーションGIFは生成されません。

                              　アニメーションGIFの生成中に [Escape]
                              キーを押すと、処理を中断して「スライドショー」ダイアログに戻ります。

                 　さらに「もどる」ボタンを押せば、「ひらく」ダイアログに戻ります。

     ----------------------------------------------------------------------

         　プログラムの終了

                 　「やめる」ボタンを押すか、Tux Paint のウィンドウを閉じるか、[Escape]
                 キーを押せば、Tux Paint が終了します。

                 　その際、本当に終了するかどうかを確認されます。

                 　作品を保存していない状態で、終了を選択した場合は、保存するかどうかを訪ねられます。さらに、新規に作成した作品でなければ、以前のバージョンを上書きするかどうかを確認されます。(上記の
                 "セーブ" をご覧下さい。)

                 　注: 終了時に保存した作品は、次に Tux Paint を起動するときに、自動的に読み込まれます。

                 　注:「やめる」ボタンと [Escape]
                 キーは、無効にできます。(Tux Paint 設定ツールで、"「やめる」ボタンを無効にする"
                 を選択するか、コマンドラインオプションで "--noquit" を指定します。)

                 　この場合、タイトルバーの「閉じる」ボタンか、[Alt] + [F4] キーで終了することができます。

                 　また、万一、上記のどちらの方法でも終了できない場合、[Shift] + [Control] + [Escape]
                 のキーの組み合わせで終了できる場合があります。(詳しくは オプションについてのドキュメント を参照して下さい。)

     ----------------------------------------------------------------------

         　効果音を消すには

                 　[Alt] + [S] キーを押すと効果音は無効になり、もう一度押すと有効になります。

                 　注: 設定ツールで、"効果音を有効にする" のチェックを外している場合や、コマンドラインで "--nosound"
                 オプションを指定している場合は、効果音は完全に無効化され、[Alt] + [S] キーによる効果音の操作はできません。

     ----------------------------------------------------------------------

                             他の画像の Tux Paint への読み込み

     　Tux Paint の「ひらく」ダイアログでは、Tux Paint
     で作成した画像だけが表示されます。その他の画像や写真を読み込んで編集するにはどのようにすれば良いでしょうか？

     　そのための方法は簡単で、画像ファイルを PNG (Portable Network Graphic) 形式に変換して、Tux Paint
     で作成した画像が保存されている、以下のディレクトリにコピーします。

     　Windows Vista, 7, 8, 10
             　各ユーザーの "AppData" フォルダ。例:
             "C:\Users\(ユーザー名)\AppData\Roaming\TuxPaint\saved\"

     　Windows 95, 98, ME, 2000, XP
             　各ユーザーの "Application Data" フォルダ。例: "C:\Documents and
             Settings\(ユーザー名)\Application Data\TuxPaint\saved\"

     　macOS
             　各ユーザーの "Library" フォルダ。例:"/Users/(ユーザー名)/Library/Application
             Support/Tux Paint/saved/"

     　Linux/Unix
             　各ユーザーのホームディレクトリの隠しディレクトリ ".tuxpaint" 以下。例:
             "$(HOME)/.tuxpaint/saved/"

     　注: Tux Paint で作成した画像を他のアプリケーションから開く場合も、これらのフォルダからになります。

　'tuxpaint-import' を使う

       　Linux または Unix では、Tux Paint と同時に、シェルスクリプト "tuxpaint-import"
       がインストールされています。このスクリプトは、NetPBM のツール ("anytopnm") を用いて画像を変換し、 Tux Paint
       のキャンバスに合うように画像サイズを変更 ("pnmscale") し、PNG 形式に変換 ("pnmtopng") します。

       　また、このスクリプトは、"date" コマンドを使用して、Tux Paint
       が保存するファイルの付与に使用する日付と時刻を取得します。(作品を保存したり開いたりするときに、ファイルネームを聞かれることはない、ということを思い出してください！)

       　使用法は、コマンドプロンプトで、取り込みたい画像のファイル名を引数として 'tuxpaint-import' を実行するだけです。

       　画像は変換された後、Tux Paint の保存フォルダにコピーされます。(注:
       子供など、他のユーザーのために変換作業を行う場合は、そのユーザーのアカウントでコマンドを実行する必要があります。)

       例:

         $ tuxpaint-import grandma.jpg
         grandma.jpg -> /home/username/.tuxpaint/saved/20020921123456.png
         jpegtopnm: WRITING A PPM FILE

       　1行目 ("tuxpaint-import grandma.jpg") が実行するコマンドで、続く2行がプログラムの実行中の出力です。

       　これで、Tux Paint
       を起動して、「ひらく」ダイアログから変換した画像を開くことができます。後は、アイコンをダブルクリックするだけです！

手動での取り込み

       　Windows、MacOS、BeOS、そして Haiku のユーザーは、手動で変換作業を行う必要があります。

       　変換したい画像ファイルの読み込み、PNG
       形式ファイルでの保存に対応した画像処理プログラムを起動します。(推奨されるソフトウェア、その他の情報については、"PNG.txt"
       をお読みください。)

       　Tux Paint で、描画キャンパスと異なる大きさの画像を読み込む場合、キャンバスに合うように拡大・縮小されます。

       　画像が引き伸ばされたりぼやけたりしないようにするには、キャンパスの大きさに合うようにサイズを変更します。キャンパスの大きさは、Tux Paint
       のウィンドウサイズや、フルスクリーン動作時の画面解像度に依存します。(注: 標準の解像度は 800x600 です)。以下の
       "イメージサイズの計算方法" をごらんください。

       　画像は PNG 形式で保存します。ファイル名は、以下の例のように、Tux Paint
       が使用する命名方式である、現在の日付と時刻を使用することを 強く 推奨します。

         YYYYMMDDhhmmss.png

         * YYYY = 年
         * MM = 月 (01-12)
         * DD = 日 (01-31)
         * HH = 時, 24時間表示 (00-23)
         * mm = 分 (00-59)
         * ss = 秒 (00-59)

       例:

         　2002年9月21日 午後1時5分ちょうどの場合 - 20020921130500

       　PNG file を Tux Paint の'保存' ディレクトリにコピーします。（上記参照）

  　イメージサイズの計算方法

         　Tux Paint のキャンバスの幅は、window の幅 (例：640, 800, 1024 ピクセルなど) から 192
         を引きます。

         　キャンバスの高さは、いくつかの手順を踏んでで計算します。

          1. Window の高さ (例： 480, 600, 768 ピクセルなど) から 144 を引く。
          2. 手順 1 の結果を 48 で割る。
          3. 手順 2 の結果の小数点以下を切り捨てる (例： 9.5 であれば、単に 9 とする)
          4. 手順 3 の結果を 48 倍する。
          5. 最後に、手順 4 の結果に 40 を加える。

         例: 解像度 1440x900 のディスプレイで、フルスクリーンモードで実行する場合。

           * キャンバス幅は、単純に、1440 - 192、すなわち 1248。
           * キャンバスの高さは、次のようにして算出。
               1. 900 - 144 で 756
               2. 756 / 48 で 15.75
               3. 15.75 を切り捨てて 15
               4. 15 * 48 で 720
               5. 720 + 40 で 760

         　このようにして、Tux Paint のウィンドウサイズが 1440x900 のとき、キャンバスサイズは 1248x760 となる。

     ----------------------------------------------------------------------

                                   その他のドキュメント

     　このドキュメントの他、"docs" フォルダには、次のようなドキュメントがあります。
       * 「まほう」ツールに関するドキュメント ("magic-docs")
       * AUTHORS.txt
         　作者と協力者のリスト
       * CHANGES.txt
         　リリース毎の変更点の概要
       * ライセンス情報
         　GNU 一般公衆利用許諾
       * INSTALL.txt
         　コンパイル、インストールの手順
       * EXTENDING.html
         　ブラシ、はんこ、背景画像の作成方法、フォントを追加する方法など。
       * OPTIONS.html
         　コマンドライン、設定ファイルのオプションに関する詳細な情報。Tux Paint Config を使用したくない人向け。
       * PNG.txt
         　PNG 形式の画像を作成する方法。
       * SVG.txt
         　SVG 形式のヴェクタ画像を作成する方法。
       * SIGNALS.txt
         　Tux Paint が応答する POSIX シグナルに関する情報。

     ----------------------------------------------------------------------

                                     問い合わせ先

     　不明な点があれば、遠慮無く New Breed Software までお問い合わせください。

       http://www.newbreedsoftware.com/

     　Tux Paint のメーリングリストに参加することもできます。

       http://www.tuxpaint.org/lists/
