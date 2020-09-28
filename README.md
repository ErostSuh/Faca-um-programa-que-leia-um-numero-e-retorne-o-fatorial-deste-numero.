# Faca-um-programa-que-leia-um-numero-e-retorne-o-fatorial-deste-numero.
// Calculando o fatorial de cada numero digitado. #include &lt;stdio.h>  int main(){   int fat, n;   printf("Insira um valor para o qual deseja calcular seu fatorial: ");   scanf("%d", &amp;n);       for(fat = 1; n > 1; n = n - 1)     fat = fat * n;      printf("\nFatorial calculado: %d", fat); return 0; }
