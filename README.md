# gaweg#include <conio.h>
#include <iostream.h>

void
main()
{
	int n, dv, ch, tr;
	clrscr();
	cout << "Nhap so nguyen duong < 1000 :\n";
	cin >> n;
	cout << "So " << n << " doi sang so La ma la :\n";
	tr = n / 100;
	n = n % 100;
	ch = n / 10;
	dv = n % 10;

	switch (tr)
	{
		case 1:
			cout << "C";
			break;
		case 2:
			cout << "CC";
			break;
		case 3:
			cout << "CCC";
			break;
		case 4:
			cout << "CD";
			break;
		case 5:
			cout << "D";
			break;
		case 6:
			cout << "DC";
			break;
		case 7:
			cout << "DCC";
			break;
		case 8:
			cout << "DCCC";
			break;
		case 9:
			cout << "CM";
	}

	switch (ch)
	{
		case 1:
			cout << "X";
			break;
		case 2:
			cout << "XX";
			break;
		case 3:
			cout << "XXX";
			break;
		case 4:
			cout << "XL";
			break;
		case 5:
			cout << "L";
			break;
		case 6:
			cout << "LX";
			break;
		case 7:
			cout << "VIII";
			break;
		case 9:
			cout << "IX";
	}
	getch();
}
