# AltiumDesignerLibrary

## Connector Library

### USB Family

- Micro/Mini USB 2.0 Type A/AB
- Micro USB 3.0
- USB 2.0 Type A/B
- USB 3.0 Type A
- USB 3.1 Type A/C
- ...

### Memory Card Family

- SD Card
- Micro SD Card
- ...

### Other

- Pitch 2.54mm Header series
- pieces of  KF128, KF301 series
- FPC, FFC (not modified)
- ...

## Comment Library

- 常用元器件（电阻、电容、电感、Led、三极管等）
- 数字芯片
  - STM32F103 C8T6/RCT6
  - STM32F407 Z/V
  - XC6SLX9-2TQG144
  - XC6LX45-2FGG484
  - 74HC138
  - 74HC595
- 数据转换
  - ADC
    - ADS1255/1271/1274
  - DAC
- 电源芯片
  - 线性电源
    - 正压
      - TPS7A470x
      - TPS734xx
      - LT3042
      - AMS1117
      - ...
    - 负压
      - TPS7A3301
      - TPS7A3001
      - TPS7A3401
      - ...
  - 开关电源
  - 电压基准
    - ADR45xx
    - REF30xx
    - REF31xx
- 放大器
  - 高速放大器
    - OPA690/693/695
    - OPA847
    - AD8009
    - AD8099
    - ...
  - 全差分放大器
    - THS4521
    - ADA4927/4930/4939 -1
  - 可变增益放大器
    - LMH6518
    - AD8367
    - ...
  - TODO: 仪表放大器
- RF
  - 通用增益模块
  - SPF5043Z
  - PE4302
  - DAT-31R5
  - PSA4-5043

## Folder

```./AD_Connectors``` Altium Designer Connectors Library Project file.

```./AD_Connectors/3D``` Connectors' 3D file in **.step** format.

```./AD_Connectors/Datasheet``` Connectors' datasheet file in **.step** format.

```./AD_Comments``` Altium Designer Comments Library Project file.

```./AD_Comments/3D``` Comments' 3D file in **.step** format.

```./Output``` Output file, you can find **.IntLib** file here.

## Layer Settings

```Mechanical 1```  勾画线路板的边框，以及内部较大的镂空或者异型镗孔。

```Mechanical 13``` 绘制三维实体。

```Mechanical 15``` 勾绘器件的占位尺寸。
