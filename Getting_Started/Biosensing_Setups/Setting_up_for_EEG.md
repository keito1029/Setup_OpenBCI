# [Setting up for EEG](https://docs.openbci.com/GettingStarted/Biosensing-Setups/EEGSetup/)

このページでは、OpenBCIボードを使用し、ゴールドカップ電極を使用してEEGデータを処理するための最も基本的なセットアップについて説明する．





#### memo    
  
* OpenBCIガングリオンUSBドングル [追加購入](https://shop.openbci.com/products/ganglion-dongle)    
* 自分のOpenBCI_GUIをgitに上げる際にコピーに時間がかかるのでrsync使った  
```  
rsync -avrih ~/Downloads/OpenBCI_GUI/ ~/my_OpenBCI/  
```  
* bluetoothトングルがあれば，PCがbluetooth機能オフ状態でも計測可能と思われる  
* 初回起動時のバッテリー電圧:5.39V  
    
#### Additional Information  
  
* 各ヘッドキャップにおけるセットアップ

	このリポジトリのHeadwear_and_Electrodes/Electrode_Cap_Getting_Started_Guide.mdを参照すること
	homeにcloneした際のvimエディタからの絶対パス
	```
	: tabe ~/Setup_OpenBCI/Headwear_and_Electrodes/Electrode_Cap_Getting_Started_Guide.md
	```


