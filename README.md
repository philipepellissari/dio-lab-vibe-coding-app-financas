# 💸 App de Organização de Finanças Pessoais do Philipe com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

-Crie a primeira versão (MVP) de um aplicativo web de Finanças Pessoais Conversacionais, com foco em simplicidade e Design Universal.

# 1. Visão Geral e Estética
- Interface moderna, limpa e responsiva (mobile e desktop).
- Estilo visual inspirado no Notion/Vercel, com suporte nativo a temas escuro e claro de alto contraste.
- Siga rigorosamente os princípios de Design Universal: alta legibilidade de fontes, áreas de clique/toque amplas (mínimo 44x44px), navegação completa por teclado, suporte a leitores de tela (ARIA labels) e visualização de dados com rótulos textuais claros além das cores (para total acessibilidade a daltônicos).

# 2. Estrutura da Página e Layout
Crie um layout principal dividido em duas seções interativas:
- Lado Esquerdo (ou Topo em telas menores): Dashboard Resumido e Histórico.
- Lado Direito (ou Painel Lateral): Chat Inteligente de Transações.

# 3. Componentes e Funcionalidades do MVP

## A. Dashboard Resumido
- Três cards principais no topo: Saldo Atual, Gastos do Mês (Despesas) e Total Guardado/Economias.
- Gráfico visual simples de distribuição de gastos por categoria. Use cores contrastantes acompanhadas de ícones e rótulos explícitos com porcentagem e valor (ex: "Alimentação: R$ 450,00 - 35%").

## B. Widget de Chat Conversacional
- Interface de chat amigável com campo de entrada de texto e botão de envio claro.
- Mensagem de boas-vindas inicial explicando o uso com exemplos visuais clicáveis (ex: "Gastei 45 reais em almoço").
- Simulação de leitura de linguagem natural: quando o usuário enviar uma mensagem como "Gastei 30 no Uber", o chat deve responder confirmando a transação ("Registrado: R$ 30,00 em Transporte") e atualizar instantaneamente o Saldo, o Gráfico e a Tabela de Transações.
- Tolerância ao erro: se a entrada for ambígua, o chat deve solicitar confirmação educadamente com botões de resposta rápida.

## C. Lista de Transações Recentes
- Tabela/lista interativa logo abaixo dos cards de resumo com as últimas transações.
- Cada item deve exibir: ícone da categoria, nome da transação, categoria, valor e data.
- Botões acessíveis para editar ou excluir transações individualmente.

## D. Agente de Insights (Painel de Dicas)
- Um card destacado contendo sugestões simples de economia geradas com base no histórico simulado (ex: "Dica: Você gastou 25% a mais em delivery esta semana em comparação com a semana passada").

# 4. Dados Iniciais
- Preencha o aplicativo com dados fictícios (mock data) de 4 a 5 transações iniciais para que a interface não fique vazia na primeira renderização.    
- ## Funcionalidades do Aplicativo (MVP - Prosa Finanças)

### 1. Assistente de Transações (Chat Conversacional)
- **Registro em Linguagem Natural:** Permite adicionar receitas, despesas e economias digitando frases simples do dia a dia (ex: "Gastei 45 reais em almoço", "Gastei 30 no Uber", "Recebi 1.200 de freela").
- **Sugestões Rápidas (Chips de Exemplo):** Apresenta exemplos interativos prontos para guiar o usuário de forma intuitiva.
- **Atualização Reativa:** Ao enviar uma mensagem, o sistema extrai o valor, a categoria e a data, atualizando automaticamente o dashboard e a lista de lançamentos.

### 2. Dashboard Resumido
- **Cards de Métricas Principais:**
  - **Saldo Atual:** Exibe o valor líquido consolidado (Receitas menos despesas e valores guardados).
  - **Gastos do Mês:** Destaque para o total de despesas acumuladas no mês vigente.
  - **Total Guardado:** Acompanhamento de reservas financeiras e a porcentagem correspondente da renda mensal.
- **Gráfico de Gastos por Categoria:** Gráfico em rosca com alto contraste visual, integrando rótulos textuais explicativos e porcentagens para garantir total acessibilidade.

### 3. Gestão e Histórico de Transações
- **Lista Interativa de Transações:** Exibição clara de todos os lançamentos com ícones por categoria, descrição, valor com código de cores (verde para entradas, vermelho para saídas) e data.
- **Ações Rápidas:** Botões acessíveis para editar ou excluir transações individualmente de maneira simples.

### 4. Agente de Insights (Painel de Dicas Inteligentes)
- **Alertas de Consumo:** Notificações automáticas sobre aumentos atípicos de gastos em categorias específicas (ex: despesas com delivery).
- **Dicas de Economia Personalizadas:** Recomendações didáticas baseadas no maior volume de despesas para auxiliar no corte de gastos desnecessários.
- **Acompanhamento de Metas:** Sugestões práticas para alcançar metas percentuais de economia mensal com base na renda.

### 5. Design Universal e Acessibilidade
- **Interface Limpa e Alto Contraste:** Visual moderno com tipografia de alta legibilidade e suporte a temas (claro/escuro).
- **Navegação Flexível:** Áreas de clique e toque amplas, preparadas para navegação via teclado e suporte a leitores de tela.
- **Comunicação Multimodal:** Informações apresentadas através de texto, ícones, números e cores de forma complementar.
```[cite: 1, 2]
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem? O chatbot me ajudou a montar os prompts para eu colocar no lovable
  - O que não funcionou como o esperado?  interações limitadas no lovable
  - O que aprendeu sobre conversar com IAs? A Ia é muito útil quando você sabe pedir para ela

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
