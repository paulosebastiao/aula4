# aula4
#include <stdio.h>
#include <stdlib.h>
#include<windows.h>

int main()
{
 loop:
    Beep(1000, 500);
    Beep(1000, 500);
    Beep(1000, 1000);
    Sleep(50);
    Beep(1000, 500);
    Beep(1000, 500);
    Beep(1000, 1000);
    Sleep(50);
    Beep(1000, 500);
    Beep(1200, 500);
    Beep(900, 500);
    Beep(950, 500);
    Beep(1000, 1000);
    goto loop;
    return 0;
}
