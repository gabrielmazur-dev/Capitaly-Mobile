# Capitaly Mobile 📱

Versão mobile do **Capitaly**, plataforma de gestão financeira pessoal.
Permite organizar receitas, despesas, dívidas, investimentos, veículos e metas
em um só lugar, direto do celular.

> Projeto interdisciplinar de Engenharia de Software II e Programação em Scripts
> — Fatec São Caetano do Sul. Orientação: Prof. Humberto Luiz de Toledo.

## Funcionalidades

- **Autenticação:** login e cadastro com validação de campos e e-mail duplicado
- **Dashboard:** saldo total, receitas, despesas e gráfico de despesas por categoria
- **Receitas, Despesas, Dívidas, Investimentos, Veículos e Metas:**
  cadastro, listagem, busca por nome, edição e exclusão
- **Configurações:** perfil, alteração de senha, sobre o app e logout

## Tecnologias

| Camada | Tecnologia |
|---|---|
| Aplicativo | Microsoft Power Apps (Canvas App, formato celular) |
| Lógica | Power Fx |
| Dados | SharePoint Online (listas) |
| Integrações | Power Automate (HTTP / Analisar JSON), Office 365 Outlook |

## Estrutura do app

**Telas:** login, cadastro, dashboard, menu, receitas, despesas, dívidas,
investimentos, veículos, metas, configurações, alterar senha, sobre o app.

**Listas SharePoint:** Usuários, Receitas, Despesas, Dívidas,
Investimentos, Veículos, Metas.

## Como executar

1. Crie as 7 listas no SharePoint com as colunas usadas pelo app
2. No Power Apps, importe o arquivo `prj_capitaly.msapp`
3. Reconecte as fontes de dados às suas listas
4. Execute (▶) ou publique e abra no app Power Apps do celular

## Telas

(inserir prints: login, dashboard, receitas, metas...)

## Limitações e próximos passos

- Integração com IA presente na versão web ainda não implementada no mobile
- Armazenamento de senhas com hash
- Planos Normal e Premium

## Equipe

- Gabriel Almeida Mazur
- Guilherme Santos Souza
