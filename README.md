
<h2 class="wp-block-heading">前書き</h2>



<div class="wp-block-group">
<p>このリポジトリは、chshコマンドを実行して新しいウィンドウまたは次回ログイン時に使用するシェルを変更します</p>
</div>



<h2 class="wp-block-heading">インストールする必要のあるコマンド</h2>



<div class="wp-block-group">
<p>特に無し</p>
</div>



<h2 class="wp-block-heading">クイックスタート</h2>



<div class="wp-block-group">
<p>上記のコマンドをインストール済みの方は、以下のコマンドを実行してリポジトリからダウンロード後、ディレクトリを移動し、chshコマンドを実行後、新しいウィンドウを開くもしくはログアウトして、シェルが変更されたか確認してみてください</p>



<h3 class="wp-block-heading">ubuntu</h3>



<div class="wp-block-group">
<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/sh
#デスクトップ画面右上から一度ログアウトしてください
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>/bin/sh</code></pre>
</details>
</div>



<h3 class="wp-block-heading">macos</h3>



<div class="wp-block-group">
<h4 class="wp-block-heading">MacPorts</h4>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/zsh
#新しいウィンドウをctrl+nまたはcmd+nで開く
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>/bin/zsh</code></pre>
</details>
</div>



<h3 class="wp-block-heading">windows</h3>



<div class="wp-block-group">
<h4 class="wp-block-heading">WSL2</h4>



<div class="wp-block-group">
<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/sh
#一度プロンプトを閉じてもう一度開いてください
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>/bin/sh</code></pre>
</details>
</div>



<h4 class="wp-block-heading">MSYS2 MINGW64</h4>



<div class="wp-block-group">
<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>不可</code></pre>
</details>
</div>
</div>
</div>



<h2 class="wp-block-heading">実行手順</h2>



<div class="wp-block-group">
<h3 class="wp-block-heading">ubuntu</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドを端末に打ち込んでcommand not foundが出なければokです</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>
</div>



<h4 class="wp-block-heading">preinstall</h4>



<div class="wp-block-group">
<p>端末にcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>
</div>



<h4 class="wp-block-heading">コマンド</h4>



<div class="wp-block-group">
<p>以下のコマンドを端末で実行することで詳細のような文字列が出力されるはずです</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/sh
#デスクトップ画面右上から一度ログアウトしてください
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>/bin/sh</code></pre>
</details>
</div>
</details>



<h3 class="wp-block-heading">macos</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドをターミナルに打ち込んでcommand not foundが出なければokです</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>



<p>※macosはMacPortsパッケージマネージャを使用してコマンドを管理します。もしインストールしていない方は以下のリンクからMacPortsのインストール手順をご覧ください<br>またコマンドに別名を設定して既存の環境と競合しないでコマンドを呼び出せるようにします。<br>初めてこのブログを利用する方は、以下の2つの記事を参考に環境構築してください</p>



[![MacPortsをインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports_title_1920_1080_2.png,)](https://ss523971.stars.ne.jp/todo/how-to-install-macports)



[![MacPortsでインストールしたコマンドのエイリアス設定](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports2.png,)](https://ss523971.stars.ne.jp/todo/how-to-setup-macports-alias)
</div>



<h4 class="wp-block-heading">preinstall</h4>



<div class="wp-block-group">
<p>ターミナルでcommand not foundが出たコマンドを以下のコマンドでインストールしてエイリアスを設定してください</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>
</div>



<h4 class="wp-block-heading">コマンド</h4>



<div class="wp-block-group">
<p>以下のコマンドをターミナルで実行することで詳細のような文字列が出力されるはずです</p>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/zsh
#新しいウィンドウをctrl+nまたはcmd+nで開く
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>/bin/zsh</code></pre>
</details>
</div>
</details>



<h3 class="wp-block-heading">windows</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドをプロンプトに打ち込んでcommand not foundが出なければokです</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>



<p>※windowsはWSL2とMSYS2 MINGW64で確認しています。可能な限りWSL2をインストールしていただいて、もし設定できなかった場合はMSYS2をインストールすることで実行できますが、所々WSL2でしか実行できないコマンドが出てくるかもしれません。WSL2とMSYS2のインストール方法は下記の記事を参考にしてください</p>



[![[windows] msys2をインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_WSL2_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-wsl2/)



[![](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/msys2_thumbnail_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-msys2)
</div>



<h4 class="wp-block-heading"><strong>preinstall</strong></h4>



<div class="wp-block-group">
<p>プロンプトでcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>特にありません</code></pre>
</div>



<h4 class="wp-block-heading"><strong>コマンド</strong></h4>



<div class="wp-block-group">
<p>以下のコマンドをプロンプトで実行することで詳細のような文字列が出力されるはずです</p>



<h5 class="wp-block-heading">WSL2</h5>



<div class="wp-block-group">
<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>chsh -s /bin/sh
#一度プロンプトを閉じてもう一度開いてください
echo $SHELL</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>/bin/sh</code></pre>
</details>
</div>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<div class="wp-block-group">
<pre class="wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>不可</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>不可</code></pre>
</details>
</div>
</div>
</details>
</div>



<h2 class="wp-block-heading">後書き</h2>



<div class="wp-block-group">
<pre class="wp-block-code has-background" style="background-color:#abb8c3"><code>cat etc/shells #etcの前に/をつけてください</code></pre>



<p>を実行することで/bin/shや/bin/zsh以外のシェルに変更することが可能です<br>chshに-sオプションを付けない場合、エディタが開いて手動で変更することになります<br>動作確認が終了したら</p>



<pre class="wp-block-code has-background" style="background-color:#abb8c3"><code>cat etc/shells #etcの前に/をつけてください</code></pre>
</div>



<p>から、戻したいシェルを選択するか</p>



<pre class="wp-block-code has-background" style="background-color:#abb8c3"><code>chsh -s /bin/bash</code></pre>



<p>を実行してください</p>
