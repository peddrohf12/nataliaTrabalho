# Trabalho Prático DevOps - Natalia

![Status](https://github.com/peddrohf12/nataliaTrabalho/actions/workflows/main.yml/badge.svg)

Este projeto foi criado para a disciplina da professora Natália, com o objetivo de aplicar conceitos de **CI/CD** e **Automação de Testes**.

## 🌐 Site Online
O site pode ser acessado através deste link:
[https://peddrohf12.github.io/nataliaTrabalho/](https://peddrohf12.github.io/nataliaTrabalho/)

## 🚀 O que a automação (GitHub Actions) faz:
Sempre que eu envio um código novo (`git push`), o GitHub roda uma série de testes automáticos:
* **Verificação de HTML:** Confere se não esqueci nenhuma tag aberta ou erro de código.
* **Teste de Segurança:** Proíbe comentários como "TODO" ou senhas no código.
* **Controle de Imagens:** Não deixa subir imagens muito pesadas (maiores que 500KB).
* **Deploy Automático:** Se todos os testes passarem, o site é atualizado sozinho no GitHub Pages.

## 🔒 Segurança da Branch
Configurei uma regra de proteção na branch `main`. Isso significa que:
* Ninguém consegue subir código errado.
* O merge só é liberado se os testes (Checks) ficarem verdes ✅.

## 📂 Estrutura do Projeto
* `.github/workflows/`: Arquivos de configuração da automação.
* `assets/` e `imagens/`: Fotos do portfólio.
* `index.html`: Página principal.
* `style.css`: Estilização visual.

**Autor:** Pedro Henrique  
**Colaborador:** `09116428-collab`