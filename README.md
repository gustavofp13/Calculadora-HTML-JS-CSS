# 🧮 Calculadora Simples

Exercício de fixação com foco em **JavaScript**: manipulação do DOM, eventos e funções. Interface HTML minimalista que realiza operações matemáticas básicas a partir de dois valores informados pelo usuário.

> ⚠️ Projeto em desenvolvimento — a estilização (CSS) ainda será adicionada.

## 📋 Funcionalidades

O usuário informa dois valores numéricos e escolhe uma operação:

- ➕ Soma
- ➖ Subtração
- ✖️ Multiplicação
- ➗ Divisão
- 📈 Potenciação

O resultado é exibido dinamicamente na página, sem a necessidade de recarregá-la.

## 🛠️ Tecnologias

- HTML5
- JavaScript (Vanilla)

## 📁 Estrutura do projeto

```
├── Exercicio_1.html   # Estrutura da página e lógica de interação
└── script.js          # Funções das operações matemáticas
```

## ▶️ Como usar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra o arquivo `Exercicio_1.html` no navegador.
3. Preencha os valores A e B, selecione a operação e clique em **Executar**.

## 🚧 Próximos passos

- [ ] Adicionar estilização com CSS
- [ ] Validar campos vazios/inválidos antes do cálculo
- [ ] Substituir o uso de `eval()` por `Number()` ou `parseFloat()` na leitura dos valores
- [ ] Melhorar o tratamento da divisão por zero (atualmente usa `alert`)

## ✍️ Autor

Desenvolvido por **Gustavo** como parte dos estudos em desenvolvimento web.
