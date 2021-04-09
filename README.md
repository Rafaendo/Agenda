# Agenda
Atividade de Agenda do Alexandre (Algoritmos II - Estrutura De Dados)
Aluno: Rafael Rodrigues Ramos 
3ª Período

Código:
#include <stdio.h>
#include <string.h>

#define TAM_AGENDA 2

typedef struct Pessoa
{
    int codigo;
    char nome[100];
    char telefone[20];
    char email[50];
    char dataNascimento[10];
    char observacoes[100];
} Pessoa;

int main(void)
{

  Pessoa contatos[10];
  int i, buscaroCodigo;

  //Cadastrar
  for(i = 0; i < TAM_AGENDA; i++){

    printf("Digite o código: ");
    scanf("%i", &contatos[i].codigo);

    printf("Digite o nome: ");
    scanf("%s", contatos[i].nome);

  }

  //Listar
  for(i = 0; i < TAM_AGENDA; i++){

    printf("Código: ");
    printf("%i\n", contatos[i].codigo);

    printf("Nome: ");
    printf("%s\n", contatos[i].nome);

  }

  //Buscar
  printf("Digite o número do código que deseja buscar: ");
  scanf("%i", &buscaroCodigo);
  for(i = 0; i < TAM_AGENDA; i++){
    
    if(buscaroCodigo == contatos[i].codigo){
      printf("Código: ");
      printf("%i\n", contatos[i].codigo);

      printf("Nome: ");
      printf("%s\n", contatos[i].nome);
}
 else
{
printf("Não Encontrado");
}
}
  return 0;
}
#include <stdio.h>
#include <string.h>

#define TAM_AGENDA 2

typedef struct Pessoa
{
    int codigo;
    char nome[100];
    char telefone[20];
    char email[50];
    char dataNascimento[10];
    char observacoes[100];
} Pessoa;

int main(void)
{

  Pessoa contatos[10];
  int i, buscaroCodigo;

  //Cadastrar
  for(i = 0; i < TAM_AGENDA; i++){

    printf("Digite o código: ");
    scanf("%i", &contatos[i].codigo);

    printf("Digite o nome: ");
    scanf("%s", contatos[i].nome);

  }

  //Listar
  for(i = 0; i < TAM_AGENDA; i++){

    printf("Código: ");
    printf("%i\n", contatos[i].codigo);

    printf("Nome: ");
    printf("%s\n", contatos[i].nome);

  }

  //Buscar
  printf("Digite o número do código que deseja buscar: ");
  scanf("%i", &buscaroCodigo);
  for(i = 0; i < TAM_AGENDA; i++){
    
    if(buscaroCodigo == contatos[i].codigo){
      printf("Código: ");
      printf("%i\n", contatos[i].codigo);

      printf("Nome: ");
      printf("%s\n", contatos[i].nome);
}
 else
{
printf("Não Encontrado");
}
}
  return 0;
}

