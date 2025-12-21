# Automação de Relatório de Exames Médicos Vencidos

## 📌 Descrição do Projeto

Este projeto foi desenvolvido com o objetivo de **automatizar a análise de uma planilha Excel e a geração de um relatório em PDF contendo exames médicos vencidos**, atividade comum na rotina de um **Técnico de Segurança do Trabalho**.

A automação reduz tarefas manuais, diminui o risco de erros humanos e garante agilidade no controle de exames ocupacionais, além de possibilitar o **envio automático do relatório por e-mail**.

---

## 🎯 Objetivo

- Ler uma planilha Excel contendo dados de exames médicos  
- Identificar exames com data de vencimento igual ou anterior à data atual  
- Gerar automaticamente um relatório em PDF com os exames vencidos  
- Enviar o relatório por e-mail como anexo  

---

## ⚙️ Funcionalidades

- Leitura de planilha Excel com **pandas**
- Tratamento e validação de datas
- Filtro automático de exames vencidos
- Geração de relatório em PDF com **ReportLab**
- Estilização do relatório (título, tabela e totalizador)
- Envio automático do PDF por e-mail via **SMTP**
- Mensagens de status durante a execução

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **pandas** – Manipulação e análise de dados
- **ReportLab** – Geração de relatórios em PDF
- **smtplib / email.mime** – Envio de e-mails com anexo
- **datetime** – Controle de datas

---

## 📁 Estrutura Esperada da Planilha

A planilha Excel deve conter, no mínimo, as seguintes colunas:

- `Nome Profissional` - (pode ser alterado de acordo com sua planilha)
- `Aci` - (pode ser alterado de acordo com sua planilha)
- `Data Vencimento` - (pode ser alterado de acordo com sua planilha)

Além disso, o código espera uma **aba específica**, que deve ser configurada no script.

---

## 🚀 Como Utilizar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/AutomacaoRelatorioMedico.git
