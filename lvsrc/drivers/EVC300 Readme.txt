
FOCUS EVCxxx Instrument Driver Readme

1. Overview

Instrument Driver Technology:  Plug and Play
Supported Language(s):  LabVIEW 2015

Supported Model(s):  
Model(s) Tested:  EVC300, EVC300i, EVC300s
Interface(s):  Serial, Ethernet (in Future)
Required Firmware Revision:  V3.0 or higher
Firmware Revision Tested:  V3.0

Driver Revision:  1.6
Current Revision Date:  09/2016


2. Required Software

Some software components need to be installed before using this instrument driver. The minimum versions of these 
components are listed below.

VISA 15.5
LabVIEW 2015

Note: VISA has additional software requirements. For example, unless you are using a serial interface, NI-VISA
requires that NI-488.2 and/or NI-VXI be installed on your system. Check with VISA help for additional finally
support software and hardware requirements.


3. Installation Instructions

LabVIEW:
Instrument drivers should be installed as a subdirectory of the LabVIEW\instr.lib. The EVCxxx 
instrument driver is installed in the following directory: 

LabVIEW\instr.lib\EVCxxx

Within this directory you can find the menu files and VI libraries that make up an instrument driver. The 
menu files allow you to view the instrument driver VIs from the Functions palette. The VI libraries contain 
the instrument driver VIs.


4. Using the Instrument Driver

LabVIEW:
To verify communication with your instrument and test a typical programmatic instrument operation, you should 
first open the Example VIs the instrument driver. Look over each of the controls and set them appropriately.
Generally, with the exception of the address field, the defaults for most controls will be sufficient for your
first run. You will need to set the instrument resource name appropriately. After running the VI, check to see
that reasonable data was returned and an error was not reported in the error cluster.

After you have verified basic communication with your instrument, you might want to customize instrument 
control for your needs. If your application needs are similar to the Example VI, the simplest means of 
creating a customized VI is to save a copy of the Getting Started or Example VI by selecting Save As 
from the File menu. You can then modify this example to meet your specific needs.

For more details, reference the LabVIEW Help under Help » VI, Function, & How-To Help.


5. Revision History

REV 1.6, 09/2016, LV 2015
- Transfering LV 2015

REV 1.5, 07/2014, LV 2010
- adapt to 2kV EVC
- VIs "EVC Get Version" and "EVC Check Device" extended

REV 1.4, 03/2010, LV 2010
- Transfering LV 2010

REV 1.3, 06/2007, LV 8.2
- Transfering LV 8.2
- VI "EVC GET VERSION" extended

REV 1.2, 01/2006, LV 8.0
- Transfering LV 8.0

REV 1.1, 09/2005, LV 7.1
- Prepare for EVC1200

REV 1.0, 08/2005, LV 7.1
- Original Release



