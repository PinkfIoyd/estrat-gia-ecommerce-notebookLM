# python-iniciante-notebookLM

1- Objetivo: Meu objetivo é tirar dúvidas sobre Python, para escrever códigos mais claros e condizentes com boas práticas.

2- Fontes ulitizadas de documentações oficiais Python: https://docs.python.org/pt-br/3/ , https://devguide.python.org/documentation/ , https://peps.python.org/pep-0008/ , https://docs.python.org/pt-br/3/tutorial/index.html , https://docs.python.org/pt-br/3/tutorial/index.html

3- Utilizei prompts simples focados em boas práticas e assuntos específicos, como: 'Me explique a função das listas e como utiliza-lás de maneira correta', 'Gostaria de saber como estruturar boas funções para que sejam de fácil entendimento para outras pessoas'

4.1- Resumo Estruturado:
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

4.2 - Glossário:
- Função: bloco de código reutilizável
- Docstring: descrição interna da função
- Type Hint: indicação de tipo de dado
- Lista: estrutura de dados ordenada e mutável
- Índice: posição de um elemento na lista
- List Comprehension: forma compacta de criar listas

4.3- Prompts Reutilizáveis:
- "Explique [conceito] com exemplos práticos e código"
- "Quais são erros comuns ao usar [conceito]?"
- "Compare [conceito A] e [conceito B] com exemplos"
- "Refatore esse código para melhorar legibilidade"
- "Esse código segue boas práticas do Python? Justifique"

4.4 Lições Aprendidas:
### Principais aprendizados

- Perguntas genéricas geram respostas superficiais
- A IA tende a explicar, mas não criticar código
- Compreensões de lista podem prejudicar legibilidade se mal usadas
- Type hints ajudam mais quem lê do que quem escreve

### Dificuldades encontradas

- Entender a diferença entre expressão e instrução
- Saber quando usar list comprehension vs for tradicional

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
