# EFI

## 配置
```
CPU I7-8700K
主板 MSI Z370 Gaming Plus
内存 金士顿 DDR4 2400 16G
显卡 华硕 RX580 8G
SMBIOS 19.1
OpenCore 0.6.3
```

### Changes
```
DevirtualiseMmio --> false
SetupVirtualMap  --> false
ExtendBTFeatureFlags --> true
DmgLoading --> any 
boot-args --> agdpmod=pikera -v debug=0x108 keepsyms=1
prev-lang:kbd --> ZW4tVVM6MA== 
ProcessorType --> 4105


<key>PlatformNVRAM</key>
<dict>
    <key>BID</key>
    <string>Mac-AA95B1DDAB278B95</string>
    <key>FirmwareFeatures</key>
    <data>dvWP/QAAAAA=</data>
    <key>FirmwareFeaturesMask</key>
    <data>f//f/wAAAAA=</data>
    <key>MLB</key>
    <string>C02912306CDLNV9FB</string>
    <key>ROM</key>
    <data>axCELPVu</data>
</dict>

AudioSupport --> true

ConsoleMode --> Max

DirectGopRendering --> true
ReplaceTabWithSpace --> true 

````

