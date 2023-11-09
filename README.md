# Labirinto em Java com Pilha, Fila, Coordenadas e Orientação a Objetos

## Clonando o Projeto

Para começar, clone o projeto em sua máquina:

```bash
git clone URL
cd nome-do-projeto
```

Preparando o Labirinto
Após clonar o projeto, crie um arquivo TXT representando o labirinto. O formato deve seguir as seguintes diretrizes:



1) primeira linha representa a quantidade de linhas do labirinto.
2) A segunda linha representa a quantidade de colunas do labirinto.
3) O restante do arquivo deve seguir as especificações abaixo:
4) #: Parede do labirinto.
5) Espaço em branco: Caminho livre.
6) E: Entrada do labirinto.
7) S: Saída do labirinto.


Exemplo de um labirinto simples:

```bash
5
5
#####
E   #
#   #
# S #
#####


```
Executando o Programa
Antes de rodar o programa, certifique-se de ter o arquivo TXT preparado. Em seguida, execute o programa, passando o caminho completo do arquivo como no terminal:
```bash
rode a main
path/arquivo.txt
```


Resultados
O programa retornará as coordenadas da entrada do labirinto até a saída. Se houver alguma inconsistência, como falta de parede, quantidade incorreta de linhas ou colunas, falta de entrada ou saída, ou se não houver solução, uma mensagem de erro será exibida, detalhando o problema encontrado no arquivo.

Certifique-se de corrigir a formatação do arquivo TXT com base nas instruções fornecidas na mensagem de erro.
