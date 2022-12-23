# SM-W910CN Windows 10용 Device driver 모음

제조사의 공식적인 Windows driver가 지원되지 않아 PC의 Device ID를 참조로 https://driverpack.io/ 에서 Windows 10용 device driver를 찾아서 구성하였습니다.</br>
일부 Device 의 경우 32bit(x86)용 driver가 존재하지 않는 경우도 있습니다.</br>
</br>
윈도우즈를 새로 설치하는 경우 유용하게 사용하시길 바랍니다. (가급적 아래 순서로 설치하시길 바랍니다)
</br></br>

Device ID | Driver folder	| Inf	file | Version |
--|--|--|--|
ACPI\INT33BD|Intel\ATOM\MBI|MBI.inf|09/24/2015,604.10146.2655.6883|
ACPI\INT33F4|Intel\ATOM\PMIC|pmic.inf|04/02/2015,604.10135.1020.62982|
ACPI\808622C1|Intel\ATOM\I2C|iai2ce.inf|10/12/2015,604.10146.2654.7394|
ACPI\808622A8|Intel\SST|isstrtc.inf|01/12/2016,604.10135.2747.11324|
VIDEO\INT22B8|Intel\ATOM\Camera\INT22B8|iacamera32.inf|03/02/2016,21.10586.6069.2007|
PCI\VEN_8086&DEV_22B8|Intel\ATOM\Camera\iaisp32|iaisp32.inf|03/02/2016,21.10586.6069.2007|
ACPI\INT340x|Intel\DPTF|dptf_acpi.inf|01/10/2017,8.2.11003.3588|
ACPI\INT340x|Intel\DPTF|dptf_cpu.inf|01/10/2017,8.2.11003.3588|
ACPI\INT340x|Intel\DPTF|dptf_pch.inf|01/10/2017,8.2.11003.3588|
ACPI\INT340x|Intel\DPTF|esif_manager.inf|01/10/2017,8.2.11003.3588|
ACPI\INT33FF|Intel\ATOM\GPIO|iagpioe.inf|07/15/2015,604.10146.2652.3930|
PCI\VEN_8086&DEV_22B0|Intel\RTM|igdlh.inf|11/04/2020,20.19.15.5171|
ACPI\INT33FE|Intel\ATOM\IntelBatteryManagement|IntelBatteryManagement.inf|06/04/2016,604.10146.2444.27233|
ACPI\INT33D5|Intel\HID|HidEventFilter.inf|09/11/2015, 1.1.0.311|
ACPI\VEN_8086&DEV_228E|Intel\ATOM\SPI|iaspie.inf|06/01/2015,604.10146.2657.947|
PCI\VEN_8086&DEV_2298|Intel\TXEI|TXEI.inf|10/11/2015,2.0.0.1094|
ACPI\8086228A|Intel\ATOM\UART|iauarte.inf|05/21/2015,604.10146.2653.391|
ACPI\10EC5651|Realtek\I2S_10.0.10586.4460|rtii2sac.inf|09/12/2016,10.0.10586.4460|
ACPI\OBDA8723|Realtek\8723_1.0.253.2_uart|rtkuart.inf|06/28/2019,1.0.253.2|
ACPI\OVTI2680|Intel\ATOM\Camera\ov2680|ov2680.inf|09/03/2015,604.10146.2443.6099|
ACPI\BOSC0200|Bosch\Accelerometer|boschaccelerometer.inf|07/06/2015,1.02.00|
ACPI\LTER0303|LITEON\LTR303	LTR303.inf|05/30/2017,8.54.50.545|
ACPI\GDIX1001|Goodix\HID|GoodixTouchDriver.inf|11/07/2015,1.2.2.26|
SD\VID_024C&PID_B723|Realtek\SDIO_3009.0.4.101|netrtwlans.inf|11/01/2018,3009.0.4.101|
