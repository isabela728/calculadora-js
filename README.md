# Calculadora Web em JavaScript

## Funcionalidades

- **Operações Básicas**: Adição, Subtração, Multiplicação (`X`) e Divisão (`/`).
- **Cálculo de Porcentagem**: Suporte prático para porcentagens (converte `%` dinamicamente).
- **Limpeza Rápida (AC)**: Reseta a tela e a memória de cálculo com um único clique.
- **Apagar Último Dígito**: Botão com ícone customizado para remover um caractere por vez.
- **Tratamento de Erros**:
  - Evita a inserção de múltiplos pontos decimais no mesmo número.
  - Impede a repetição seguida de operadores (substitui o operador antigo pelo novo).
  - Trata expressões terminadas com operadores antes de efetuar a conta.
  - Exibe a mensagem de `Erro` caso ocorra uma expressão inválida.

---

## Design e Interface

A interface foi desenvolvida focando no tema escuro (*Dark Mode*), oferecendo bom contraste e legibilidade:
- **Botões Circulares**: Estilo elegante com estados visuais claros.
- **Destaques de Cores**: Operadores em laranja chamativo, controles em cinza claro e números em cinza escuro.
- **Display Flexível**: Garante alinhamento à direita e quebra de linha quando necessário.

---

## Tecnologias Utilizadas

- **HTML**
- **CSS**
- **JavaScript**

---

## Estrutura do Projeto

```text
calculadora-js/
├── assets/          # Ícones e recursos visuais (ex: ícone do botão apagar)
├── index.html       # Estrutura HTML da calculadora
├── style.css        # Estilos, tema dark e layout em grid
├── script.js        # Lógica matemática e comportamentos
└── README.md        # Documentação do projeto
```

---

## Como Executar o Projeto

Como o projeto é construído apenas com tecnologias nativas, você não precisa instalar nenhuma dependência.

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/isabela728/calculadora-js.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd calculadora-js
   ```

3. **Abra o arquivo `index.html`:**
   - Basta dar um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador de sua preferência.
   - Ou utilize a extensão **Live Server** no VS Code para rodar localmente com atualização automática.

