# DevOps Documentation: Humanized by AI 🤖

## 📒 Descrição
Este projeto explora a capacidade das IAs Generativas de criar documentação técnica para Kubernetes e AWS com um tom de voz "senior developer", fugindo da linguagem robótica padrão. O objetivo é testar se a IA consegue explicar conceitos complexos de infraestrutura como um humano (Natty).

## 🤖 Tecnologias Utilizadas
* **Amazon Bedrock** (Modelo: Claude 3 ou Titan Text)
* **Prompt Engineering** (Técnica de Few-Shot para ajuste de tom)

## 🧐 Processo de Criação
Utilizei o **Amazon Bedrock** para gerar explicações sobre *arquetetura de microserviços* e *manifestos Kubernetes*. Em vez de pedir "explique o pod", utilizei prompts contextualizados pedindo analogias do mundo real e gírias corporativas de TI para mascarar a origem artificial do texto.

## 🚀 Resultados
O texto gerado apresentou uma fluidez surpreendente, utilizando termos como "gargalo", "deploy suave" e analogias com trânsito para explicar balanceamento de carga, passando no teste de "Natty" (natural) para leitores leigos.

## 💭 Reflexão (Opcional)
O desafio foi impedir que a IA fosse excessivamente formal. Ajustar a "temperatura" do modelo no Bedrock foi essencial para atingir o resultado "fake natty".
