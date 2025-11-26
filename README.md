# Devboard
A custom RP2040 devboard.

<img width="334" height="429" alt="Screenshot 2025-11-25 at 10 13 17 PM" src="https://github.com/user-attachments/assets/9827f567-a1d0-4dc4-8468-fa2f963384b9" />
<img width="334" height="429" alt="Screenshot 2025-11-25 at 10 13 34 PM" src="https://github.com/user-attachments/assets/6fd31bb4-f7b2-4cec-a213-1db88a2e4f15" />

## Schematic:
<img width="1232" height="844" alt="Screenshot 2025-11-25 at 10 15 26 PM" src="https://github.com/user-attachments/assets/42f030c7-f980-44f6-a529-40617eb09b31" />

## PCB:
<img width="334" height="742" alt="Screenshot 2025-11-25 at 10 14 38 PM" src="https://github.com/user-attachments/assets/16ad272e-eda6-4f6f-99fe-0c83ebce1354" />

## BOM:
| Reference                     | Qty | Value                      | DNP | Exclude from BOM | Exclude from Board | Footprint                                        | Datasheet                                                                                     |
|-------------------------------|-----|----------------------------|-----|------------------|-------------------|-------------------------------------------------|------------------------------------------------------------------------------------------------|
| C1,C10                        | 2   | 1uF                        |     |                  |                   | Capacitor_SMD:C_0402_1005Metric                  | ~                                                                                              |
| C2,C3,C4,C5,C6,C7,C8,C9,C11,C12,C17 | 11  | 0.1uF                      |     |                  |                   | Capacitor_SMD:C_0402_1005Metric                  | ~                                                                                              |
| C13,C14                      | 2   | 10uF                       |     |                  |                   | Capacitor_SMD:C_0603_1608Metric                  | ~                                                                                              |
| C15,C16                      | 2   | 33pF                       |     |                  |                   | Capacitor_SMD:C_0402_1005Metric                  | ~                                                                                              |
| J1                            | 1   | USB_C_Receptacle_USB2.0_14P |     |                  |                   | Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12 | https://www.usb.org/sites/default/files/documents/usb_type-c.zip                               |
| J2,J3                        | 2   | Conn_01x20                 |     |                  |                   | Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical | ~                                                                                              |
| J4                            | 1   | Conn_01x03                 |     |                  |                   | Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical | ~                                                                                              |
| R1,R2                        | 2   | 5.1K                       |     |                  |                   | Resistor_SMD:R_0402_1005Metric                   | ~                                                                                              |
| R3,R4                        | 2   | 27                         |     |                  |                   | Resistor_SMD:R_0402_1005Metric                   | ~                                                                                              |
| R5,R7                        | 2   | 1K                         |     |                  |                   | Resistor_SMD:R_0402_1005Metric                   | ~                                                                                              |
| R6                            | 1   | 10K                        |     |                  |                   | Resistor_SMD:R_0402_1005Metric                   | ~                                                                                              |
| SW1                           | 1   | SW_Push                    |     |                  |                   | Button_Switch_SMD:SW_Push_SPST_NO_Alps_SKRK     | ~                                                                                              |
| U1                            | 1   | RP2040                     |     |                  |                   | Package_DFN_QFN:QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm | https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf                                |
| U2                            | 1   | NCP1117-3.3_SOT223         |     |                  |                   | Package_TO_SOT_SMD:SOT-223-3_TabPin2             | http://www.onsemi.com/pub_link/Collateral/NCP1117-D.PDF                                        |
| U3                            | 1   | W25Q16JVZPIQ TR            |     |                  |                   | Package_SON:Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm | https://www.winbond.com/resource-files/w25q128jv_dtr%20revc%2003272018%20plus.pdf              |
| Y1                            | 1   | 12 MHz                     |     |                  |                   | Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm          | ~                                                                                              |
