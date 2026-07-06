# 🎯 Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

## 📌 Introdução

Este repositório apresenta minha participação no **Desafio Criativo da DIO**, cujo objetivo foi extrair insights de feedbacks de clientes bancários com apoio da inteligência artificial. O tema escolhido foi **Relacionamento e Fidelização de Clientes Bancários**, por sua relevância estratégica na retenção de clientes e na recomendação da instituição para terceiros. O desafio propôs a construção de um prompt estruturado, capaz de orientar a IA a analisar dados e gerar resultados úteis para apoiar decisões de negócio.

---

## 🧩 Desenvolvimento do Desafio

1. **Definição do tema da análise** Escolhi trabalhar com a temática de relacionamento e fidelização, por ser um aspecto central para bancos e clientes.

2. **Criação da base de dados fictícia** Solicitei à IA (Microsoft Copilot) a geração de um conjunto de feedbacks simulados, contendo: comentário, data, canal, produto e nota de satisfação.

3. **Estruturação do prompt** Segui o modelo proposto pelo desafio da DIO, definindo contexto, critérios de análise e restrições para orientar a IA na análise dos dados.

4. **Análise dos feedbacks** A IA classificou os comentários por temas, sentimentos, urgência, canal, experiência do cliente e probabilidade de fidelização/indicação.

---

## 📊 Resultados Obtidos

* ### Prompt construído conforme modelo proposto no desafio:

Quero que a IA analise comentários dos clientes acerca da sua satisfação com os serviços oferecidos pela instituição bancária para identificar o grau de relacionamento cliente/banco e a probabilidade de fidelidade e indicação do banco para terceiros.


O resultado será usado por uma equipe de produtos serviços para apoiar o incremento da fidelização de clientes.


A entrega deve conter resumo executivo de no máximo 5 linhas, tabelas com os principais motivos de fidelização e de não fidelização com seu grau de importância e exemplos, lista de insights e recomendações práticas.


O resultado será considerado bom se for claro, organizado, baseado nos comentários fornecidos e útil para promover ações.


Contexto: Estou trabalhando com feedbacks de clientes bancários relacionados a satisfação do cliente e a probabilidade de fidelização desses clientes.


Dados disponíveis: A base contém a data do comentário, canal de atendimento, texto do feedback, produto citado e nota de satisfação.


Critérios de análise: A IA deve classificar os feedbacks por temas, sentimento, urgência, canal, experiência do cliente e a probabilidade desse cliente se fidelizar ao banco e indicá-lo para terceiros (utilize a seguinte escala probabilidade: Alta, Moderada, Baixa e Nula).

Identifique os principais padrões, problemas, elogios e oportunidades.

Aponte evidências nos dados fornecidos.

Sugira ações práticas para a equipe de produtos e serviços.


Cuidados e restrições: Use apenas os dados fornecidos; não invente números, causas ou conclusões; não exponha dados pessoais ou sensíveis; se houver informação insuficiente, indique a limitação; e use linguagem direta e de fácil compreensão para tomar decisões, porém mantenha a formalidade.


Banco de dados:

| Comentário do Cliente | Data | Canal | Produto | Nota de Satisfação | 
| --- | --- | --- | --- | --- | 
| "Gosto muito do atendimento no chat do app, sempre rápido e educado. Isso me faz confiar mais no banco." | 12/05/2026 | App do Banco | Atendimento Digital | 9 | 
| "Participo do programa de pontos, mas acho que as opções de resgate são limitadas. Gostaria de mais benefícios exclusivos." | 28/04/2026 | Reclame Aqui | Programa de Fidelidade | 6 | 
| "Recebi uma ligação de acompanhamento após abrir minha conta, achei atencioso e me senti valorizado." | 03/06/2026 | Telefone | Conta Corrente | 10 | 
| "O banco oferece promoções para novos clientes, mas quem já é fiel há anos não recebe vantagens. Isso desanima." | 19/05/2026 | Redes Sociais (Twitter) | Conta Corrente | 5 | 
| "Adoro os eventos exclusivos para clientes premium, me sinto parte de uma comunidade especial." | 25/06/2026 | App do Banco | Cartão Platinum | 8 | 
| "O atendimento da ouvidoria resolveu meu problema com rapidez e ainda me deram um bônus de pontos. Excelente!" | 30/06/2026 | Ouvidoria | Programa de Pontos | 9 | 

