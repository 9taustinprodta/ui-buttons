## How to use SNIM\_RW\_V1.0.4 to write AT commands on MTK devices

  
# How to use SNIM\_RW\_V1.0.4 to write AT commands on MTK devices
 
SNIM\_RW\_V1.0.4 is a tool that allows you to write AT commands on MTK devices using a USB cable[^4^]. AT commands are instructions that you can use to control the modem or phone functions of your device, such as sending SMS, making calls, changing network settings, etc.
 
## Snim Rw V1.0.4 Setup Rar.epub


[**Download File**](https://www.google.com/url?q=https%3A%2F%2Furllie.com%2F2tKGA3&sa=D&sntz=1&usg=AOvVaw2CaRKxPOpK4dgQ3taMRb44)

 
In this article, I will show you how to use SNIM\_RW\_V1.0.4 to write AT commands on MTK devices step by step. You will need the following things:
 
- A Windows PC with SNIM\_RW\_V1.0.4\_setup installed[^4^]. You can download it from [here](https://support.halabtech.com/index.php?a=downloads&b=folder&id=42330).
- A USB cable that can connect your MTK device to your PC.
- A MTK device that supports AT commands. You can check the compatibility of your device by running SNIM\_RW.exe and clicking on the "Scan" button.

Once you have everything ready, follow these steps:

1. Run SNIM\_RW.exe as administrator and click on the "Scan" button. The tool will detect your MTK device and show its information on the screen.
2. Select the COM port that corresponds to your device from the drop-down menu.
3. Type the AT command that you want to write in the text box below the COM port selection. For example, if you want to check the IMEI of your device, type "AT+CGSN" and press enter.
4. The tool will send the AT command to your device and display the response on the screen. You can see if the command was successful or not by checking the status bar at the bottom of the tool.
5. You can repeat steps 3 and 4 for any other AT commands that you want to write on your device.

That's it! You have successfully used SNIM\_RW\_V1.0.4 to write AT commands on your MTK device. You can use this tool for various purposes, such as unlocking, repairing, flashing, etc. However, be careful when using AT commands, as some of them may cause irreversible damage to your device if used incorrectly.
 
If you have any questions or feedback about this article, please leave a comment below or contact me at jimmy@buffering.com.
  
In this section, I will show you some examples of AT commands that you can use with SNIM\_RW\_V1.0.4 and their functions. Note that these commands may vary depending on your device model and firmware version, so always check the manual or online resources before using them.
 
## Some useful AT commands for MTK devices

| AT command | Function |
| --- | --- |

| AT+CGSN | Displays the IMEI of the device. |

| AT+CFUN=0 | Sets the device to minimum functionality mode, which turns off the radio and reduces power consumption. |

| AT+CFUN=1 | Sets the device to full functionality mode, which turns on the radio and enables normal operation. |

| AT+COPS? | Displays the current network operator name and mode. |

| AT+COPS=? | Searches for available network operators and displays their names and modes. |

| AT+COPS=0 | Sets the device to automatic network selection mode, which allows the device to choose the best network operator available. |

| AT+COPS=1,x,y | Sets the device to manual network selection mode, which allows the user to specify the network operator by its numeric code (x) and access technology (y). For example, AT+COPS=1,310,2 selects AT&T as the network operator and GSM as the access technology. |

| AT+CMGF=0 | Sets the SMS message format to PDU mode, which allows sending and receiving binary data. |

| AT+CMGF=1 | Sets the SMS message format to text mode, which allows sending and receiving plain text. |

| AT+CMGS="number" | Sends an SMS message to the specified number. The message text should be entered after the command and terminated with Ctrl+Z. |

| AT+CMGL="status" | Lists all SMS messages in the device memory with the specified status. The status can be "REC UNREAD", "REC READ", "STO UNSENT", or "STO SENT". For example, AT+CMGL="REC UNREAD" lists all unread messages in the device memory. |

| AT+CMGR=index | Reads an SMS message from the device memory at the specified index. The index can be obtained from the AT+CMGL command. |

| AT+CMGD=index | Deletes an SMS message from the device memory at the specified index. The index can be obtained from the AT+CMGL command. |

| ATDnumber; | Makes a voice call to the specified number. The semicolon at the end indicates a voice call. For example, ATD1234567890; makes a voice call to 1234567890. |

| ATA | Answers an incoming voice call. |

| ATH | Hangs up a voice call. |

| AT+CLCC | Lists all current voice calls and their statuses. |

| AT+CHLD=x | Performs call-related supplementary services according to the value of x. For example, AT+CHLD=0 releases all held calls or sets User Determined User Busy (UDUB) for a waiting call; AT+CHLD=1 releases all active calls (if any exist) and accepts the other (held or waiting) call; AT+CHLD=2 places all active calls (if any exist) on hold and accepts the other (held or waiting) call; AT+CHLD=3 adds a held call to the conversation; AT+CHLD=4 connects two calls and disconnects from both calls (Explicit Call Transfer). |

I hope you found this article helpful and learned something new about SNIM
 0f148eb4a0
