# Miniguia de Estudos: Boas Práticas em Python

---

## 1. Objetivo

Meu objetivo é tirar dúvidas sobre Python para escrever códigos mais claros, legíveis e alinhados com boas práticas da linguagem.

---

## 2. Fontes Utilizadas

- https://docs.python.org/pt-br/3/  
- https://devguide.python.org/documentation/  
- https://peps.python.org/pep-0008/  
- https://docs.python.org/pt-br/3/tutorial/index.html  

---

## 3. Engenharia de Prompts

Utilizei prompts simples, focados em boas práticas e tópicos específicos:

- "Me explique a função das listas e como utilizá-las de maneira correta"
- "Gostaria de saber como estruturar boas funções para que sejam de fácil entendimento para outras pessoas"

### Observações

- Prompts genéricos geraram respostas superficiais  
- Prompts mais específicos produziram respostas mais úteis e aplicáveis  

---

4. Miniguia de Estudo
4.1 Resumo Estruturado

Aqui você NÃO copia o texto.
Você reduz para o essencial.

Exemplo baseado no que você trouxe:

### Funções em Python

Uma função deve ser clara, previsível e fácil de entender.

Boas práticas principais:
- Nome descritivo (snake_case)
- Uma única responsabilidade
- Uso de docstrings para documentação
- Tipagem com type hints
- Retornos consistentes

Exemplo:

def calcular_media(notas: list[float]) -> float:
    """Calcula a média de uma lista de notas."""
    return sum(notas) / len(notas)
### Listas em Python

Listas são estruturas que armazenam múltiplos valores em ordem.

Características:
- Acesso por índice (começa em 0)
- Mutáveis
- Permitem diferentes tipos de dados

Boas práticas:
- Iterar com `for item in lista`
- Evitar `len(lista) == 0`, usar `if not lista`
- Usar list comprehension com moderação

Exemplo:

numeros = [1, 2, 3]
quadrados = [x**2 for x in numeros]
4.2 Glossário

Direto e útil:

- Função: bloco de código reutilizável
- Docstring: descrição interna da função
- Type Hint: indicação de tipo de dado
- Lista: estrutura de dados ordenada e mutável
- Índice: posição de um elemento na lista
- List Comprehension: forma compacta de criar listas
4.3 Prompts Reutilizáveis

Aqui você mostra maturidade. Não é repetir perguntas — é criar ferramentas mentais.

- "Explique [conceito] com exemplos práticos e código"
- "Quais são erros comuns ao usar [conceito]?"
- "Compare [conceito A] e [conceito B] com exemplos"
- "Refatore esse código para melhorar legibilidade"
- "Esse código segue boas práticas do Python? Justifique"
4.4 Lições Aprendidas (essa é a parte que diferencia)

Aqui está o ponto onde você provavelmente está deixando valor na mesa.

Você precisa expor:

Onde a IA falhou
Onde você teve dúvida
O que você percebeu

Exemplo forte:

### Principais aprendizados

- Perguntas genéricas geram respostas superficiais
- A IA tende a explicar, mas não criticar código
- Compreensões de lista podem prejudicar legibilidade se mal usadas
- Type hints ajudam mais quem lê do que quem escreve

### Dificuldades encontradas

- Entender a diferença entre expressão e instrução
- Saber quando usar list comprehension vs for tradicional
def calcular_media(notas: list[float]) -> float:
    """Calcula a média de uma lista de notas."""
    return sum(notas) / len(notas)

---

## 5. Conclusão

### Principais aprendizados

- Funções bem estruturadas dependem mais de clareza do que de complexidade
- Nomeação e organização têm impacto direto na legibilidade
- Listas são simples, mas seu uso pode se tornar confuso sem boas práticas
- A qualidade das respostas da IA depende diretamente da qualidade dos prompts

### Limitações e pontos a melhorar

- Ainda tenho dificuldade em decidir quando usar list comprehension vs laços tradicionais
- Preciso melhorar a escrita de prompts mais específicos
- Em alguns momentos, aceitei respostas da IA sem questionar profundamente

### Próximos passos

- Praticar refatoração de código para melhorar legibilidade
- Estudar mais exemplos reais de código bem escrito
- Explorar casos mais complexos de funções e estruturas de dados
