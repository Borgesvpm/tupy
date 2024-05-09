# tupy
Um tutor avançado de Python para concursos públicos e certificações.

## Apresentação
Olá, pessoas!

Meu nome é Vinicius Borges, sou mestre em Neurociências, analista do SERPRO, sou professor de programação em Python e escritor de dois livros sobre aprendizagem e programação: um chama-se "O Guia Definitivo do Estudante" e outro "O Zen do Python - Uma Introdução Suave à Programação".

Eu produzo materiais de estudo de programação voltados para concursos públicos e certificações. Para este desafio da Alura e da Google, resolvi alimentar o modelo Gemini com algumas das minhas anotações e fiquei surpreendido com o resultado! Eu pessoalmente aprendi diversas coisas novas ao brincar com o modelo por algumas horas.

## Importante
O modelo, por vezes, alucina respostas, provavelmente embaralhando outras linguagens com o Python na sua representação interna do embedding.

Se você é um estudante, recomendo o uso da ferramenta com uma ferramenta rodando Python ao lado, **sempre confirmando** o resultado proposto.
De qualquer maneira, mesmo para alunos avançados, o Gemini está produzindo questões surpreendentes e muito divertidas de fazer.

## Exemplo de perguntas geradas

```python
x = 10
y = 5
x, y, z = x,x + y,y
print(z) 
```

```shell
5
```

```python
def gen(n):
   for i in range(n):
      yield i
      yield from gen(i)

print(list(gen(3)))
```

```shell
[0, 1, 0, 2, 0, 1, 0]
```

Segue meu exemplo favorito:

```python
def f(x, l=[]):
   for i in range(x):
      l.append(i*i)
   print(l)

f(2)
f(3,[3,2,1])
f(3)
```

```shell
[0, 1]
[3, 2, 1, 0, 1, 4]
[0, 1, 0, 1, 4] 
```

## Redes sociais
https://www.instagram.com/vi_neuro/
