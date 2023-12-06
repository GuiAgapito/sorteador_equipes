# Sorteador de Equipes

Bem-vindo ao Sorteador de Equipes! Este programa em C permite que você sorteie a ordem das equipes de forma aleatória. Ele utiliza o algoritmo de ordenação quicksort para organizar os números das equipes de forma eficiente.

## Como usar

### Requisitos

Certifique-se de ter um compilador C instalado em seu sistema para executar o programa. Você pode usar o [GCC](https://gcc.gnu.org/) ou qualquer outro compilador C de sua escolha.

### Executando o programa

1. Clone o repositório para o seu sistema local.

```bash
git clone https://github.com/seu-usuario/sorteador-de-equipes.git
cd sorteador-de-equipes
```

2. Compile o programa usando o GCC.

```bash
gcc sorteador.c -o sorteador
```

3. Execute o programa.

```bash
./sorteador
```

## Funcionalidades

1. **Sortear Equipes**: O programa permite que você sorteie a ordem das equipes. Basta escolher a opção 1, digitar a quantidade de equipes desejada e o programa cuidará do resto.

2. **Encerrar o Programa**: Você pode encerrar o programa a qualquer momento escolhendo a opção 2.

## Estrutura do Código

O código é estruturado da seguinte forma:

- **Trocar Valores**: Função `trocar` para trocar os valores apontados por ponteiros.
- **Particionar Matriz**: Função `particionar` para escolher o pivô e rearranjar a matriz usando o algoritmo quicksort.
- **Quicksort**: Função `quickSort` para ordenar a matriz.
- **Sortear Equipes**: Função `sortearEquipes` para sortear os números das equipes e exibir a ordem sorteada.
- **Função Principal**: `main` é a função principal que interage com o usuário, chama as funções necessárias e controla o fluxo do programa.

## Localização

O programa utiliza a biblioteca `locale.h` para garantir a exibição correta de caracteres especiais no idioma português.

## Contribuição

Sinta-se à vontade para contribuir para o aprimoramento deste programa. Se encontrar bugs ou tiver sugestões, abra uma [issue](https://github.com/seu-usuario/sorteador-de-equipes/issues) ou envie uma [pull request](https://github.com/seu-usuario/sorteador-de-equipes/pulls).

Divirta-se sorteando equipes! 🎉
