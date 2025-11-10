# 📊 Hypex — Fluxo de Análise do YouTube com n8n

Este repositório contém o **fluxo de automação do projeto Hypex**, desenvolvido para coletar e processar dados diretamente da **API do YouTube** usando a plataforma **n8n**.

---

## 🧩 Sobre o Projeto

O **Hypex** tem como objetivo automatizar a coleta e análise de informações sobre vídeos do YouTube, facilitando o estudo de métricas e tendências de hype.  
O fluxo foi criado no **n8n**, uma ferramenta de automação de código aberto que permite integrar serviços e bancos de dados de forma visual e simples.

---

## 📁 Conteúdo do Repositório

- `hypex.json` → Arquivo de fluxo exportado do n8n.  
  Ele contém toda a automação pronta para ser importada diretamente na sua instância do n8n.

---

## ⚙️ Como Usar

1. Baixe o arquivo **`hypex.json`** deste repositório.  
2. Acesse sua instância do **n8n**.  
3. Vá até **Import > Import from File** e selecione o arquivo.  
4. Configure as **credenciais da API do YouTube** dentro do n8n.  
5. **Conecte o fluxo ao seu próprio banco de dados**, ajustando os nós correspondentes (PostgreSQL, MongoDB ou outro que preferir).  
6. Execute o fluxo e veja os dados sendo coletados automaticamente.

---

## 🗃️ Requisitos

- Conta configurada na **API do YouTube**  
- Instância do **n8n** (local ou na nuvem)  
- Acesso a um **banco de dados próprio** (ex: PostgreSQL ou MongoDB)

---

## 💡 Observação

O fluxo foi projetado para ser facilmente adaptável.  
Você pode alterar, adicionar ou remover nós conforme suas necessidades e o tipo de análise que deseja realizar.
