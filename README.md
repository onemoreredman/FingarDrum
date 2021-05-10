# FingarDrum
# 作品説明
Midiキーボードで設定した鍵盤を押すと、図形が表示される作品です。
https://youtu.be/NEEVg0PcmTs 

# プログラムの説明
Shape.pde:親クラス
line.pde,Square.pde,line.pde,Circle:子クラス
drum.maxpat:processingとMidiキーボードをつなげるプログラム

鍵盤を押すと、Shape型のlisに子クラスのインスタンスが追加されます。
図形が下の画面まで落ちたら、listから削除するプログラムです。

