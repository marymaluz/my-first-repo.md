#include <avr/io.h>
Int main(void)
{
Unsigned char z;
DDRB= 0xFF;
for(z=0;z<=255;z++)
PORTB=z;
return 0;
}
