/*
------------------------------------------------------------
 Project Name : LED Blink using Embedded C
 Microcontroller : AVR (ATmega Series)
 Clock Frequency : 16 MHz
 Author : Your Name
 Description :
    This program blinks an LED connected to PORTB pin 0
    with a delay of 1 second using Embedded C.
------------------------------------------------------------
*/

#define F_CPU 16000000UL      // Define CPU clock frequency as 16 MHz

#include <avr/io.h>           // AVR input/output register definitions
#include <util/delay.h>       // Delay functions library

int main(void)
{
    DDRB = 0x01;              // Set PB0 (PORTB bit 0) as OUTPUT
                               // 1 = Output, 0 = Input

    while (1)                 // Infinite loop
    {
        PORTB = 0x01;         // Turn ON LED (Set PB0 HIGH)
        _delay_ms(1000);      // Wait for 1000 ms (1 second)

        PORTB = 0x00;         // Turn OFF LED (Set PB0 LOW)
        _delay_ms(1000);      // Wait for 1 second
    }
}
