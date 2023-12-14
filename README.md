# PCB_Main
メイン電装部のPCBデータです．24代のメイン電装は2層構成になっており，上層をPCB_Main1,下層をPCB_Main2として設計しています．

# 使用している部品，フットプリント
テキスト印字→◯の部品は基板上にテキスト(ICS-Boardなど)を印字してください．
リファレンス印字→◯の部品は基板上にリファレンス(D1など)を印字してください．
## PCB_Main1
|リファレンス|部品|フットプリント|テキスト印字|リファレンス印字|
|:---:|:---:|:---:|:---:|:---:|
|D1~D8|[整流ダイオード](https://akizukidenshi.com/catalog/g/gI-08327/)|Diode_THT:D_A-405_P10.16mm_Horizontal|✕|✕|
|D9~D14|[LED](https://akizukidenshi.com/catalog/g/gI-06247/)|LED_THT:LED_D5.0mm|◯|✕|
|M78AR05-1~M78AR05-4|[DCDCコンバータ(5V0.5A)](https://akizukidenshi.com/catalog/g/gM-07179/)|Converter_DCDC:Converter_DCDC_RECOM_R-78E-0.5_THT|✕|◯|
|M78AR033-1|[DCDCコンバータ(3.3V0.5A)](https://akizukidenshi.com/catalog/g/gM-07178/)|Converter_DCDC:Converter_DCDC_RECOM_R-78E-0.5_THT|✕|◯|
|XH1~XH6|[XHコネクタ](https://akizukidenshi.com/catalog/g/gC-12842/)|((n)はピン数に合わせて)Connector_JST:JST_XH_S4B-XH-A_1x0(n)_P2.50mm_Horizontal|◯|✕|
|U1|[Raspberry Pi Pico](https://akizukidenshi.com/catalog/g/gM-16132/)|SamacSys_Parts:RPi_Pico_SMD_TH|✕|✕|
|U2|[BNO055](https://akizukidenshi.com/catalog/g/gK-16996/)|AE-BNO055:AE-BNO055|◯|✕|
|U3|[DPS310](https://www.switch-science.com/products/6286)|DPS310:DPS310|◯|✕|
|ICS-Board1|[ICS変換基板](https://www.amazon.co.jp/dp/B07XYZWJGD)|ICS:ICS|✕|✕|
|ICS-SW1A|[トグルスイッチ 3P1回路2接点](https://akizukidenshi.com/catalog/g/gP-12406/)|Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical|◯|✕|
|C1|[電解コンデンサ](https://akizukidenshi.com/catalog/g/gP-17897/)|Capacitor_THT:CP_Radial_D5.0mm_P2.50mm|✕|◯|

補足  
- 配置は別で送った配置図で指定されているものはそれに従ってください
- 四隅にM3のネジ穴を開けてください

## PCB_Main2
|リファレンス|部品|フットプリント|テキスト印字|リファレンス印字|



