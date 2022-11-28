# 22.-odev

//recursive fakt�riyel fonksiyonu

#include<stdio.h>

int faktoriyel(int);

int main(void)
{
	int sayi=4;
	int sonuc=faktoriyel(sayi);
	printf("%d! = %d \n" ,sayi,sonuc);
	return 0;
}

int faktoriyel(int x)
{
	if(x<=1)
	return 1;
	
	return x*faktoriyel(x-1);
}
