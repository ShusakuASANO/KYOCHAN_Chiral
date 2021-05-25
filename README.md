# KYOCHAN_Chiral
KYOCHAN_Chiral is a standalone software for an automated analysis of stereochemical stability of dynamic chiral molecules using microflow setup. Its details and benefits are described in a publication DOI:xxxxxxxx. The newest version is 3.0, released in May, 2021.
The standalone executable file is provided here. Windows 10 PC is recommended. You may require internet connection to install runtime engines (NI).

**Files**

KYHOCHAN3.0_Chiral.zip: Executable application file and data folder. Do not change data folder directry.

demo_spreadsheet: Example of the spreadsheet file that can be read and executed from KYOCHAN.

spreadsheet_template.xlsx: Template excel file to make spreadsheet. You can fill in the excel table and copy them to the blank txt file to make spreadsheet that can be read from KYOCHAN.

**Hardware requirement**

Syringe pump: Many models of the syringe pumps are supported in KYOCHAN_Chiral. It should have a USB or RS-232 connection port. Pump11 Elite or PHD ULTRA(Harvard Apparatus) is recommended.

Temperature sensor: TC-01 (NI) is supported.

Digital output device: USB-DAQ and Compact DAQ (NI) modules are supported.

6 port valve: Valves controlled by digital input or relay contact can be used. These valves are provided from JASCO, VICI, Shimadzu, and so on. VA-21 series valve (FLOM) works with specific contact but supported exceptionally. 

HPLC system: Any models of HPLC system which have start signal input can be used.


**Warning**

KYOCHAN3.0_Chiral enables accurate temperature control with simple heating device however, it does not provide safety function to prevent fire accidents. The author does not take any responsibility on the accident during the operation.



**Note**
KYOCHAN_Chiral has limited functions of KYOCHAN platform, which covers broad range of lab automation and intelligent flow chemistry. If you have interest in applications not described in DOI:xxxxxxxx, please contact to the corresponding author.
