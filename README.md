#include <stdio.h>

int main() {
    // Variáveis da Carta 1
    char estado1[20];
    char codigo1[5];
    char nome_da_cidade1[50];
    int populacao1;
    float area_km1;
    float PIB1;
    int pontos_turisticos1;

    // Variáveis da Carta 2
    char estado2[20];
    char codigo2[5];
    char nome_da_cidade2[50];
    int populacao2;
    float area_km2;
    float PIB2;
    int pontos_turisticos2;

    // Preenchendo os dados da Carta 1
    printf("Preencha os dados da Carta 1\n");

    printf("Digite o estado: ");
    scanf(" %19[^\n]", estado1);

    printf("Digite o código: ");
    scanf(" %4s", codigo1);

    printf("Digite o nome da cidade: ");
    scanf(" %49[^\n]", nome_da_cidade1);

    printf("Digite a população: ");
    scanf("%d", &populacao1);

    printf("Digite a área em km²: ");
    scanf("%f", &area_km1);

    printf("Digite o PIB (em bilhões): ");
    scanf("%f", &PIB1);

    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontos_turisticos1);

    getchar(); // Captura a quebra de linha para evitar problemas na próxima entrada de string

    // Preenchendo os dados da Carta 2
    printf("\nPreencha os dados da Carta 2:\n");

    printf("Digite o estado: ");
    scanf(" %19[^\n]", estado2);

    printf("Digite o código: ");
    scanf(" %4s", codigo2);

    getchar(); // Captura a quebra de linha antes da próxima entrada de string

    printf("Digite o nome da cidade: ");
    scanf(" %49[^\n]", nome_da_cidade2);

    printf("Digite a população: ");
    scanf("%d", &populacao2);

    printf("Digite a área em km²: ");
    scanf("%f", &area_km2);

    printf("Digite o PIB (em bilhões): ");
    scanf("%f", &PIB2);

    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontos_turisticos2);

    // Exibindo as cartas preenchidas
    printf("\n--- Carta 1 ---\n");
    printf("Estado: %s\n", estado1);
    printf("Código: %s\n", codigo1);
    printf("Nome da Cidade: %s\n", nome_da_cidade1);
    printf("População: %d habitantes\n", populacao1);
    printf("Área: %.2f km²\n", area_km1);
    printf("PIB: R$ %.2f bilhões\n", PIB1);
    printf("Número de Pontos Turísticos: %d\n", pontos_turisticos1);

    printf("\n--- Carta 2 ---\n");
    printf("Estado: %s\n", estado2);
    printf("Código: %s\n", codigo2);
    printf("Nome da Cidade: %s\n", nome_da_cidade2);
    printf("População: %d habitantes\n", populacao2);
    printf("Área: %.2f km²\n", area_km2);
    printf("PIB: R$ %.2f bilhões\n", PIB2);
    printf("Número de Pontos Turísticos: %d\n", pontos_turisticos2);

    return 0;
}
