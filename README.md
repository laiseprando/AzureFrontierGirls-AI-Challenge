# AzureFrontierGirls-AI-Challenge
Build Your First Copilot Challenge (Foundry Edition)
## Introdução
Projeto desenvolvido para conclusão do curso Azure Frontier Girls promovido pela WoMakersCode e Microsoft.
O projeto baseou-se na criação de um agente de inteligência artificial no AI Foundry.
<br/>
<br/>

## 🤖 Agente de Cálculo de Alto Desempenho (Azure AI Foundry)
Este é um projeto de prova de conceito (PoC) que demonstra a criação e a funcionalidade de um Agente de IA Orientado à Ação utilizando o Azure AI Foundry Agent Service. O agente foi projetado para atuar como um Assistente de Análise e Cálculo de Dados, utilizando a ferramenta Code Interpreter para executar código Python e garantir a precisão de cálculos complexos.
<br/>

## ✨ Funcionalidades Principais

| Funcionalidade | Descrição | Status |
| --- | --- | --- |
| Cálculo Preciso | Resolve equações matemáticas e expressões complexas com a ajuda do Code Interpreter. | ✅ Funcional |
| Raciocínio Lógico | Utiliza o LLM (ex: GPT-4o-mini) para determinar o melhor curso de ação para resolver o problema. | ✅ Integrado |
| Processamento de Dados | Capacidade de processar entradas numéricas extensas. | 🔜 Em desenvolvimento |
<br/>
<br/>

## 🛠️ Tecnologias Utilizadas 
| Plataforma Central | Modelo de Linguagem | Ação Funciona |  Infraestrutura |
| --- | --- | --- | --- |
| Azure AI Foundry Agent Service | [GPT-4o-mini](https://openai.com/pt-BR/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) | Code Interpreter (para execução de código Python) | Azure🚀 |
<br/>
<br/>

## ⚙️ Como Configurar e Rodar o Agente
Este projeto é configurado principalmente via Azure AI Studio. <br/>

**Pré-requisitos:**<br/>
Conta no Azure.<br/>
Acesso ao Azure AI Foundry.<br/>
O modelo de LLM deve estar implantado.<br/>
<br/>

### Demonstração de Uso

O agente é treinado para reconhecer quando uma requisição exige precisão matemática e, automaticamente, invoca a ferramenta de cálculo.
<br/>
**Exemplo de Prompt:** <br/>
*Qual é o resultado da expressão: (450 * 12) / 3.5 + 2^8?*<br/>

**Resultado Esperado (Raciocínio do Agente):**<br/>
  - **2.1. Reconhecimento:** O agente identifica a necessidade de cálculo.<br/>
  - **2.2 Chamada da Ferramenta:** Invoca o Code Interpreter.<br/>
  - **2.3 Execução do Código:** Roda o código Python: *print((450 * 12) / 3.5 + 2**8)*<br/>
  - **2.4 Resposta:** Apresenta o resultado final *(aproximadamente 1885.14)*.<br/>
<br/>

---

### BIBLIOGRAFIA:
[What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry?view=foundry-classic)<br/>
[AI Foundry Newsletter - By Bruno Malhano](https://www.linkedin.com/pulse/microsoft-agent-framework-major-azure-ai-foundry-updates-malhano-2knnf/)<br/>
[What is Azure AI Foundry Agent Service?](https://www.linkedin.com/pulse/microsoft-agent-framework-major-azure-ai-foundry-updates-malhano-2knnf/)<br/>
[Artificial Intelligence for Beginners - A Curriculum](https://microsoft.github.io/AI-For-Beginners/)<br/>
[Generative AI for Beginners (Version 3) - A Course](https://microsoft.github.io/generative-ai-for-beginners/#/)<br/>
[AI Agents for Begineers Repository](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)<br/>
[MCP for Beginners Repository](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)<br/>
[Discord do AI Foundry](https://discord.com/invite/microsoftfoundry)<br/>
[Regioes dos modelos](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/model-region-support?view=foundry-classic&tabs=global-standard)


