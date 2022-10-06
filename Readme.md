# LoopMusicPlayer-Core
``LOOPSTART・[LOOPLENGTH,LOOPEND]``  
のタグをもとにループ再生するミュージックプレイヤー用ライブラリ  
ループタグがなかった場合、曲全体をループします

## 注意事項
* ループ時に指定されたサンプルから数サンプルずれている可能性があります。(計算式がずさん)

## 開発環境(動作確認環境)
OS
* Windows 11(Ver.22H2) (x64)

Editor
* Visual Studio Community 2022  
* Visual Studio Code

## 更新履歴
|バージョン |日付(JST) |                                       実装内容                                       |
|:---------:|:--------:|:-------------------------------------------------------------------------------------|
|Ver.1.0.0.0|2021-11-18|初版(LoopMusicPlayer-CSharpより分離)                                                  |
|Ver.2.0.0.0|2021-12-31|オンメモリ再生の削除                                                                  |
|Ver.3.0.0.0|2022-01-07|導入されているBASSのプラグインに応じたコーデック・コンテナを読み込めるよう変更        |
|Ver.3.0.0.1|2022-10-07|Bass.InitのFrequencyフラグの削除                                                      |

## 謝辞
各依存パッケージを作成していただいてる方々に感謝を申し上げます。

## 作者より
このプログラムを使用し発生した、いかなる不具合・損失に対しても、一切の責任を負いません。
