# Tasker-send-PIN-for-smartmeter-SML-
eHZB-W25E8-0LHPG-D6-A5Q1

Send smartmeter PIN with mobilephone's torch ;-)

Modify wait time for your meter if necessary.


Script for Tasmota:
>D
>B
=>sensor53 r
>M 1
+1,3,s,0,9600,Haus
1,77070100010800FF@1000,Zaehlerstand Total,kWh,180_zaehlerstand_total,-3
1,77070100020800FF@1000,Wirkenergie Total,Wh,280_wirkenergie_total,-3
1,77070100100700FF@1,aktuelle Wirkleistung,W,power,0
1,77070100600100FF@#,Server ID,,Server_ID,0
1,7707010060320101@1,Meter Nr,,Meter_number,0
1,77010b0a01445a47@1,Unbekannt,,unknown,0
#
