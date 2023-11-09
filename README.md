# Labirinto em Java com Pilha, Fila, Coordenadas e Orientação a Objetos

## Clonando o Projeto

Para começar, clone o projeto em sua máquina:

```bash
git clone https://github.com/seu-usuario/nome-do-projeto.git
cd nome-do-projeto
```

Preparando o Labirinto
Após clonar o projeto, crie um arquivo TXT representando o labirinto. O formato deve seguir as seguintes diretrizes:

A primeira linha representa a quantidade de linhas do labirinto.
A segunda linha representa a quantidade de colunas do labirinto.
O restante do arquivo deve seguir as especificações abaixo:
#: Parede do labirinto.
Espaço em branco: Caminho livre.
E: Entrada do labirinto.
S: Saída do labirinto.


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
Antes de rodar o programa, certifique-se de ter o arquivo TXT preparado. Em seguida, execute o programa, passando o caminho completo do arquivo como argumento:
```bash
java -jar NomeDoProjeto.jar /caminho/do/arquivo.txt
```


Resultados
O programa retornará as coordenadas da entrada do labirinto até a saída. Se houver alguma inconsistência, como falta de parede, quantidade incorreta de linhas ou colunas, falta de entrada ou saída, ou se não houver solução, uma mensagem de erro será exibida, detalhando o problema encontrado no arquivo.

Certifique-se de corrigir a formatação do arquivo TXT com base nas instruções fornecidas na mensagem de erro.
