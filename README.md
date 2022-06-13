# SDIO_MSC_DMA
## USB sd card reader using STM32f407vet6 dev board.
## Notes:
- SDIO clock using APB2 clock bus.
- NVIC DMA interrupts priority should be less then SDIO interrupt priority.
- SDIO in polling mode using maximum clock speed about 5 MHz.
- SDIO in DMA mode using maximum clock speed about 24 MHz.
## Changed files:
- Core/main.c
- USB_DEVICE/App/usbd_storage_if.c
