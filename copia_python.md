# Instruções Iniciais
Este repositorio esta configurado para armazenar um livro em Jupyter notebook a fim de explicar claramente o uso de Python do inicio ao fim no que compreende o total do conhecimento do autor, na atual versão temos apenas 2 arquivos:
- Python_book.ipynb, O arquivo que esta lendo no momento.
- Atividades.ipynb, Uma coleção de atividades compiladas da internet e respondidas, como uma biblioteca de usos de codigo que vai do mais simples ao mais facil, a edição atual compreende as atividades do Curso em Video Python Mundo 1 do Gustavo Guanabara.
- Respostas.ipynb, arquivo onde constam todas as respostas das atividades para caso haja duvidas.
# Funcoes e Modulos
Uma função em Python é um bloco de código nomeado que realiza uma tarefa específica. Ela pode receber argumentos (dados de entrada), processá-los e retornar um valor (dados de saída). As funções ajudam a modularizar o código, tornando-o mais legível, reutilizável e organizado.
Em Python, existem três tipos principais de funções:

- Funções Integradas (Built-in Functions): São funções que já vêm embutidas na linguagem e podem ser usadas diretamente sem a necessidade de importar módulos adicionais. Algumas funções integradas comuns incluem print(), len(), type(), int(), str(), entre outras. Elas fornecem funcionalidades básicas e essenciais para a programação em Python.

- Funções Definidas pelo Usuário: São funções que você mesmo cria para realizar tarefas específicas. Você pode definir suas próprias funções usando a palavra-chave def e dar um nome significativo à função. As funções definidas pelo usuário podem receber argumentos, executar um bloco de código e retornar valores.

- Funções de Bibliotecas (Library Functions): Essas são funções que não fazem parte do núcleo da linguagem, mas estão disponíveis em bibliotecas (módulos) específicas. Para usar essas funções, você precisa importar o módulo relevante. Exemplos incluem as funções matemáticas do módulo math, as funções de manipulação de arquivos do módulo os, etc.
Além desses três tipos principais, algumas funções têm propriedades especiais:

- Funções Anônimas (Lambda Functions): São funções pequenas e sem nome que podem ser usadas para operações simples. Elas são definidas usando a palavra-chave lambda.

- Funções Recursivas: São funções que chamam a si mesmas em seu próprio processo. São úteis para resolver problemas que podem ser divididos em subproblemas semelhantes.

- Funções Geradoras (Generator Functions): São funções especiais que retornam um gerador, permitindo a criação de sequências de valores sob demanda, economizando memória.

Cada tipo de função tem seu próprio propósito e uso. As funções integradas e as funções de bibliotecas fornecem uma ampla gama de funcionalidades prontas para uso, enquanto as funções definidas pelo usuário permitem que você crie código personalizado e modular para atender às suas necessidades específicas.
# Variaveis
- Variáveis em Python são usadas para armazenar valores. Elas são declaradas com um nome e podem conter diferentes tipos de dados, como números, strings e objetos. Atribuímos valores às variáveis usando o sinal de igual (=).
# Built-in Functions/Funções Embutidas
As funções embutidas, também conhecidas como funções integradas ou built-in functions, são funções pré-definidas na linguagem de programação Python. Elas fazem parte do próprio Python e estão disponíveis para uso imediato, sem a necessidade de importar módulos adicionais. Essas funções são componentes essenciais da linguagem e oferecem funcionalidades básicas que são amplamente utilizadas em tarefas de programação comuns.
## Funcoes Build in - Variaveis 1
### print()
A função print() é usada para exibir informações na saída padrão, que normalmente é o console onde você está executando o código. Ela aceita um ou mais argumentos separados por vírgulas e os exibe como texto na saída.
É possivel utilizar tambem o /n para adicionar quebras ao print, por exemplo
### input()
A função input() é usada para obter entradas do usuário. Ela exibe uma mensagem (prompt) na tela e espera que o usuário digite algo. Quando o usuário pressiona a tecla "Enter", o que foi digitado é retornado como uma **string**.
- Lembre que valor retornado por input() é sempre uma string e precisa ser tratado.
### format()
A função format() é usada para formatar uma string, substituindo marcadores de posição (chamados de "placeholders") pelos valores especificados. Isso é especialmente útil quando você deseja criar strings complexas ou formatar saídas. Veja um exemplo:
É possivel utilizar tambem de formatacoes diferentes utilizando .format, como por exemplo:
### isnumeric():

