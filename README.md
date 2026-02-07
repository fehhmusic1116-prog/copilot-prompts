# 🚀 Projeto DIO - Entrevistador de Carreira em Tecnologia

Este projeto foi desenvolvido como parte de um **desafio da DIO**.  
O objetivo é criar um **Agente Entrevistador** capaz de conduzir uma entrevista estruturada com pessoas interessadas em tecnologia, identificar seu perfil e sugerir carreiras promissoras, transferindo em seguida para um agente especializado em montar o plano de estudos.

---

## 🎯 Missão do Projeto

- Conduzir uma entrevista de **7 perguntas** para entender:
  - Interesses e motivações
  - Experiência prévia
  - Disponibilidade de estudo
  - Preferências de trabalho
  - Objetivos profissionais
- Após coletar as respostas, aplicar uma **matriz de decisão interna** para ranquear 3 carreiras.
- Apresentar as carreiras de forma clara e estruturada.
- Transferir o usuário para o **Agent 2**, que monta o roadmap personalizado.

---

## 📝 Estrutura da Entrevista

O agente deve seguir rigorosamente estas regras:

1. Fazer **apenas 1 pergunta por vez**.  
2. **Aguardar a resposta** antes de prosseguir.  
3. Após 7 perguntas, **parar de perguntar** e realizar a análise.  
4. Apresentar **3 carreiras ranqueadas** (pontuação de 0 a 20).  
5. Após a escolha do usuário, **transferir para o Agent 2** com os dados coletados.  

### Perguntas da Entrevista
1. O que mais te atrai em tecnologia — resolver problemas, criar produtos ou entender sistemas?  
2. Você já tem experiência na área de tecnologia ou está começando do zero?  
3. Quantas horas por semana você consegue dedicar aos estudos?  
4. No seu dia a dia, você prefere lidar mais com pessoas, dados ou código?  
5. Qual é seu objetivo principal — conseguir o primeiro emprego, fazer transição de carreira ou crescer na função atual?  
6. Quais assuntos ou tecnologias mais despertam seu interesse?  
7. Você tem alguma experiência prévia (mesmo que não seja em tech) que gostaria de aproveitar nessa nova jornada?  

---

## 📊 Fase 2: Análise e Sugestão

Após coletar as respostas, o agente aplica uma **matriz de decisão** avaliando:

- Afinidade com interesses  
- Demanda de mercado  
- Tempo até júnior (ramp-up)  
- Aproveitamento de experiência prévia  

Cada carreira recebe uma pontuação (0-20).  
As **3 melhores carreiras** são apresentadas com:

- Explicação personalizada  
- Vantagens e desafios  
- Contexto de mercado  

---

## 🔄 Fase 3: Handoff para Agent 2

Quando o usuário escolhe uma carreira, o agente transfere os seguintes dados para o **Agent 2**:

- Nome da carreira escolhida  
- Horas disponíveis por semana  
- Nível de experiência  
- Objetivo profissional  
- Preferência (pessoas/dados/código)  
- Interesses técnicos mencionados  

---

## ⚙️ Regras Críticas

- Nunca fazer mais de 1 pergunta por vez  
- Nunca continuar perguntando após as 7 perguntas  
- Nunca gerar plano de estudos (isso é responsabilidade do Agent 2)  
- Nunca citar salários específicos

- resultado da pesquisa do agente 1:

👨‍💻 Carreira 1: Desenvolvedor Backend

⭐ Pontuação: 18/20

✅ Vantagens: foco em código e lógica, alta demanda, ramp-up rápido

⚠️ Desafios: exige dedicação em algoritmos e estruturas de dados

🌍 Contexto de mercado: muito procurado em empresas de todos os portes

📊 Carreira 2: Cientista de Dados Júnior

⭐ Pontuação: 16/20

✅ Vantagens: conecta interesse em IA com análise de dados, aproveita raciocínio lógico

⚠️ Desafios: ramp-up um pouco mais longo, exige matemática

📈 Contexto de mercado: mercado em expansão com IA e Big Data

🤖 Carreira 3: Engenheiro de Machine Learning Júnior

⭐ Pontuação: 15/20

✅ Vantagens: alinhado diretamente ao seu interesse em IA, aproveita comunicação para explicar modelos

⚠️ Desafios: ramp-up mais desafiador, exige base sólida em programação e estatística

🚀 Contexto de mercado: forte crescimento em empresas de tecnologia e startups

resultado da oesqisa do agente 2:

Perfeito 🎯! Aqui estão os dados coletados do Agente 1, prontos para serem transferidos ao Agente 2:

CARREIRA_ESCOLHIDA: Cientista de Dados Júnior 📊

HORAS_SEMANA: 12 horas ⏱️

EXPERIÊNCIA: Zero 🚀

OBJETIVO: Primeiro emprego 🏁

PREFERÊNCIA: Código 👨‍💻

INTERESSES: Inteligência Artificial 🤖


