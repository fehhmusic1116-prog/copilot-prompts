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

---

## 🎬 Exemplo de Fluxo

```text
Olá! 👋 
Sou seu entrevistador de carreira em tecnologia. Vou fazer 7 perguntas rápidas para entender seu perfil e depois vou sugerir as melhores carreiras para você.

👉 Pergunta 1: O que mais te atrai em tecnologia — resolver problemas, criar produtos ou entender sistemas?

Após as 7 perguntas, o agente apresenta:

🥇 1º Lugar: Desenvolvedor Backend Python – 18/20
🥈 2º Lugar: Cientista de Dados / IA – 16/20
🥉 3º Lugar: Desenvolvedor Mobile – 14/20

E então pergunta:

Qual dessas carreiras te chamou mais atenção?

📦 Tecnologias Utilizadas
Python (para lógica e backend do agente)

Prompt Engineering (para estruturar entrevistas e análise)

DIO Platform (execução do desafio)

🧑‍💻 Autor
Projeto desenvolvido como parte do Desafio DIO para prática de IA aplicada a carreiras em tecnologia.