* ### Resposta da IA

### 📌 Resumo Executivo

Os feedbacks analisados mostram que clientes valorizam atendimento ágil e personalizado, mas apontam limitações em programas de fidelidade e benefícios para clientes antigos. A probabilidade de fidelização é alta quando há reconhecimento e exclusividade, e moderada ou baixa quando há percepção de desigualdade entre novos e antigos clientes. O banco tem oportunidades claras de fortalecer a confiança e ampliar benefícios para manter clientes fiéis e incentivar recomendações.

### 🔑 Principais motivos de fidelização

| Motivo | Grau de Importância | Exemplo | 
| --- | --- | --- | 
| Atendimento rápido e educado | Alto | "Gosto muito do atendimento no chat do app, sempre rápido e educado." | 
| Reconhecimento e atenção personalizada | Alto | "Recebi uma ligação de acompanhamento após abrir minha conta, achei atencioso." | 
| Benefícios exclusivos para clientes premium | Moderado | "Adoro os eventos exclusivos para clientes premium." | 
| Resolução eficiente de problemas | Alto | "A ouvidoria resolveu meu problema com rapidez e ainda me deram um bônus." | 

### 🚫 Principais motivos de não fidelização

| Motivo | Grau de Importância | Exemplo | 
| --- | --- | --- | 
| Falta de benefícios para clientes antigos | Alto | "O banco oferece promoções para novos clientes, mas quem já é fiel não recebe vantagens." | 
| Limitação nas opções de resgate de pontos | Moderado | "As opções de resgate são limitadas, gostaria de mais benefícios exclusivos." | 

### 📊 Insights extraídos

* **Sentimento predominante:** Positivo em relação ao atendimento e exclusividade; negativo em relação à falta de reconhecimento de clientes antigos.

* **Urgência:** Alta para revisar políticas de fidelização e benefícios, pois impactam diretamente a retenção.

* **Canais mais relevantes:** App do banco e ouvidoria geram feedbacks positivos; redes sociais e Reclame Aqui concentram críticas.

* **Probabilidade de fidelização:**

  * Alta: Atendimento digital, ouvidoria, acompanhamento personalizado.

  * Moderada: Programa de pontos com limitações.

  * Baixa: Promoções voltadas apenas a novos clientes.

### ✅ Recomendações práticas

* **Expandir benefícios do programa de pontos**, incluindo mais opções de resgate e vantagens exclusivas.

* **Criar campanhas específicas para clientes antigos**, valorizando sua fidelidade com bônus ou condições diferenciadas.

* **Manter e ampliar ações de atendimento personalizado**, como ligações de acompanhamento e chat ágil.

* **Reforçar comunicação positiva nos canais digitais**, destacando casos de resolução eficiente e benefícios exclusivos.

* **Monitorar redes sociais e Reclame Aqui** para agir rapidamente em críticas e transformar insatisfações em oportunidades de fidelização.

---

## ✅ Conclusão

O desafio demonstrou como o uso de IA pode apoiar equipes de produtos e serviços na análise de feedbacks, transformando dados em **insights acionáveis**. A temática de relacionamento e fidelização evidenciou oportunidades estratégicas para bancos, como ampliar benefícios, reconhecer clientes antigos e reforçar o atendimento personalizado. A experiência reforça a importância de prompts bem estruturados para extrair valor real dos dados e apoiar decisões de negócio de forma clara e objetiva.
