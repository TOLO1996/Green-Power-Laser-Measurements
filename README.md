## Introduction
For many of my projects, I use laser diodes available on Chinese auction sites with manufacturer-rated optical powers of 100 mW and 200 mW. Unfortunately,
these diodes lack datasheets. I decided to measure their parameters—specifically forward voltage, current, and both electrical and optical power at a relatively constant temperature—as,
well as the effect of temperature on optical power and the temperature profile over time at maximum power.
## Diode parameters
<img width="800" height="646" alt="image" src="https://github.com/user-attachments/assets/bf12116d-1485-4205-b7be-cbe62ddd4353" />

The descriptions for both the 100mW and 200mW versions are very sparse:
Green laser with a wavelength of 532nm
Dimensions: 12×35mm
Dot-shaped output – the beam forms a dot, allowing for precise point marking on stage. Ideal for lighting effects and visual presentations.
Dimensions:

<img width="489" height="313" alt="image" src="https://github.com/user-attachments/assets/5a67e3ee-be71-41c4-850e-5f752388fafd" />

The dimensions for the 100mW and 200mW versions are identical.

## Temperature measurement
I set the output power to 100 mW and 200 mW, respectively, using a potentiometer connected to the CN5711 driver, and then measured the time, 
temperature, and optical power of the given diode. The test setup is shown below.

<img width="489" height="313" alt="image" src="Setup_temp.png" />

## Results
Full results can be found in the attached odt file. Charts below:
## 100mW Version

<img width="489" height="313" alt="image" src="Optical_Power_vs_temperature_100mW.png" />
<img width="489" height="313" alt="image" src="Temperature_vs_time_100mW.png" />

## 200mW Version

<img width="489" height="313" alt="image" src="Optical_Power_vs_temperature_200mW.png" />
<img width="489" height="313" alt="image" src="Temperature_vs_time_200mW.png" />

## Results description


It is evident that the optical output power depends heavily on temperature. A 10-degree rise causes a power drop of nearly 50%. Since both diode versions share the same housing, this issue is particularly pronounced in the 200 mW version, where a 50% power drop occurred after just 80 seconds of continuous operation, compared to 240 seconds for the 100 mW version (although the latter experienced a 40% drop). This highlights the need for temperature stabilization. Consequently, for subsequent measurements, I used an additional fan to maintain a relatively constant temperature of 25°C.
