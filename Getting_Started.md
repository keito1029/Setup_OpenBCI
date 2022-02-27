  
## Getting Started  
  
OpenBCIの使用を開始するために知っておく必要のあるすべて  
  
### Ganglion Getting Started Guide  
  
1. [Ganglionバイオセンシングチュートリアルビデオ](https://www.youtube.com/watch?v=l13R_99h0qQ&feature=youtu.be)  
1. READMEよりOPENBCI GUIv5.0.9ダウンロード  
1. 以下の備品確認  
	1. OpenBCIガングリオンボード  
	1. OpenBCIガングリオンドングル  
	1. 6V AAバッテリーパック＆（x4）AAバッテリー（バッテリーは含まれていません）  
	1. （x4）ボード安定化用のプラスチック製脚  
	1. EEG電極：OpenBCIゴールドカップ電極、または独自の電極、および電極ペースト  
	1. またはEMG電極：スナップ電極ケーブルおよびスナップ電極  
	1. インターネットに接続されたコンピューター  
1. GUIツールを[ダウンロード](https://docs.openbci.com/Software/OpenBCISoftware/GUIDocs/#installing-the-openbci-gui-as-a-standalone-application)し起動  
```  
./Downloads/OpenBCI_GUI/OpenBCI_GUI  
```  
1. Bluetoothの接続  
	* libGanglionScan.so: cannot open shared object file: No such file or directory  
		恐らくjavaの設定でhomeディレクトリに起動に必要なライブラリがインストールされる様になっているので移動  
		```  
		mv libGanglionScan.so Downloads/OpenBCI_GUI/libGanglionScan.so  
		```  
  
	* その前にしたこと（[Linux Users: Serial Port Permissions](https://docs.openbci.com/Software/OpenBCISoftware/GUIDocs/#installing-the-openbci-gui-as-a-standalone-application)参照）  
		* id -Gn keito  
		 	dialoutが確認出来ていたので関係なかった  
		* lsusb  
		 	無名のまま出る システムにデバイスファイルを移動してないせいか結局無名のまま  
		* watch 'dmesg | tail'  
			USBのデバイスドライバ名を調べた結果/dev/ttyACM0  
		* windowsは起動画面のままフリーズした(Windows Users: How to run the GUI with High DPI Screens参照)  
  
  
  
  
	  
#### memo  

* [ハードウェアの詳細](https://docs.openbci.com/Ganglion/GanglionLanding/) 長いので飛ばして良い  
* OpenBCIガングリオンUSBドングル [追加購入](https://shop.openbci.com/products/ganglion-dongle)  
* 自分のOpenBCI_GUIをgitに上げる際にコピーに時間がかかるのでrsync使った
```
rsync -avrih ~/Downloads/OpenBCI_GUI/ ~/my_OpenBCI/
```
* 初回起動時のバッテリー電圧:5.39V
  

