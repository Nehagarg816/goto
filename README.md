# goto
use of goto statement in c programming for shifting for printf in desired row and column.
#include<windows.h>
void gotoxy(int x,int y)
{
	COORD c;
	c.X=x;
	c.Y=y;
	SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE),c);
}
void main()
{
	gotoxy(30,15);
	printf("Neha Garg");
}
