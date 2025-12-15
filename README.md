# KiCad-Template-M5Stack
a PCB template of modules of M5Stack with footprints for KiCad.

## for KiCad 9
- Changed file name and folder structure to KiCad 9 from KiCad 6.
    - file name: bf-021.kicad_pcb  <-  bf-021_pcb.kicad
    - folder structure 1: ./bf-021.kicad_pcb  <-  bf-021/bf-021_pcb.kicad
    - folder structure 2: ./meta/  <-  bf-021/meta/

- Example of KiCad 9
```
C:\Users\ChinoKafu\Documents\KiCad\9.0\template\KiCad-Template-M5Stack>tree /f /a .
フォルダー パスの一覧:  ボリューム OS
ボリューム シリアル番号は 2025-1215 です
C:\USERS\CHINOKAFU\DOCUMENTS\KICAD\9.0\TEMPLATE\KICAD-TEMPLATE-M5STACK
|   bf-021.kicad_pcb
|   bf-021.kicad_prl
|   bf-021.kicad_pro
|   bf-021.kicad_sch
|   bf-021_pcb.pdf
|   bf-021_scm.pdf
|   fp-info-cache
|   LICENSE
|   README.md
|
+---meta
|       icon.png
|       info.html
|       meta.json
|       proto.png
|
+---image
|       bf-021.png
|       core2_mbus500.bmp
|       FKGhLbtaQAIh2uu.png
|       M-BUS500.bmp
|
\---pretty
        BF@M5Stack_MBUS.kicad_mod
        BF@MountingHole_2.2mm_M2.kicad_mod
        BF@MountingHole_3.2mm_M3.kicad_mod
```

- Example of KiCad 6
```
C:\Users\ChinoKafu\Documents\KiCad\6.0\template\KiCad-Template-M5Stack>tree /f /a .
フォルダー パスの一覧:  ボリューム OS
ボリューム シリアル番号は 2025-1215 です
C:\USERS\CHINOKAFU\DOCUMENTS\KICAD\6.0\TEMPLATE\KICAD-TEMPLATE-M5STACK
|   bf-021_pcb.pdf
|   bf-021_scm.pdf
|   LICENSE
|   README.md
|
+---bf-021
|   |   bf-021.kicad_pcb
|   |   bf-021.pro
|   |   bf-021.sch
|   |
|   \---meta
|           icon.png
|           info.html
|           proto.png
|
+---image
|       bf-021.png
|       core2_mbus500.bmp
|       FKGhLbtaQAIh2uu.png
|       M-BUS500.bmp
|
\---pretty
        BF@M5Stack_MBUS.kicad_mod
        BF@MountingHole_2.2mm_M2.kicad_mod
        BF@MountingHole_3.2mm_M3.kicad_mod
```

## for KiCad 6
https://github.com/botanicfields/KiCad6-Environment

## for KiCad 5
- Manufacture with a thickness of 1.0 mm.
- M-BUS pin numbers match pin headers and pin sockets in the KiCad library.
- The template has a notch, but it may be actually needed only for the M5Stack controller board.

<img src="./image/bf-021.png" width=300>

