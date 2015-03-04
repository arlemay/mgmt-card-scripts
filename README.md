mgmt-card-scripts
=================

Scripts used to find mgmt cards ilo drac fsp


HP Ilo example

{{{[WOPR2 mgmt-card-scripts]$ sudo ./findilos x.0.0.0/24
Scanning...

--------------- ------ -------- ------------ -------------------------
iLO IP Address  iLO HW iLO FW   Server S/N   Productid   Server Model 
--------------- ------ -------- ------------ -------------------------
x.0.0.112    iLO-2  2.07     USxxxxxxxx   N/A        ProLiant DL580 G5
x.0.0.113    iLO-2  2.06     MXxxxxxxxx   N/A        ProLiant DL320 G5p
x.0.0.114    iLO-4  2.02     MXxxxxxxxx   7xxxxx-xxx ProLiant DL320e Gen8 v2
x.0.0.115    iLO-4  2.02     MXxxxxxxxx   7xxxxx-xxx ProLiant DL320e Gen8 v2
x.0.0.116    iLO-4  2.02     MXxxxxxxxx   7xxxxx-xxx ProLiant DL320e Gen8 v2
x.0.0.117    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8
x.0.0.118    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8
x.0.0.119    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8
x.0.0.11a    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8
x.0.0.11b    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8
x.0.0.11c    iLO-4  2.02     MXxxxxxxxx   6xxxxx-xxx ProLiant DL320e Gen8

11 iLOs found on network target x.0.0.0/24.
}}}

IBM fsp example 

 {{{[@WOPR2 mgmt-card-scripts]$ sudo ./findfsps x.x.xx.0/21
Scanning...

--------------- ------ ---------------------------------- -------------------------
fsp IP Address  fsp HW fsp FW               Server S/N   Server Model
--------------- ------ ------------------------------------ -------------------------
x.x.xx.125    N/A    N/A                  N/A          N/A
x.x.xx.126    N/A    FW810.20 (SV810_xxx) 2xxxxxx      8247-22L
x.x.xx.127    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.128    N/A    N/A                  N/A          N/A
x.x.xx.129    N/A    AL730_049            1xxxxxx      8233-E8B
x.x.xx.12a    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.12b    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.12c    N/A    FW810.21 (SV810_108) 2xxxxxx      8247-22L
x.x.xx.12d    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.12e    N/A    FW810.11 (SV810_xxx) 2xxxxxx      8247-22L
x.x.xx.12f    N/A    AL710_119            0xxxxxx      8233-E8B
x.x.xx.130    N/A    AL710_083            0xxxxxx      8233-E8B
x.x.xx.131    N/A    AL730_035            1xxxxxx      8202-E4B
x.x.xx.132    N/A    AL770_008            1xxxxxx      8205-E6D
x.x.xx.133    N/A    AL730_099            0xxxxxx      8231-E2B
x.x.xx.134    N/A    AL730_035            0xxxxxx      8231-E2B
x.x.xx.135    N/A    AL770_007            1xxxxxx      8231-E2D
x.x.xx.136    N/A    FW810.20 (SV810_xxx) 1xxxxxx      8286-42A
x.x.xx.137    N/A    FW810.00 (TV810_028) 1xxxxxx      8284-22A
x.x.xx.138    N/A    FW810.20 (SV810_896) 2xxxxxx      8247-22L
x.x.xx.139    N/A    FW810.20 (SV810_101) 1xxxxxx      8247-22L
x.x.xx.13a    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.13b    N/A    FW810.10 (SV810_081) 2xxxxxx      8286-42A
x.x.xx.13c    N/A    FW810.20 (SV810_101) 2xxxxxx      8247-22L
x.x.xx.13d    N/A    FW810.10 (SV810_081) 2xxxxxx      8286-42A
x.x.xx.13e    N/A    AL720_082            1xxxxxx      8231-E2B
x.x.xx.13f    N/A    AL720_082            1xxxxxx      8231-E2B
x.x.xx.140    N/A    FW810.20 (SV810_xxx) 2xxxxxx      8247-22L
x.x.xx.141    N/A    FW810.20 (SV810_xxx) 2xxxxxx      8247-22L

29 fsps found on network target x.x.x.0/21.
}}}

