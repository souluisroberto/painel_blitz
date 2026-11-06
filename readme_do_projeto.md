# Painel Operacional CD 📊

Sistema web desenvolvido para otimizar, controlar e auditar a conferência de pedidos e metas diárias em Centros de Distribuição (CD).

---

## 🚀 Sobre o Projeto

O **Painel Operacional CD** foi criado para substituir processos manuais e planilhas desconexas, permitindo que os operadores e gestores façam a importação rápida de arquivos XML operacionais, acompanhem o andamento das rotas, controlem a quantidade auditada no dia, visualizem o status de conferência por cores e monitorem o atingimento da meta em tempo real.

---

## ✨ Principais Funcionalidades

- **Importação de Arquivos XML:** Suporte a múltiplos arquivos (`BD_XML`) para leitura automática de pedidos e dados de pulmão.
- **Integração com Nuvem (`BD_NUVEM`):** Acesso rápido aos links de relatórios oficiais diretamente pelo modal integrado.
- **Controle de Metas Dinâmico:** Meta diária configurável com disparo de comemoração visual ao atingir ou superar o objetivo.
- **Tabela de Acompanhamento Principal:** Exibição detalhada por Rota, Filial, Pulmão, Volumoso, Fraldas, Linha e Total, com coloração baseada na frequência de conferências.
- **Tabela de Auditoria Diária:** Registro em tempo real das filiais inseridas e conferidas no dia.
- **Painel Administrativo Restrito:** Acessado facilmente digitando a palavra secreta **`luis`** em qualquer lugar da tela, contendo:
  - Alteração da meta diária.
  - Botão para marcar todas as filiais como conferidas.
  - Exportação de relatório em formato JSON.
  - Limpeza e reset de dados do sistema.
  - Acesso à função de limpeza de dados e status do modo de exibição.
- **Persistência de Dados Local (`localStorage`):** Histórico mensal de conferências salvo de forma segura no navegador, garantindo que os dados não sejam perdidos ao fechar a aba.

---

## 🔒 Segurança e Privacidade

- **Processamento Local (Client-Side):** Todos os dados e arquivos XML são processados exclusivamente dentro do navegador do usuário. Nenhuma informação operacional é enviada para servidores externos, garantindo sigilo e segurança total dos dados.

---

## 💻 Como Usar

1. Abra o arquivo principal do sistema (`.html`) em qualquer navegador moderno (Google Chrome, Microsoft Edge, etc.).
2. Clique no botão **`BD_XML`** para carregar os arquivos XML do dia ou utilize **`BD_NUVEM`** se necessário.
3. Acompanhe a tabela principal com as rotas e filiais carregadas.
4. Utilize o campo **"Nº da Filial"** no painel lateral para inserir ou remover as filiais auditadas no dia.
5. Para acessar configurações avançadas (como alterar a meta ou exportar dados), digite **`luis`** no teclado.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & JavaScript Puro (Vanilla):** Lógica rápida, leve e sem dependências complexas de instalação.
- **Tailwind CSS:** Framework utilitário para um design moderno, responsivo e de alto padrão corporativo.
- **Canvas Confetti:** Animação festiva para o atingimento de metas.

---

## 👨‍💻 Autor

Desenvolvido por **Luis Roberto Dos Anjos Braga** para a gestão e eficiência operacional de Centros de Distribuição.