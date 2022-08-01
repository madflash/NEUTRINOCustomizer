# NEUTRINO Customizer patch
NEUTRINO Customizer patch for NEUTRINO  
NEUTRINOカスタマイズ拡張パッチ

## How to Install
in English:
1. Override these file to NEUTRINO Installed folder.
2. Finish.

in Japanese:
1. ファイルをNEUTRINOのインストールフォルダに置きます。
2. 完了

## How to use
in English:
1. Double click the "NC_Customizer.bat" file to run.
2. Input Score's name and VC's name on dialog style.
3. Done.

in Japanese:
1. "NC_Customizer.bat"ファイルをダブルクリックで起動します。
2. ダイアログでscoreファイルネームとボーカル名を入力します。
3. scoreフォルダにwavファイルが出来上がり。

## Settings
in English:
1. Open the "setting.txt" file by notepad or something cording tool.
2. Change bottom codes.

set ENABLE_SKIP=0  
-> When set 1 to skip dialog and user input.  
set ENABLE_OUTPUTNAME=1  
-> When set 1 to change output file names.  
set DEFAULT_NAME_SCORE=score  
-> Please set it up to score file's name. (default)  
set DEFAULT_NAME_VC=MERROW  
-> Please set it up to Vocaloid's name. (default)  

in Japanese:
1. "setting.txt"ファイルをメモ帳やコーディングツールで開きます。
2. 下のコードを変更します。

set ENABLE_SKIP=0  
-> 1に設定すると、ダイアログとユーザ入力をスキップします。  
set ENABLE_OUTPUTNAME=1  
-> 1を指定すると、出力ファイル名を変更する。  
set DEFAULT_NAME_SCORE=score  
-> スコアファイル名を設定してください。(デフォルト)  
set DEFAULT_NAME_VC=MERROW  
-> ボーカルの名前を設定します。(デフォルト)  

## Function
in English:
* Input and specify the score file name and vocal name in the dialog box.
* Export a wav file name in the format "score file name_vocal name_yyyyymmddhhssmmss".

in Japanese:
* ダイアログで、スコアファイル名やボーカル名を入力指定します。
* wavファイル名を「スコアファイル名_ボーカル名_yyyymmddhhssmmss」の形式で書き出します。
