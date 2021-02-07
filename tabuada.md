#include <iostream>



int main(int argc, char** argv) {
	
	int n,numero;


​	
	printf("Qual tabuada deseja consultar? \n");
	scanf("%d", &n);
	numero=1;
	while (numero <= 10) {
		
		printf("%d x %d = %d\n ", n,numero,n*numero);
		numero++;
	}
	
	return 0;
}