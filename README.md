# Linux-i2c-i801
modify i2c-i801 driver

## I2C-i802 device list

|Platfrom | PCH(codename) | Definition | Device ID | Kernel |
|---------|------------------|------------|-----------|-----|
|Haswell-EP| C61x (Wellsburg) | PCI_DEVICE_ID_INTEL_WELLSBURG_SMBUS | 0x8d22 | 3.15 |
| | |PCI_DEVICE_ID_INTEL_WELLSBURG_SMBUS_MS0 | 0x8d7d | 3.15 |
| | |PCI_DEVICE_ID_INTEL_WELLSBURG_SMBUS_MS1 | 0x8d7e | 3.15 |
| | |PCI_DEVICE_ID_INTEL_WELLSBURG_SMBUS_MS2 | 0x8d7f | 3.15 |
|Skylake| 100 Series and C23x Series (Sunrise point-H) |  PCI_DEVICE_ID_INTEL_SUNRISEPOINT_H_SMBUS | 0xa123 | 3.18 |
|Skylake-EP| C62X Series(Lewisburg) | PCI_DEVICE_ID_INTEL_LEWISBURG_SMBUS| 0xa1a3 | 4.4 |
|Kabylake| 200 Series (Union Point) | PCI_DEVICE_ID_INTEL_KABYLAKE_PCH_H_SMBUS | 0xa2a3 | 4.9 |
|Coffeelake| 300 Series and C24x Series (Cannon lake)|PCI_DEVICE_ID_INTEL_CANNONLAKE_H_SMBUS | 0xa323 | 4.13 |





## References
[CONFIG_I2C_I801](https://cateee.net/lkddb/web-lkddb/I2C_I801.html)

[Itnel Platform Controller Hub](https://en.wikipedia.org/wiki/Platform_Controller_Hub)
