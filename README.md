#include <stdio.h>

int main (void) {

    // Variáveis para armazenar a distância da viagem e o preço do combustível
    float distancia, preco;

    // Solicita ao usuário a distância da viagem e o preco do combustivel
    printf("Digite a distancia da viagem em km: ");
    scanf("%f", &distancia);
    printf("Digite o preco do combustivel por litro: R$ ");
    scanf("%f", &preco);

    // Considerando que o carro faz 10 km por litro, calcula o gasto total da viagem
    float gasto_total = (distancia / 10) * preco;
    // Exibe o resultado para o usuário
    printf("O gasto total da viagem sera: R$ %.2f\n", gasto_total);
    
    return 0;

}
