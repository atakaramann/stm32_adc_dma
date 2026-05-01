## STM32 ADC with DMA & VREFINT Calibration

**Board:** STM32 Nucleo F413ZH  
**IDE:** STM32CubeIDE  
**Library:** HAL  

### What it does
Reads potentiometer voltage via ADC with DMA transfer. Real supply voltage (VDDA) is 
calculated using internal VREFINT calibration for accurate measurements.

### Key concepts
- 12-bit ADC resolution
- DMA circular mode (continuous data transfer to memory)
- Multi-channel ADC scan with DMA buffer
- VREFINT calibration for accurate VDDA measurement
- Conversion complete callback (HAL_ADC_ConvCpltCallback)
