# Imersao-Alura-com-GoogleGemini
Desafio proposto pela Imersão da Alura junto com o Google Gemini, consiste na criação de agentes de Inteligencia Artificial (auxilio do gemini).
Este projeto nasceu da vontade de resolver uma dor real enfrentada por muitas empresas: um processo de onboarding mal estruturado. Apesar de subestimado, o onboarding tem um grande potencial de agregar valor quando bem conduzido.
Com base no que aprendi durante a Imersão Alura, desenvolvi uma solução voltada especialmente para pequenas e médias empresas: um assistente inteligente que torna o onboarding mais acessível, ágil e eficiente.

> 📎 [Clique aqui para visualizar o PDF de exemplo de onboarding](./ONBOARDING-TESTE.pdf)



# 🤖 Assistente de Onboarding com IA 

O funcionamento é simples: a empresa fornece um único PDF contendo as informações relevantes sobre sua cultura, estrutura e processos. A partir desse arquivo, o assistente utiliza inteligência artificial para dar suporte ao novo colaborador por meio de dois agentes:

Um agente de boas-vindas, que guia o início da jornada de forma acolhedora.

Um agente tira-dúvidas, que responde às perguntas do colaborador com base no conteúdo do PDF, sem que ele precise buscar manualmente em documentos extensos.

O **objetivo** é que o novo funcionário tenha acesso rápido e fluido às informações que precisa, sem se sentir perdido nos primeiros dias.

Este projeto é uma proposta de inovação para **empresas de pequeno e médio porte** que desejam tornar o processo de integração de novos colaboradores mais **eficiente, acolhedor e automatizado**, mesmo sem um setor de RH estruturado.


---

## 📄 O que é?

Um **assistente virtual de onboarding** que lê um **documento PDF fornecido pela empresa**, contendo informações essenciais para os novos colaboradores.  
Com base nesse conteúdo, o assistente é capaz de:

- Dar as boas-vindas e orientar o colaborador
- Responder dúvidas frequentes de forma contextualizada e personalizada

> ⚠️ O PDF utilizado neste protótipo é fictício. Em um uso real, a própria empresa irá fornecer seu documento com cultura, processos, ferramentas e contatos reais — que serão a base da interação do assistente.

---

## 🧠 Como funciona?

1. A empresa envia um PDF com as informações de onboarding.
2. O assistente processa o conteúdo do PDF.
3. O novo colaborador interage com o assistente via chat e tira dúvidas em linguagem natural.

---

## 🤖 Os dois agentes

- **Agente 1 – Boas-vindas**:  
  Recebe o colaborador, apresenta a empresa e explica como a integração vai funcionar.

- **Agente 2 – Tira-Dúvidas**:  
  Responde perguntas baseadas **somente no conteúdo do PDF** enviado pela empresa.

---

## ✅ Problemas que resolve

- Integração inconsistente em empresas menores  
- Falta de clareza sobre ferramentas, pessoas e processos  
- Dificuldade em transmitir a cultura organizacional  
- Carga operacional de RH (quando existe)

---

## 🚀 Visão de Futuro

Este projeto pode evoluir para:

- Um ciclo de 90 dias de onboarding com feedbacks periódicos  
- Armazenamento de interações para análise posterior  
- Acesso via link ou painel web com login seguro  
- Integração com trilhas de conhecimento e FAQs

---

## 🛠️ Tecnologias utilizadas

- Python + Google Colab (prototipação)
- Gemini 2.0 Flash (via LangChain)
- `PyPDF` para leitura de PDF
- Interface via `IPython.display`

---

## ❗ Sobre o acesso do colaborador

Atualmente, o projeto roda no **Google Colab** por ser um ambiente ideal para testes com IA.  
**O foco foi demonstrar o potencial funcional da IA no onboarding.**

> 💡 Em um cenário real, o chatbot será integrado em uma **interface web acessível** para que qualquer colaborador possa usar facilmente, sem depender do Colab.

---

## 💬 Exemplos de perguntas respondidas

- “Quem é meu líder direto?”
- “Como funciona o reembolso?”
- “Qual sistema usamos para ponto eletrônico?”
- “Com quem falo sobre treinamentos?”

---

## ✨ Conclusão

Este projeto mostra como a IA generativa pode ser **acessível, útil e prática** para resolver **problemas reais** no dia a dia das empresas.

Ele é simples, adaptável e tem grande potencial de impacto — principalmente para empresas que não têm uma estrutura robusta de RH.

---

