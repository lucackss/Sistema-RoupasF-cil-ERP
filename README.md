# 💻 Projeto GCS – Loja de Roupas Femininas

## 🛍️ BoutiqueManager

**Tema:** Sistema de controle de estoque e pedidos para loja de roupas femininas
**Ferramenta de GCS:** GitHub

### 👩‍💻 Integrantes

* **Lucas Lima** – Gestor de Configuração
* **Juliana** – Desenvolvedora Principal
* **Michael Douglas** – Revisor de Código

---

## 🧩 1. Planejamento da Configuração

### Itens de Configuração

* Código-fonte do sistema (`.py`, `.js` ou `.html`)
* Arquivos de configuração (`config.json`)
* Documentação (`README.md`, `RELATORIO.md`)
* Base de dados simulada (`produtos.json`, `clientes.json`)
* Prints e imagens de resultados (`/img/`)

### Convenções de Nomeação

* **Branches:**

  * `feature/cadastro-produto`
  * `feature/pedidos-clientes`
  * `fix/erro-listagem`
  * `release/1.0`
* **Commits:**

  * `feat:` → nova funcionalidade
  * `fix:` → correção
  * `docs:` → documentação
  * `refactor:` → melhorias de código
  * **Exemplo:** `feat: adicionar cadastro de novos produtos`

### Política de Versionamento

* **Versão 1.0.0:** versão inicial com cadastro e listagem de produtos
* **Versão 1.1.0:** módulo de pedidos
* **Versão 1.2.0:** relatórios de vendas
* **Versão 1.2.1:** correções de bugs
* Segue o padrão **SemVer (MAJOR.MINOR.PATCH)**

### Política de Branching

* `main` → versão estável do projeto
* `develop` → integração de novas funcionalidades
* `feature/*` → desenvolvimento de cada integrante
* `hotfix/*` → correções urgentes
* `release/*` → preparação de novas versões

### Estratégia de Backup e Recuperação

* Código hospedado no **GitHub (nuvem)**
* Cada membro mantém cópia local via `git clone`
* Sincronização com `git pull origin develop`
* Backup extra via `git bundle` se necessário

---

## ⚙️ 2. Criação do Repositório e Setup

1. **Criação do repositório:**
   `github.com/grupo-boutique/BoutiqueManager`

2. **Conteúdo do README.md:**

   * Descrição do projeto
   * Objetivo
   * Linguagem utilizada
   * Funcionalidades principais
   * Integrantes e funções

3. **Estrutura inicial dos arquivos:**

   ```
   /src
     app.py
     produtos.py
     pedidos.py
   /data
     produtos.json
     clientes.json
   /docs
     relatorio.md
   /img
     print_commits.png
   README.md
   .gitignore
   ```

4. **Permissões:**
   Adicionar Maria e João como *Collaborators* no GitHub.

---

## 🔄 3. Controle de Versão e Colaboração

### Passos Realizados

1. **Criação das branches individuais**

   * Lux → `feature/configuracao-inicial`
   * Maria → `feature/cadastro-produto`
   * João → `feature/pedidos-clientes`

2. **Commits padronizados**

   ```bash
   git commit -m "feat: adicionar função de cadastro de produto"
   git commit -m "fix: corrigir bug na listagem de produtos"
   ```

3. **Pull Requests**

   * Cada membro envia *Pull Request* para a branch `develop`.
   * João (revisor) analisa e aprova o *merge*.

4. **Simulação de Conflito**

   * Lux e Maria alteraram o mesmo trecho em `app.py`.
   * Git apontou conflito → resolvido manualmente, mantendo a versão mais atualizada e comentada.

5. **Criação de Tags**

   ```bash
   git tag -a v1.0.0 -m "Versão inicial com cadastro de produtos"
   git push origin v1.0.0
   ```

---

## 🧾 4. Relatório Final

### Estrutura de Repositório e Política de Branching

Fluxo de desenvolvimento:

```
main
 └── develop
      ├── feature/cadastro-produto
      ├── feature/pedidos-clientes
      └── fix/erro-listagem
```

### Dificuldades e Soluções

| Dificuldade                  | Solução                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| Conflitos de merge no app.py | Comunicação entre os membros e comparação manual das versões |
| Commits fora do padrão       | Definição de convenção padronizada para mensagens            |
| Branches desatualizadas      | Uso de `git pull` e `git merge develop` antes de cada push   |

### Exemplo de Conflito Resolvido

* **Arquivo:** `app.py`
* **Situação:** Funções de listagem duplicadas.
* **Solução:** Mantida a versão de Maria, incorporando o log criado por Lux.

### Histórico de Commits

![Histórico de commits](img/print_commits.png)

### Conclusões

O uso do GitHub como ferramenta de GCS foi essencial para compreender a importância do **controle de versão**, **colaboração** e **organização** no desenvolvimento em equipe.
O projeto simulou um ambiente real, com situações de **merge, conflitos e revisão de código**, e mostrou como práticas como **versionamento semântico** e **políticas de branching** mantêm o fluxo de trabalho eficiente e seguro.

Além disso, o sistema desenvolvido tem potencial para evoluir e se tornar uma aplicação real de apoio à **gestão de uma loja de roupas femininas**, automatizando cadastros, pedidos e controle de estoque.

---

**Repositório:** [github.com/grupo-boutique/BoutiqueManager](https://github.com/grupo-boutique/BoutiqueManager)
