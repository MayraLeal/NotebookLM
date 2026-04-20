# Miniguia de Estudos - n8n

## Contexto e Objetivos

Neste caderno temático, escolhi explorar o **n8n**, uma ferramenta de automação de fluxo de trabalho. O objetivo deste projeto é entender melhor o que é o n8n, suas características únicas e como configurar um fluxo de trabalho básico. Com isso, espero adquirir habilidades práticas em automação e integração de APIs.

## Curadoria de Fontes

Aqui estão as fontes que selecionei para este projeto:

1. **[Fonte 1](https://www.youtube.com/watch?v=Eaf1UxvGmlE)** 
2. **[Fonte 2](https://www.youtube.com/watch?v=2MkbZj8w4AI&t=57s)**
3. **[Fonte 3](https://www.youtube.com/watch?v=2MkbZj8w4AI)**
4. **[Fonte 4](https://www.youtube.com/watch?v=Eaf1UxvGmlE&t=366s)**
5. **[Fonte 5](https://www.youtube.com/watch?v=-Ka4YKW7RwM)**

## Engenharia de Prompts e "Cicatrizes"

Durante o desenvolvimento deste projeto, elaborei as seguintes perguntas:

- **Pergunta 1**: O que é o n8n e como ele se diferencia de outras ferramentas de automação?

**Resposta obtida:** 
  
O n8n é uma das principais ferramentas de automação e integração de sistemas disponíveis atualmente, ganhando destaque por sua interface visual "no-code" (sem necessidade de programação) que utiliza blocos chamados de nodes (nódulos) para criar fluxos de trabalho. 

Ele permite que diferentes aplicações, que antes não se comunicavam, troquem informações de forma automatizada e eficiente.
  As principais diferenças que o destacam de concorrentes como Zapier e Make incluem:Poder em Inteligência Artificial: O n8n se diferencia drasticamente por suas funções avançadas de IA, possuindo integrações nativas que facilitam a criação de agentes autônomos e fluxos complexos com modelos de linguagem (LLMs) como GPT-4 e Gemini.
  - Modelo Self-Hosted: Diferente de outras ferramentas totalmente em nuvem, o n8n fornece seu código-fonte, permitindo que você o instale em seus próprios servidores ou máquina local. Isso oferece maior privacidade de dados e pode eliminar custos de assinatura mensal, já que você paga apenas pela sua infraestrutura.
  - Flexibilidade Técnica: Embora seja "no-code", ele é considerado uma ferramenta mais técnica e robusta, permitindo personalizações profundas através de APIs e Webhooks, o que atrai tanto iniciantes quanto desenvolvedores.
  - Mais de 400 Integrações: A ferramenta já vem com centenas de conexões pré-prontas (como Google Sheets, WhatsApp e e-mail), facilitando a montagem rápida de automações comuns.
  
  Em resumo, enquanto ferramentas tradicionais focam em simplicidade na nuvem, o n8n foca em flexibilidade, economia e integração profunda com IA.

- **Pergunta 2**: Como configurar um fluxo de trabalho básico no n8n?

**Resposta obtida:** 

Configurar um fluxo de trabalho básico no n8n envolve conectar uma série de etapas que juntas realizam uma tarefa automatizada. 
O processo consiste essencialmente em definir um ponto de partida (gatilho) e as ações subsequentes que a ferramenta deve executar.Aqui está o passo a passo para criar um fluxo simples:
1. **Acesse a Interface e Crie um Novo Fluxo:** 
   - Ao abrir o n8n, você verá uma tela em branco (o canvas) onde poderá adicionar itens e criar conexões de forma visual.
2. **Escolha o Gatilho (Trigger):** 
   - Todo fluxo precisa de um começo. O gatilho define quando a automação será iniciada.
- Exemplos de gatilhos:O recebimento de uma mensagem no WhatsApp , a chegada de um e-mail, ou um agendamento de horário específico. 
3. **Adicione e Configure os Nódulos (Nodes):** 
   - Nódulos são os blocos que representam as ações no fluxo.
   - Após o gatilho, você adiciona um nódulo clicando no botão "+" e selecionando a aplicação desejada.
   - Configuração: Em cada nódulo, você deve definir o que ele fará, como "Adicionar uma linha em uma planilha do Google" ou "Enviar uma resposta via WhatsApp".
4. **Conecte os Nódulos:**
   - Desenhe linhas ligando o gatilho aos nódulos de ação para estabelecer a ordem de execução.
   - As informações capturadas no gatilho podem ser passadas para os nódulos seguintes (por exemplo, pegar o nome de quem enviou o e-mail e usá-lo na resposta).
5. **Teste e Ative o Fluxo:** 
   - Você pode executar o fluxo manualmente para testar se tudo está funcionando como esperado.
   - Uma vez validado, basta ativar o fluxo para que ele passe a rodar de forma automática sempre que o gatilho for acionado.
  
**Dica de Fluxo Simples:** Um exemplo comum para iniciantes é integrar o WhatsApp ao Google Sheets, onde cada mensagem recebida gera automaticamente uma nova linha em uma planilha para registro de leads ou atendimentos.

## Miniguia de Estudo (Entrega Final)

### Resumos Estruturados

 **O que é o n8n**: O n8n é uma ferramenta de automação de fluxo de trabalho que permite a integração de diferentes aplicações através de uma interface visual.

 **Diferenciação em Relação a Outras Ferramentas**: O n8n se destaca pela flexibilidade, possibilidade de auto-hospedagem e capacidades avançadas de IA.

 **Configuração de Fluxos**: O processo de configuração de um fluxo de trabalho básico envolve a escolha de gatilhos e nódulos, conectando-os para executar tarefas automatizadas.

### Glossário

- **n8n**: Ferramenta de automação de fluxo de trabalho.
- **Nodes (Nódulos)**: Blocos que representam ações dentro de um fluxo de trabalho.
- **Gatilho (Trigger)**: Evento que inicia um fluxo de trabalho.

### Conjunto de Prompts Reutilizáveis

1. **Prompt 1**: Como o n8n pode ser utilizado para integrar diferentes APIs?
2. **Prompt 2**: Quais são as melhores práticas para gerenciar fluxos de trabalho no n8n?
3. **Prompt 3**: Como lidar com erros em fluxos de trabalho no n8n?

---

## Conclusão

Este projeto não só me ajudou a aprofundar meu conhecimento sobre o **n8n**, mas também a desenvolver habilidades de curadoria de conteúdo e engenharia de prompts. Espero que este miniguia sirva como um recurso útil para futuros estudos!

