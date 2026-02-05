# Trabalho Prático DevOps - Natalia

![Status](https://github.com/peddrohf12/nataliaTrabalho/actions/workflows/main.yml/badge.svg)

## O que a automação (GitHub Actions) faz:
Sempre que eu envio um código novo (`git push`), o GitHub roda uma série de testes automáticos:
* **Verificação de HTML:** Confere se não esqueci nenhuma tag aberta ou erro de código.
* **Teste de Segurança:** Proíbe comentários potencialmente perigosos
* **Controle de Imagens:** Não deixa subir imagens muito pesadas (maiores que 500KB).
* **Deploy Automático:** Se os testes passarem, o site é atualizado sozinho no GitHub Pages.

## 📂 Estrutura do Projeto
* `.github/workflows/`: Arquivos de configuração da automação.
* `assets/` e `imagens/`: Fotos do portfólio.
* `index.html`: Página principal.
* `style.css`: Estilização visual.

**Autor:** Pedro Henrique  
