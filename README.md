# 💸 App de Organização de Finanças FinanceAI

- Seu **prompt final** (PRD);
```markdown
📄 PRD Revisado: App de Finanças Pessoais Conversacional (MVP)Instruções para o Lovable / AI: Utilize este documento como especificação do produto para construir uma interface moderna, amigável e funcional voltada para um MVP de gestão financeira baseada em IA e chat.
🎯 1. Visão Geral do ProdutoNome Sugerido: FinanceAI / ConversaFinanceiraObjetivo: Permitir que iniciantes controlem suas finanças apenas conversando, sem preencher formulários longos ou planilhas complexas.Proposta de Valor: "Controle financeiro simples como mandar uma mensagem no WhatsApp."
👤 2. Público-Alvo e DoresPúblico: Pessoas que desejam ter controle financeiro, mas desistem por falta de tempo ou pela complexidade dos aplicativos tradicionais (foco em iniciantes).Principal Dor: Entrada manual exaustiva de dados e falta de recomendações acionáveis.
🚀 3. Funcionalidades do MVPChat Financeiro com Linguagem Natural:O usuário digita ou grava voz: "Gastei R$ 45 no almoço" ou "Recebi R$ 2500 de salário".A IA interpreta o valor, o tipo (receita/despesa) e a descrição.Categorização Automática:Classificação automática em categorias como Alimentação, Transporte, Lazer, Moradia, Salário.Confirmação rápida no chat (ex: "Registrado em Alimentação 🍲. Correto?").Metas Financeiras Simples:Definição de limites mensais por categoria ou metas gerais (ex: "Quero guardar R$ 300 este mês").Barra de progresso visual no painel.Agente Financeiro (Dicas de Economia):Recomendações e insights automáticos gerados pela IA no chat (ex: "Você já gastou 80% do seu orçamento de Restaurantes este mês!").Dashboard / Relatórios Simplificados:Visão geral rápida com: Saldo Atual, Gastos do Mês, Gráfico de Categorias e Progresso das Metas.
🖥️ 4. Estrutura de Telas (UX/UI)Tela 1: Conversa (Tela Principal)Interface estilo chat (mensagens do usuário e respostas do Agente Financeiro).Campo de texto fixo no rodape com botão de envio e ícone de atalhos rápidos (ex: "Registrar gasto", "Ver saldo", "Pedir dica").Tela 2: Visão Geral (Dashboard)Resumo financeiro em cards (Entradas, Saídas, Saldo).Gráfico simples em pizza/rosca dos gastos por categoria.Lista das últimas transações com opção de edição rápida.Tela 3: Metas & DicasCards com as metas ativas e barra de progresso.Feed de Dicas do Agente Financeiro acumuladas ao longo do mês.🛠️
 5. Requisitos Técnicos & Integrações (Lovable)Frontend: Interface fluida, moderna, limpa (estilo Neumorphism ou minimalista), responsiva para mobile.Backend / LLM: Integração com modelo de IA (OpenAI GPT / Claude) para processar os prompts de linguagem natural em JSON estruturado { valor, categoria, tipo, data, descricao }.Banco de Dados: Tabelas de Users, Transactions, Categories e Goals.📋
6. Plano de Validação Inicial (Roadmap do MVP)EtapaAçãoCritério de Sucesso1. PrototipagemGerar as 3 telas principais no Lovable.Interface funcional e navegável.2. Teste de InputSimular 20 frases diferentes de gastos/receitas no chat.IA acertar valor e categoria em >90% dos casos.3. Teste com UsuáriosConvidar 5-10 iniciantes para usar por 7 dias.Registrar pelo menos 3 transações por dia sem abandonar o app.
```
- Prints ou pequenos vídeos das interações com a IA;
 <img width="802" height="511" alt="image" src="https://github.com/user-attachments/assets/61f2382c-ddb5-40ed-a4b1-613dbc1ce3d8" />
<img width="828" height="755" alt="image" src="https://github.com/user-attachments/assets/550bc8f3-874d-4ace-921a-c628f29645cd" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
  Aqui está um resumo bem direto e visual das **funcionalidades do MVP**, perfeito para consulta rápida ou apresentação do projeto:
### 💬 1. Chat e Registro Conversacional

* **Entrada em Linguagem Natural:** O usuário registra entradas e saídas digitando ou enviando áudio no estilo WhatsApp (ex: *"Gastei R$ 45 no almoço"*).
* **Processamento por IA:** A IA extrai automaticamente valor, tipo (despesa/receita) e descrição, eliminando a digitação manual de formulários.
### 🏷️ 2. Categorização Inteligente
* **Autoclassificação:** Atribuição automática de categorias (*Alimentação, Transporte, Moradia, Lazer, etc.*).
* **Validação Expressa:** Mensagem rápida de confirmação no chat para ajustes imediatos se necessário.
### 🎯 3. Metas e Limites de Gastos

* **Definição Flexível:** Criação de metas gerais ou orçamentos por categoria (ex: *"Limitar Restaurantes a R$ 500/mês"*).
* **Acompanhamento Visual:** Barras de progresso e status em tempo real.


### 🤖 4. Agente Financeiro (Consultor IA)

* **Alertas Proativos:** Avisos automáticos sobre uso do orçamento (ex: *"Você já gastou 80% da sua meta de lazer"*).
* **Dicas Personalizadas:** Recomendações educacionais de economia com base nos hábitos do usuário.

---

### 📊 5. Dashboard Simplificado

* **Resumo Financeiro:** Cards com Entradas, Saídas e Saldo Atual.
* **Visualização Gráfica:** Gráfico de pizza/rosca para divisão de gastos por categoria.
* **Histórico:** Lista das últimas transações com atalhos para edição rápida.
- Uma breve **reflexão sobre o processo**:
  
