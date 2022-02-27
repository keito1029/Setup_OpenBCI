# [Setting up for EEG](https://docs.openbci.com/GettingStarted/Biosensing-Setups/EEGSetup/)  
  
このページでは、OpenBCIボードを使用し、ゴールドカップ電極を使用してEEGデータを処理するための最も基本的なセットアップについて説明する．  
  
  
1. Connect your electrodes to OpenBCI  
  
* Ganglionボードへのピン接続  
	  
* Ganglionボード4つのスイッチは、 EEGの場合は「DOWN」に設定する
	既に全てDownになっていた
* ピン配置は[Ultracortex Mark IV](https://docs.openbci.com/AddOns/Headwear/MarkIV/#ganglion-board-setup)を参照
	左端のピン2つがイヤークリップで，残りの4つがチャンネル接続
	
  
  
1. Connect your electrodes to your head and body   
  
* この項目のアイテムがないので，[Related Headware](https://docs.openbci.com/GettingStarted/Biosensing-Setups/EEGSetup/#related-headware)より各ヘッドキャップにおける[Electrode Cap](https://docs.openbci.com/AddOns/Headwear/ElectrodeCap/)のセットアップを行う  
	このリポジトリのHeadwear_and_Electrodes/Electrode_Cap_Getting_Started_Guide.mdを参照すること  
	homeにcloneした際のvimエディタからの絶対パスと[githubリンク](https://github.com/keito1029/Setup_OpenBCI/blob/master/Headwear_and_Electrodes/Electrode_Cap_Getting_Started_Guide.md)  
	```  
	: tabe ~/Setup_OpenBCI/Headwear_and_Electrodes/Electrode_Cap_Getting_Started_Guide.md  
	```  
1. Launch the GUI and adjust your channel settings  
  
  
  
  
#### memo      
    
-[ ] ピン配置をどこにするか[Ganglionハードウェア仕様](https://docs.openbci.com/Ganglion/GanglionSpecs/#inverting-input-select-switches)を見て決める      
-[ ] チュートリアルにおける[cytonのピン配置](https://docs.openbci.com/GettingStarted/Biosensing-Setups/EEGSetup/#1-connect-your-electrodes-to-openbci)を見ながら実際にピンを配置 ただし使うヘッドキャップは異なる為，このピン配置とチュートリアルを参考にして良いのかわからない とにかくアルファ波が正常に計測できているのか知りたい
-[ ] 19chのキャップにおける[ピン配置](https://docs.openbci.com/AddOns/Headwear/ElectrodeCap/)を見る しかし，これはcytonにおけるピン配置である為，ganglionのハードウェア仕様を参照しなければならない
     
#### Additional Information    
    
* [Ganglionハードウェア仕様](https://docs.openbci.com/Ganglion/GanglionSpecs/#inverting-input-select-switches)     
	Ganglionのオープンソースの回路やピン配置が書いてあってとても便利
  