A função isnumeric() é usada para verificar se uma string contém apenas caracteres numéricos. Ela retorna True se todos os caracteres da string forem numéricos e False caso contrário. Veja um exemplo:
# Contagem no Python
É imporante notar que ele ignora o ultimo numero.
# Primitive Types/Tipos primitivos
**Tipos primitivos**
O que sao strings (str)
, intigre (int),  
float (float)
booleans (bool)

Funcao type, exemplo print

Funçao .format
Exemplo print('A soma entre {} e {} vale {}'.format(x,y,z))

Fucnoes de metodo de tipo, como print(z.isnum(input?))
O que sao strings, int, float e booleans.
Strings sao textos precisam ter aspas seguidas para utilizar no print.

int sao integrais, nao precisam de aspas entre aspas, e voce pode realizar contas dentro, como por exemplo: 
``` python
print(7+4), vai retornar 11.
``` 

Voce pode adicionar os valores como strings, usando as ''.
```python
print('7'+'4'), ele ira retornar 74, como a soma do texto 7 e do texto 4.
```

Porem voce nao consegue adicionar 2 campos diferente, como:
```python
print('Ola' + 5), ele era retornar um erro.
```
Para ter esse print sera necessario utilizar da seguinte forma:
```python
print('Ola' , 5)
```

Podemos utilizar o modo interativo usando a funcao input, usando 
nome = input('Qual seu nome?')

**Tipos primitivos**
O que sao strings (str)
, intigre (int),  
float (float)
booleans (bool)

Funcao type, exemplo print

Funçao .format
Exemplo print('A soma entre {} e {} vale {}'.format(x,y,z))

Fucnoes de metodo de tipo, como print(z.isnum(input?))
int sao integrais, nao precisam de aspas entre aspas, e voce pode realizar contas dentro, como por exemplo: 
``` python
print(7+4), vai retornar 11.
Voce pode adicionar os valores como strings, usando as ''.
```python
print('7'+'4'), ele ira retornar 74, como a soma do texto 7 e do texto 4.
```
Porem voce nao consegue adicionar 2 campos diferente, como:
```python
print('Ola' + 5), ele era retornar um erro.
Para ter esse print sera necessario utilizar da seguinte forma:
```python
print('Ola' , 5)
```
# Arrays/Listas
Pense em uma lista como uma caixa onde você pode guardar várias coisas, como brinquedos. Cada brinquedo é um "elemento" da lista. Você pode adicionar mais brinquedos, tirar brinquedos, ou até mesmo trocar um brinquedo por outro.

Um array é como uma estante organizada, onde você coloca livros. Cada livro é um "elemento" do array. Os livros têm números que indicam onde estão na estante, então você pode pegar um livro diretamente usando o número certo.

No mundo da programação, listas e arrays funcionam de maneira parecida. Uma lista é uma coleção de coisas, e cada coisa é um elemento. Em uma lista, você pode adicionar, remover ou trocar elementos facilmente. Um array é uma forma específica de lista, onde os elementos estão organizados por números, tornando mais eficiente encontrar um elemento específico.

Lembre-se, no Python, usamos principalmente listas para armazenar coleções de elementos, e se precisamos de funcionalidades mais avançadas para cálculos numéricos, podemos recorrer à biblioteca NumPy e seus arrays.
# Operadores Aritmeticos
- (=) É utilizado para armazenar dados, se eu utilizo pessoa = 5, eu estou armazenando o dado 5 na classe pessoa.

