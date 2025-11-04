# 🧵 BoutiqueManager

**Autores:**

* Lux
* Maria
* João

---

## 💡 Sobre o projeto

O **BoutiqueManager** é um sistema simples de gerenciamento de estoque voltado para **lojas de roupas femininas**.
Com ele, é possível **cadastrar, listar, atualizar e vender produtos**, mantendo o controle de forma prática e organizada.

O projeto foi desenvolvido como parte de um trabalho acadêmico sobre **Gerenciamento de Dados e Processos**, simulando o uso de um sistema interno para uma boutique moderna e bem estruturada.

---

## 🎯 Funcionalidades

✅ Cadastrar novos produtos (nome, tamanho, preço e quantidade)
✅ Listar o estoque atual com todas as informações dos produtos
✅ Atualizar o estoque manualmente (quando há reposição ou perda)
✅ Registrar pedidos (atualizando automaticamente o estoque)
✅ Armazenamento local em arquivo `.json` (persistência simples)

---

## 🛠️ Tecnologias utilizadas

* **Python 3.x**
* **JSON** (para armazenamento dos dados)
* Execução em **terminal/console**

---

## ⚙️ Como executar o sistema

1. **Baixe ou clone o repositório**:

   ```bash
   git clone https://github.com/seuusuario/BoutiqueManager.git
   cd BoutiqueManager
   ```

2. **Crie a pasta de dados (caso ainda não exista)**:

   ```bash
   mkdir data
   ```

3. **Execute o programa:**

   ```bash
   python app.py
   ```

4. **Escolha uma das opções do menu interativo:**

   ```
   ===== 🧵 BoutiqueManager =====
   1️⃣  Listar produtos
   2️⃣  Cadastrar produto
   3️⃣  Atualizar estoque
   4️⃣  Registrar pedido
   5️⃣  Sair
   ```

---

## 🧾 Estrutura do projeto

```
BoutiqueManager/
│
├── app.py               # Código principal do sistema
├── data/
│   └── produtos.json    # Banco de dados local (gerado automaticamente)
└── README.md            # Este arquivo
```

---

## 🖼️ Exemplo de execução

```
===== 🧵 BoutiqueManager =====
1️⃣  Listar produtos
2️⃣  Cadastrar produto
3️⃣  Atualizar estoque
4️⃣  Registrar pedido
5️⃣  Sair

Escolha uma opção: 2

=== Cadastro de Novo Produto ===
Nome: Blusa Floral
Tamanho (P/M/G): M
Preço (R$): 79.90
Quantidade: 10

✅ Produto 'Blusa Floral' cadastrado com sucesso!
```

---

## 💬 Conclusão

O **BoutiqueManager** demonstra como um sistema simples, porém bem estruturado, pode otimizar a rotina de uma loja de roupas femininas — oferecendo praticidade, organização e controle sobre o estoque.
É uma ferramenta educativa e útil, feita com dedicação e foco em aprendizado. 💖
