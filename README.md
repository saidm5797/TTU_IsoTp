# TTU_IsoTp

This class has been modified from altelch's iso-tp class.
Found here: https://github.com/altelch/iso-tp

It has been modified to be a derived class of coryjfowler's MCP_CAN class.
Found here: https://github.com/coryjfowler/MCP_CAN_lib

This allows it to be used as a base class for the TTUCAN class.
Found here: https://github.com/saidm5797/TTUCAN

From altelch's repository:
    ISO 15765-2 ISO-TP protocol implementation for Arduino

    This implementation requires MCP_CAN_lib from

    https://github.com/coryjfowler/MCP_CAN_lib with debug output disabled.

    Currently implemented:

    11 bit standard CAN messages
    Send ISO-TP single frame messages
    Send ISO-TP multi frame messages using first and consecutive frames
    Evaluate flow controll and honour minimum separation time + block size during send
    Receive ISO-TP single frame messages
    Receive ISO-TP multi frame messages
    Send flow controll as configured in message (minimum separation time + block size)
    Session timeout
    FC timeout
    CF timeout
    Timeout after too many FC Wait messages
    some error handling
    simple frame padding with 0x00
    See usage example in example/send_receive/send_receive.ino
