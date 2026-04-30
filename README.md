## STM32 ADC with DMA & VREFINT Calibration

**Board:** STM32 Nucleo F413ZH  
**IDE:** STM32CubeIDE  
**Library:** HAL  

### What it does
Reads potentiometer voltage and internal temperature sensor
via ADC with DMA transfer. Real supply voltage (VDDA) is 
calculated using internal VREFINT calibration for accurate measurements.

### Key concepts
- 12-bit ADC resolution
- DMA transfer mode (non-blocking)
- VREFINT calibration for accurate VDDA measurement
- Internal temperature sensor reading
- Conversion complete callback (HAL_ADC_ConvCpltCallback)
