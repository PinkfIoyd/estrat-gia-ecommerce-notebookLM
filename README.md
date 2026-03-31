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

## 4. Miniguia de Estudo

### 4.1 Resumo Estruturado

#### Funções em Python

Uma função deve ser clara, previsível e fácil de entender.

**Boas práticas:**
- Nome descritivo (`snake_case`)
- Responsabilidade única
- Uso de docstrings
- Tipagem com type hints
- Retornos consistentes

**Exemplo:**
```python
def calcular_media(notas: list[float]) -> float:
    """Calcula a média de uma lista de notas."""
    return sum(notas) / len(notas)
