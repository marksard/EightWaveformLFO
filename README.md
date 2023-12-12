# Eight Waveform LFO

Eight Waveform LFO for Eurorack

## Specification

### Power

|Use Voltage|Current consumption|
|:--|:--|
|+12V|18mA|
|-12V|18mA|

### Input

|Name|Description|
|:--|:--|
|Sync|-|
|Adjust In|BIPOLER to UNIPOLER<br>and ATTENUATOR|

### Output

|Name|Description|
|:--|:--|
|SQU/PULSE|SQUARE or PULSE<br> BIPOLER 10.5Vpp|
|TRI/SAW|TRIANGLE or DOWN/UP SAW<br> BIPOLER 10Vpp|
|SINE/S.SAW| SINE AND Cos/Tan Curve<br>BIPOLER 10Vpp|
|Adjust Out|-|

### Controller

|Name|Description|
|:--|:--|
|Freq Pot|Frequency|
|Shape Pot|Wave shape|
|Range|LOW:28Sec ~ 10Hz<br>HIGH:8Hz ~ 2kHz|
|Gain|Attenuator for Adjust In|
|Offset|DC Offset for Adjust In|

## Image

## Schematic

![img](_data/EightWaveformLFO_rev1.0.0.png)

## Waveform

Square
![img](_data/ewlfo_wave_squ.png)  

Triangle
![img](_data/ewlfo_wave_tri.png)  

Sine
![img](_data/ewlfo_wave_sin.png)  

Pulse
![img](_data/ewlfo_wave_pulse1.png)  
![img](_data/ewlfo_wave_pulse2.png)  

Saw
![img](_data/ewlfo_wave_saw_down.png)  
![img](_data/ewlfo_wave_saw_up.png)  

Sine
![img](_data/ewlfo_wave_sin_down.png)  
![img](_data/ewlfo_wave_sin_up.png)  

Sync
![img](_data/ewlfo_wave_sync.png)  
