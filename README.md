2D-FD　2次元非圧縮性流体シミュレーター

説明：

本プログラムは、2次元における非圧縮性ナビエストークス方程式の数値解を得るためのプログラムです。

可視化の方法や初期条件などをExcelファイル(Config.xlsx)で指定して2D-FD.pyを実行することで計算を行います。

計算結果は動画(GIF)と計算終了時点の各物理量(初期条件と同じ形式のExcelファイル)で出力されます。

各ファイルの説明：

config.xlsx　 可視化の方法、端の境界条件、障害物の位置、外力、流速と圧力の初期条件を記述します。

2D-FD.py　　　 mainメソッドを記述しているモジュールであり、他のモジュールの関数を呼び出して計算を実行します。

functions.py　境界条件や可視化に関わるメソッドを記述しているモジュールです。

parameters.py config.xlsxに記載された値の扱い方に関するメソッドを記述しているモジュールです。

terms.py　　　 非圧縮性ナビエストークス方程式の各項の計算に関するメソッドを記述しているモジュールです。

result(フォルダ) 初期条件と計算結果を順次格納します。

注意：

・本プログラムの計算結果は非商用・商用問わず自由に用いて構いませんが、
　商用するようなことがもしあれば、Twitter(X)の流体力学メモ(@fluidSuikouK)にDMまたはリプライでその旨をご連絡ください。
 
・本プログラムの利用は、使用者の自己責任の上でお願いします。
