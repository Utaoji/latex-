# latex設定
## .latexmkrc
ホームディレクトリ直下に
## settings.json
WSLの場合、

/home/username/.vscode-server/data/Machine/settings.json

あるいは

左下の歯車

↓

設定

↓

リモート[WSL:Ubuntu]

↓

右上にある『設定(JSON)を開く』

## Preamble.texおよびdir
自分の好きなディレクトリに配置。dirの名前も任意

dir/subfile/subfilename.tex 7行目の\bibliography{/Absolute/path/to/references}は、なぜか絶対パスでないと動かない。相対パスの方法もあるはず。。。
