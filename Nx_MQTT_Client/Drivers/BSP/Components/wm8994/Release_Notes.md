---
pagetitle: Release Notes for WM8994 Component Driver
lang: en
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

::: {.card .fluid}
::: {.sectione .dark}
<center>
# **Release Notes for WM8994 Component Driver**
Copyright &copy; 2016 STMicroelectronics\
    
[![ST logo](_htmresc/st_logo.png)](https://www.st.com){.logo}
</center>
:::
:::

# License

This software component is licensed by ST under BSD 3-Clause license, the "License"; You may not use this component except in 
compliance with the License. You may obtain a copy of the License at:
<center>
[https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)
</center>

# Purpose

This driver provides a set of functions needed to drive WM8994, Audio Codec component

:::

::: {.col-sm-12 .col-lg-8}

# Update History

::: {.collapse}
<input type="checkbox" id="collapse-section10" checked aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">__V3.0.2 / 23-November-2019__</label>
<div>

## Main Changes

-	Update st_logo.png inclusion path in Release notes

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section9" checked aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">__V3.0.1 / 03-July-2019__</label>
<div>

## Main Changes

-	Update license path to BSD-3

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section8" checked aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">__V3.0.0 / 12-April-2019__</label>
<div>

## Main Changes

Official release of component drivers for WM8994 in line with STM32Cube BSP drivers development guidelines (UM2298)

## Backward Compatibility

This version breaks the compatibility with previous versions

## Dependencies

This software release is compatible with BSP Common V6.0.0 or above

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section7" checked aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">__V2.2.1 / 24-January-2018__</label>
<div>			

## Main Changes

-	Fix output device headphone initialization issue

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">__V2.2.0 / 05-June-2017__</label>
<div>			

## Main Changes

-	Add support of ColdStartup sequence for headphone
-	Unmute is performed in a gradual way to minimize pop noise.
-	Update wm8994_SetFrequency to support AUDIO_FREQUENCY_32K
-	Update comments to be used for PDSC generation

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section5" checked aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">__V2.1.0 / 22-February-2016__</label>
<div>			

## Main Changes

__wm8994.c : __

-	Update wm8994_Init() by adding the support of analog microphone connected to INPUT LINE 1
-	INPUT_DEVICE_DIGITAL_MICROPHONE_1 and INPUT_DEVICE_DIGITAL_MIC1_MIC2
-	Add AUDIO_FREQUENCY_32K as possible AudioFreq value

__wm8994.h :__

-	Add INPUT_DEVICE_DIGITAL_MIC1_MIC2 define

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section4" checked aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">__V2.0.0 / 24-June-2015__</label>
<div>			

## Main Changes

__wm8994.h :__

-	Add codec de-initialization function: wm8994_DeInit()
-	Add Audio IO de-initialization function prototype: AUDIO_IO_DeInit()
-	Add INPUT_DEVICE_INPUT_LINE_1 and INPUT_DEVICE_INPUT_LINE_1 support for AUDIO IN
-	Add Input audio volume control support

__wm8994.c :__

-	Update wm8994_Init() function to support the Audio IN
-	Update wm8994_Stop() function to only stop the codec if it was configured
-	Enable VMID_BUF_ENA bit in R57 ANTIPOP register (address 0x39) for all configurations

## Dependencies

This release must be used with BSP Common driver V4.0.0 or later

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section3" checked aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">__V1.0.2 / 12-February-2015__</label>
<div>			

## Main Changes

__wm8994.c: __
   
- Update the wm8994_Init() function to set the volume after enabling the dynamic charge pump power control mode 

</div>
:::


::: {.collapse}
<input type="checkbox" id="collapse-section2" checked aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">__V1.0.1 / 24-June-2015__</label>
<div>			

## Main Changes

__wm8994.h: __
   
-	change "\" by "/" in the include path to fix compilation issue with Linux

</div>
:::


::: {.collapse}
<input type="checkbox" id="collapse-section1" checked aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">__V1.0.0 / 24-June-2015__</label>
<div>			

## Main Changes

-	First official release of **WM8994** audio component drivers

</div>
:::


:::
:::

<footer class="sticky">
For complete documentation on <mark>STM32 Microcontrollers</mark> ,
visit: [[www.st.com](http://www.st.com/STM32)]{style="font-color: blue;"}
</footer>
