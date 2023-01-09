# Curso Testes Unitários em Java com JUnit

Repositório criado com o intuito de realizar as aulas práticas do curso Testes Unitários em Java com JUnit realizado pela Udemy. 

# Testes unitário em Java utilizando JUnit

- Estrutura de um bom teste
- Como escrever documentação com comentários para que fique bem claro para outras pessoas
- Como otimizar testes com cenários parecidos, utilizando: SetUp e TearDown

```jsx
@Before
public void setUp(){
//Código
}

@After
public void tearDown(){
//Código
}
```

- Suite de testes - Realizar todos os testes de uma vez só utilizando:

```jsx
@RunWith
@SuiteClasses
```

- Valor limite

## **Artigo**

**Análise do Valor limite**

"O comportamento nos limites de uma partição de equivalência é onde existe maior probabilidade de estar incorreto. Portanto, limites são áreas onde testes estão mais propensos a indicar defeitos. Os valores limites de uma partição são seu máximo e seu mínimo.

A análise do valor limite pode ser aplicada em todos os níveis de teste e é relativamente fácil aplicá-la. Sua capacidade de encontrar defeitos é alta e especificações detalhadas podem ser úteis em sua elaboração. Pode ser aplicada para entradas manuais como, por exemplo, em escalas de tempo ou tabela de limites."

![https://img-b.udemycdn.com/redactor/raw/2018-03-11_01-17-07-7429c75306537038865091b29c5e6805.jpg](https://img-b.udemycdn.com/redactor/raw/2018-03-11_01-17-07-7429c75306537038865091b29c5e6805.jpg)

Ou seja, análise do valor limite nada mais é do que uma técnica de teste utilizada para exercitar os limites do domínio de entrada.

Um exemplo seria: "O campo **Idade** deve aceitar valores entre 18 e 65".

Quando você for testar o funcionamento deste campo, deve considerar testar os limites do intervalo:

. 17 e 18 anos;

. 65 e 66 anos.

É comum encontrar falhas em sistemas quando testamos os limites dos intervalos que determinam quais valores são ou não válidos.

*Syllabus - CTFL*

[Testes+Automáticos+de+Software.pdf](Testes%20unita%CC%81rio%20em%20Java%20utilizando%20JUnit%20fa57fe63277e48fa9787b87ad96d2294/TestesAutomticosdeSoftware.pdf)

 <a href="https://www.linkedin.com/in/j%C3%A9ssica-nicodemos-de-melo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
