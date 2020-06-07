


SPRINT3

User story (1):
Use an existing RTOS project to write a simple program with the following requirements:
AGILE_REQ1:
< 4 Tasks, A, B, C, D >
AGILE_REQ2:
< Task A responsible for outputting incoming data to LCD >
AGILE_REQ3:
< Task B monitors Keypad and sends readings to LCD >
AGILE_REQ4:
< Task C sends any received data on UART to LCD >
AGILE_REQ5:
< Task D sends push button state to LCD >
AGILE_REQ6:
< LCD shall display any Keypad readings on row 1, And shall display any new data from UART on row 2 >
AGILE_REQ7:
< If push button is pressed once LCD is cleared >
User story (2) - Final Project:
Use an existing RTOS project to write a chatting application between two micro-controllers  with the following requirements:
AGILE_REQ1:
< The two micro-controllers shall communicate over a UART channel (9600 bps) full duplex >
AGILE_REQ2:
< Each micro-controller will contain 1 keypad, 2 LEDs, 1 LCD, and 1 push button >
AGILE_REQ3:
< LCD shall display the received message in the lower row. The received message will be displayed when received for two seconds and then cleared >
AGILE_REQ4:
< LCD shall display the sender input from keypad in the upper row. When sender press the push button the message displayed in the upper row is sent to the other micro-controller through UART channel and the message is cleared from the sender LCD >
AGILE_REQ5:
< LED 1 is turned ON for 500ms when a new message is received >
AGILE_REQ6:
< LED 2 is turned ON for 200ms when a new message is sent >
