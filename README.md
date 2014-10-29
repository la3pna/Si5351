Si5351
======

Si5351 things

Cadsoft eagle shematics and board layout for the Si5351A backpack. 

Load ATmega32U4 with Arduino bootloader to upload via USB. 

Boards avaible at https://oshpark.com/shared_projects/kJa9OECr

Mounting tips:
The LCD is supposed to go on the microcontroller side. mount the large components like SMB connectors, crystal (if hole mounted) and pot on the backside of the board.

Arduino pinout:

D0    ENCODER A (Interrupt)

D1    ENCODER b (Interrupt)

D2    I2C SDA to Si5351A

D3    I2C SCI to Si5351A

D4    Extra

D5    Extra

D6    LCD D7

D7    ENCODER SWITCH (Interrupt)

D8    LCD D6

D9    LCD D5

D10   LCD D4

D11   LCD Enable

D12   LCD RS

D13   External LED

None of the analog pins are connected.


