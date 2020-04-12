# mapfile
This is to manage the mapfile for GIS system of mapserver in `Narok Water and Sewerage Services Company`.

All the materials related to this repository were as of September 2016.
And all the Shapefiles under this repository belong to `Narok Water and Sewerage Services Company`.

The main mapfile `narwassco.map` should follow the below structure under main directory.
However, those tiff files of satallite imagery are missing in this repository because file sizes are too huge.
```
├── basemap
│   ├── Narok\ Plots_Cadastrals.dbf
│   ├── Narok\ Plots_Cadastrals.prj
│   ├── Narok\ Plots_Cadastrals.sbn
│   ├── Narok\ Plots_Cadastrals.sbx
│   ├── Narok\ Plots_Cadastrals.shp
│   ├── Narok\ Plots_Cadastrals.shp.xml
│   ├── Narok\ Plots_Cadastrals.shx
│   └── geotiff
│       ├── 20150618_landsat8_kisumu.tif
│       ├── 20150618_landsat8_kisumu.tif.ovr
│       ├── 20151231_landsat8_kapsabet.tif
│       ├── 20151231_landsat8_kapsabet.tif.ovr
│       ├── 20151231_landsat8_narok.tif
│       ├── 20151231_landsat8_narok.tif.ovr
│       ├── airbus
│       │   ├── IMG_PHR1A_PMS_201404100818234_ORT_1659047101-001_R1C1.TIF
│       │   ├── IMG_PHR1A_PMS_201404100818234_ORT_1659047101-001_R1C1.TIF.ovr
│       │   ├── IMG_PHR1A_PMS_201504110803030_ORT_1659046101-001_R1C1.TIF
│       │   ├── IMG_PHR1A_PMS_201504110803030_ORT_1659046101-001_R1C1.TIF.ovr
│       │   ├── IMG_PHR1B_PMS_201401160815464_ORT_1659045101-001_R1C1.TIF
│       │   ├── IMG_PHR1B_PMS_201401160815464_ORT_1659045101-001_R1C1.TIF.ovr
│       │   ├── IMG_PHR1B_PMS_201406280811013_ORT_1659048101-001_R1C1.TIF
│       │   ├── IMG_PHR1B_PMS_201406280811013_ORT_1659048101-001_R1C1.TIF.ovr
│       │   └── airbus_20140104_olopito.tif
│       ├── alpsmlr02_19798n3620f3565b3675_lt_n-ololulunga091012.tif
│       ├── alpsmlr02_26333n3620f3565b3675_lt_n-kilgoris110103.tif
│       ├── alpsmlr02_26508n3620f3565b3675_lt_n-naroktown110115.tif
│       └── digitalglobe
│           ├── 11DEC10082908-S2AS-054996851010_01_P001.TIF
│           └── 11DEC10082908-S2AS-054996851010_01_P001.TIF.ovr
├── fonts
│   ├── ANTQUAB.TTF
│   ├── ANTQUABI.TTF
│   ├── ANTQUAI.TTF
│   ├── ARIALN.TTF
│   ├── ARIALNB.TTF
│   ├── ARIALNBI.TTF
│   ├── ARIALNI.TTF
│   ├── ARIALUNI.TTF
│   ├── BKANT.TTF
│   ├── BOOKOS.TTF
│   ├── BOOKOSB.TTF
│   ├── BOOKOSBI.TTF
│   ├── BOOKOSI.TTF
│   ├── BRADHITC.TTF
│   ├── BSSYM7.TTF
│   ├── CENTURY.TTF
│   ├── CalibriL.ttf
│   ├── CalibriLI.ttf
│   ├── FREESCPT.TTF
│   ├── FRSCRIPT.TTF
│   ├── GADUGI.TTF
│   ├── GADUGIB.TTF
│   ├── GARA.TTF
│   ├── GARABD.TTF
│   ├── GARAIT.TTF
│   ├── GOTHIC.TTF
│   ├── GOTHICB.TTF
│   ├── GOTHICBI.TTF
│   ├── GOTHICI.TTF
│   ├── ITCKRIST.TTF
│   ├── JUICE___.TTF
│   ├── LEELAWAD.TTF
│   ├── LEELAWDB.TTF
│   ├── LHANDW.TTF
│   ├── MISTRAL.TTF
│   ├── MSJH.TTC
│   ├── MSJHBD.TTC
│   ├── MSUIGHUB.TTF
│   ├── MSUIGHUR.TTF
│   ├── MSYH.TTC
│   ├── MSYHBD.TTC
│   ├── MTCORSVA.TTF
│   ├── NIRMALA.TTF
│   ├── NIRMALAB.TTF
│   ├── OUTLOOK.TTF
│   ├── PAPYRUS.TTF
│   ├── PRISTINA.TTF
│   ├── REFSAN.TTF
│   ├── REFSPCL.TTF
│   ├── SEGOEUISL.TTF
│   ├── TEMPSITC.TTF
│   ├── WINGDNG2.TTF
│   └── WINGDNG3.TTF
├── fonts.txt
├── kenyamap
│   ├── County.dbf
│   ├── County.prj
│   ├── County.sbn
│   ├── County.sbx
│   ├── County.shp
│   ├── County.shp.xml
│   └── County.shx
├── narwassco.map
└── symbols.txt
```

`Copyright (c) 2020 Narok Water and Sewerage Services Co., Ltd.`