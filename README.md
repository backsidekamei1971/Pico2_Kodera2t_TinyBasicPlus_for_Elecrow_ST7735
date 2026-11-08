# Pico2_RP2035_Kodera2t_TinyBasicPlus_Elecrow ST7735S OLEDのみ
まず先に、この書込みプログラムは以下のようなElecrow ST7735Sディスプレイでないと何も画面に映らない<br>
<img width="1029" height="717" alt="IMG_9100" src="https://github.com/user-attachments/assets/997b0fc1-cc11-448d-aa1b-4feeaeb0c454" />

Kodera2t TinyBasicPlusシリーズの中で、<br>
これ↓だけが上手く【Pico2】に入る【Pico】には入らない<br>
https://github.com/kodera2t/tinyBASIC_OLED/blob/master/ATMega328P%2BColorLCD/Ada_ATMega328_LCD.ino <br>
まず先にボードマネージャで追加ボードで【Raspberry Pi】を選びインストール<br>
【File】→【Preference】でRaspberryのJSONファイルをインストール<br>
その後くらいに<br>
【一回目】はuf2接続(BootSelボタンを押しながらWindowsパソコンとUSB接続)で書込み→必ず失敗する<br>
【二回目】はCOM接続で再び書込み→そうすると成功する<br>
<img width="946" height="697" alt="IMG_8358" src="https://github.com/user-attachments/assets/d385f05d-b1ab-422e-be0f-a9ce1f7c1624" />
