# NVE in Circuit Game
[CircuitGame](https://github.com/bem130/circuitgame)の中でNVEを実装したい  

[CircuitGame](https://github.com/bem130/circuitgame)というのは[Bem130](https://github.com/bem130)が開発している論理回路シミュレータのこと  
NVEというのは[Bem130](https://github.com/bem130)が開発しているプログラミング言語であるNLPの実行環境[NLPS](https://github.com/neknaj/nlps)に含まれる、仮想マシンのこと  

## CircuitGame
Bem130Server [https://neknaj.bem130.com/repos/circuitgame/3deditor.html](https://neknaj.bem130.com/repos/circuitgame/3deditor.html)  
GithubPages [https://bem130.github.io/circuitgame/3deditor.html](https://bem130.github.io/circuitgame/3deditor.html)  
上記どちらかのリンクで開くことができる  
両方とも同じはずである  

## このリポジトリの目的

CircuitGameでNVEを実装する過程を保存して公開する  
つまり(?)私の備忘録だ  

## 形式

Base64形式かNCGファイルで回路のデータを張り付ける  
(Base64はCircuitGame内で回路のデータのコピペに使っている形式)  
(NCGはNeknajCircuitGameの略で、CircuitGameのプロジェクトファイルの拡張子)  

NCGはブラウザ版CircuitGameではLoadFileボタンから読み込むことができる  
Base64はブラウザ版CircuitGameではEditorのEditModeでペーストすることができる  

それぞれデータの下にはできたら回路の画像を貼る