- (==) É utilizado como sinal de igualdade de fato, é importante ter isso em vista quando vai filtrar alguma informação.
Por exemplo, idades = 5 armazenaria o dado 5 em idades, enquanto idades == 5 vai iria trazer a igualdade.

- (+) Adição
Exemplo: 5+2 == 7

- (-) Subtração
5-2 == 3

- (*) Multiplicacão
5*2 == 10

- (/) Divisão
5/2 == 2.5

- (**) Potencia
5**2 == 25
É possivel utilizar a funcao pow tb, seguido dos numeros pow(5,2)

- (//) Divisao Inteira - Se eu divir 5/2 usando metodo de divisao, eu botaria 2, e 2*2=4, ou seja Resta 1.
2 Passa a ser o Inteiro da divisao, podendo ser percebido até mesmo como 2.5 em inteiro, 2.
5//2 ==2


- (%) Resto da divisão - É o resto que sobre da divsão entre 5/2, 1.
5%2 == 1

- (+=) ???
s = s + n == s+=n
 
#### Ordem de Precendencia
1. ()
2. **
3. * . / . // . %
4. + . -
### Librarys/Bibliotecas
Sao conjutos de Modulos com propositos especificos, e que necessitam ser instalados via pip install.
### Módulos
Comandos import é necessario para trazer determinadas funcoes

Comandos from x import y para filtrar exatamente o que se quer utilizar.

Biblioteca math
.ceil
.floor
.trunc
.pow
.sqrt
.factorial
# Manipulating Text

- Fatiamento de Strings
We're going to learn operations with strings in Python in this class. The main operations that we're going to see are Slicing, len() analysis, count(), find(), transformation using replace(), upper(), lower(), capitalize(), title(), strip(), merging with join().

frase[9:12]
frase = Curso em Video Python 
- Contar cada letra e espaco como um numero, 9:14 equivale a video 


### Funcoes de transformações.

- len()

- analysis

- count()
frase.count('o')
frase.count('o', 0, 13)

- find()

- replace()

- upper()

- lower()

- capitalize()

- title()

- strip()

- join()


### Metodos
Todo metodo leva parentenses no final?

Em Python, métodos são funções que estão associadas a objetos. Eles permitem que você realize operações específicas em um objeto ou modifique o objeto de alguma forma. Métodos são parte fundamental da programação orientada a objetos (POO) e são usados para encapsular lógica e funcionalidades relacionadas a um objeto específico.

Cada tipo de objeto em Python pode ter seus próprios métodos, que podem ser acessados através da notação de ponto (`.`). Por exemplo, se você tem uma variável `x` que é uma lista, você pode chamar métodos específicos de lista usando a sintaxe `x.metodo()`.

Por exemplo, considere uma lista chamada `my_list`:

```python
my_list = [1, 2, 3, 4, 5]
```

Aqui estão alguns exemplos de métodos que você pode usar com listas:

1. `append(valor)`: Adiciona um valor ao final da lista.
```python
my_list.append(6)
```

2. `remove(valor)`: Remove a primeira ocorrência do valor especificado na lista.
```python
my_list.remove(3)
```

3. `index(valor)`: Retorna o índice da primeira ocorrência do valor na lista.
```python
index = my_list.index(4)
```

4. `count(valor)`: Retorna o número de ocorrências do valor na lista.
```python
count = my_list.count(2)
```

Estes são apenas exemplos simples de métodos em Python. Cada tipo de objeto tem seus próprios métodos específicos que realizam tarefas relacionadas a esse tipo de objeto. A documentação oficial do Python é uma ótima fonte para aprender sobre os métodos disponíveis para diferentes tipos de objetos.
# Identação.
Em Python, a identação refere-se à maneira como você recua (indenta) o código para criar blocos de código. Em muitas outras linguagens de programação, como C++ ou Java, você usa chaves {} para definir blocos de código. No entanto, em Python, a identação é usada para indicar qual parte do código pertence a um bloco específico.
Aqui está um exemplo:

```python
if idade >= 18:
    print("Você é um adulto!")
else:
    print("Você é menor de idade.") 
```

Neste exemplo, a identação é usada para definir o bloco de código que pertence ao if e ao else. O código dentro do bloco if será executado se a condição idade >= 18 for verdadeira, e o código dentro do bloco else será executado se a condição for falsa.

Portanto, em resumo, em Python, a identação é a maneira de organizar e estruturar seu código, indicando quais partes do código pertencem a blocos específicos, como loops, condicionais, funções, entre outros. Certifique-se de manter a mesma quantidade de espaço em branco à esquerda para todos os elementos de um mesmo bloco. Isso ajuda o Python a entender a estrutura do seu código corretamente.
# Condicionais
Em Python, condicionais são estruturas de controle que permitem que o programa tome decisões com base em condições específicas. Elas permitem que você execute um bloco de código se uma determinada condição for verdadeira e outro bloco de código se essa condição for falsa. As condicionais mais comuns em Python são definidas usando as palavras-chave if, elif (abreviação de "else if") e else.

Aqui está um exemplo básico de como as condicionais funcionam em Python:
Neste exemplo, o código verifica se a variável idade é maior ou igual a 18. Se a condição for verdadeira, o programa imprimirá "Você é maior de idade." Caso contrário, imprimirá "Você é menor de idade."

Você também pode usar a cláusula elif para lidar com múltiplas condições. Aqui está um exemplo:
## Condicoes simples
Uma condição simples é uma estrutura de controle que envolve apenas um teste condicional. Isso significa que você está verificando apenas uma única condição e executando um bloco de código caso essa condição seja verdadeira. O bloco de código que deve ser executado está diretamente associado à condição única.

Exemplo de uma condição simples em Python:

## Condicoes compostas
Uma condição composta envolve vários testes condicionais, muitas vezes combinados usando as palavras-chave if, elif (abreviação de "else if") e else. Isso permite que você crie uma série de verificações sequenciais para lidar com diferentes cenários. Uma condição composta é útil quando você tem várias opções e quer decidir qual bloco de código deve ser executado dependendo de várias condições.

Exemplo de uma condição composta em Python:
- if = se
- else = senao
- elif = senao se

EXEMPLO:
if carro.esquerda():
    bloco True
else:
    bloco False
## Condições Aninhadas

# Cores no Terminal?

O que é um codigo ANSI?
\033[(style) (text) (back)m

\033[0:33:44m

##### Style
0 - None
1 - Bold
4 - Underline
7 - Negative

##### Text
30 Branco
31 Vermelho
32 Verde
33 Amarelo
34 Azul
35 Roxo
36 Ciano
37 Cinza

##### Back
40 Branco
41 vermelho
42 verde
43 amarelo
44 azul
45 roxo
46 ciano
47 cinza
Claro, vou transformar isso em uma tabela usando a sintaxe de markdown:

| Style | Código | Texto     |
|-------|--------|-----------|
| 0     | None   | Branco    |
| 1     | Bold   | Vermelho  |
| 4     | Underline | Verde   |
| 7     | Negative | Amarelo  |




| Código | Back   | Texto     |
|--------|--------|-----------|
| 30     | Branco | Branco    |
| 31     | Vermelho | Vermelho |
| 32     | Verde  | Verde     |
| 33     | Amarelo | Amarelo  |
| 34     | Azul   | Azul      |
| 35     | Roxo   | Roxo      |
| 36     | Ciano  | Ciano     |
| 37     | Cinza  | Cinza     |

A tabela acima representa as informações fornecidas em um formato organizado.
# Estruturas de Repetições
laço = for
in = no

Exemplo:
```python
for c in range(1,10)
    passo
pega
```

## Estrutura de repetição for
É imporante notar que ele ignora o ultimo numero.
Varivel de Controle,
Laço de Variavel de controle.
Identacao.
## Estrutura de repetição while
while = enquanto
while not = enquanto NAO
if = se

```python
while not x:
    if x:
        +1

Claro! A função de repetição `while` em Python é utilizada para criar loops que executam um bloco de código repetidamente enquanto uma condição especificada for verdadeira. A estrutura básica do `while` é a seguinte:

```python
while condição:
    # bloco de código a ser repetido enquanto a condição for verdadeira
```

Aqui está um exemplo completo que abrange todas as possibilidades da função `while`, juntamente com uma explicação detalhada para cada parte do código:

```python
# Vamos criar um programa que solicita ao usuário um número inteiro e, em seguida,
# calcula a soma dos números inteiros de 1 até o número fornecido pelo usuário.

# Passo 1: Solicitar um número inteiro ao usuário
numero_fornecido = int(input("Digite um número inteiro: "))

# Passo 2: Inicializar variáveis para a soma e o contador
soma = 0
contador = 1

# Passo 3: Criar um loop while com base na condição do contador
while contador <= numero_fornecido:
    # O bloco de código dentro do loop será executado enquanto a condição for verdadeira
    
    # Passo 4: Adicionar o valor do contador à soma
    soma += contador
    
    # Passo 5: Incrementar o contador para prosseguir para o próximo número
    contador += 1

# Passo 6: Exibir o resultado da soma
print(f"A soma dos números de 1 até {numero_fornecido} é {soma}")
```

Agora, vamos detalhar cada parte do código:

1. **Solicitar um número inteiro ao usuário (`numero_fornecido`):** O programa começa pedindo ao usuário para digitar um número inteiro. A função `input()` é usada para receber a entrada do usuário, e `int()` é usada para converter a entrada em um número inteiro.

2. **Inicializar variáveis (`soma` e `contador`):** Duas variáveis são criadas. `soma` será usada para acumular os valores dos números inteiros, e `contador` será usado para acompanhar qual número estamos atualmente somando.

3. **Criar um loop while:** Aqui começa o loop `while`. Enquanto a condição `contador <= numero_fornecido` for verdadeira, o bloco de código dentro do loop será executado repetidamente.

4. **Adicionar o valor do contador à soma:** Dentro do loop, o valor atual do `contador` é adicionado à variável `soma`.

5. **Incrementar o contador:** O valor do `contador` é incrementado em 1 a cada iteração do loop, permitindo que o programa prossiga para o próximo número na sequência.

6. **Exibir o resultado:** Após o loop ter terminado, ou seja, quando a condição `contador <= numero_fornecido` for falsa, o programa exibe a soma dos números inteiros de 1 até o número fornecido pelo usuário.

Este exemplo abrange todas as fases de um loop `while` em Python: inicialização, condição, bloco de código dentro do loop e atualização. O loop continuará executando até que a condição especificada seja falsa.
### Interrompendo repetições while
# Tuplas
Uma tupla em Python é como uma lista, mas com uma diferença importante: as tuplas não podem ser modificadas depois de criadas. É como se você colocasse algumas coisas em uma caixa e fechasse a tampa bem forte. Você ainda pode ver o que está dentro, mas não pode adicionar, remover ou trocar nada.

Pense em uma tupla como uma lista "imutável". Ela é ótima para armazenar informações que você não quer que sejam alteradas acidentalmente. Cada item em uma tupla é um "elemento", assim como na lista, mas você não pode fazer mudanças nesses elementos depois de criar a tupla.

Por exemplo, se você tiver informações sobre uma pessoa, como nome e idade, e quiser ter certeza de que essas informações não mudem, você poderia usar uma tupla para armazená-las.

Em resumo, uma tupla em Python é como uma lista que não pode ser alterada após ser criada. Ela é usada para armazenar dados que precisam ser mantidos constantes.
# Listas
### Dicionários
# Funçoes
# Módulos e Pacotes
# Tratamento de Erros e Exceções
# outros assuntos
## Variaveis
### Funcoes Build in Variaveis 1

## Funcoes e Modulos

## Tipos Primitivos
### Funcoes Build in Primitivas
#### String(str)
#### Bolean(bolean)
#### Integre
#### Float (float) 

## Estrutura de Decisão

## Estrutura de Repeticão

## Formatação de String
