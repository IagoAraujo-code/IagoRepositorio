# IagoRepositorio

#include <iostream>

int main()
{
	int i;
	
	do {
		printf("\n Digite o numero do sabor \n");
		printf("\t (1) FLOCOS \n");
		printf("\t (2) MORANGO \n");
		printf("\t (3) ABACAXI \n");

		scanf_s("%d", &i);
	} while ((i < 1) || (i > 3));
	switch (i) {
	case 1: printf("\t\t VOCE ESCOLHEU FLOCOS");
		break;

	case 2: printf("\t\t VOCE ESCOLHEU MORANGO");
		break;

	case 3: printf("\t\t VOCE ESCOLHEU ABACAXI");
		break;
	}
}
