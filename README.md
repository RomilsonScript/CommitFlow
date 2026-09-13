# 🚀 CommitFlow - Gerenciador de Commits Pro

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-brightgreen.svg)](https://github.com/TomSchimansky/CustomTkinter)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Um aplicativo desktop com interface gráfica moderna desenhado para simplificar o seu fluxo de trabalho com o Git. Gerencie múltiplos projetos, faça os primeiros commits (vínculo de repositório) e atualizações diárias de código com apenas um clique, sem precisar abrir o terminal.

---

## ✨ Funcionalidades

* **Gestão Multi-Projetos:** Cadastre a pasta local e a URL do repositório apenas uma vez. O app salva tudo em um arquivo de configuração `projetos.json`.
* **Interface Moderna:** UI em modo escuro (Dark Mode) com cantos arredondados construída com a biblioteca `CustomTkinter`.
* **1º Commit Simplificado:** Um único botão para inicializar o repositório (`git init`), adicionar os arquivos, criar a branch `main`, vincular a origem e fazer o `push`.
* **Commit Rápido:** Adicione suas mudanças e faça o push (`git add .`, `git commit -m`, `git push`) em segundos.
* **Terminal Integrado e Multithreading:** Acompanhe o log do Git em tempo real na própria interface. O processo roda em segundo plano, evitando que o aplicativo congele.

## ⚙️ Pré-requisitos

Para usar o aplicativo, você só precisa ter instalado no seu computador:
* [Git](https://git-scm.com/) (devidamente configurado com seu `user.name` e `user.email`).

*(O Python só será necessário caso você queira rodar ou modificar o código-fonte).*

---

## 📖 Tutorial de Instalação e Uso

Você pode escolher usar a versão pronta (Executável) ou rodar direto do código-fonte.

### Opção 1: Usando o Executável (.exe) - *Mais Fácil*

1. Acesse a aba **[Releases](https://github.com/RomilsonScript/CommitFlow/releases)** aqui no GitHub.
2. Baixe o arquivo `CommitFlow.exe` (ou o nome que você deu ao executável).
3. Salve em uma pasta da sua preferência e dê um duplo clique para abrir.
   > **Nota:** Como o executável não tem assinatura digital comercial, o Windows pode exibir uma tela azul do *SmartScreen*. Basta clicar em **Mais informações** e depois em **Executar assim mesmo**.

### Opção 2: Pelo Código-Fonte (Para Desenvolvedores)

Se você quer modificar o código ou ver como funciona:

```bash
# Clone o repositório para sua máquina
git clone [https://github.com/RomilsonScript/CommitFlow.git](https://github.com/RomilsonScript/CommitFlow.git)
