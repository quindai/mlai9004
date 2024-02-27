# Mineração de Conhecimento e Inteligência de Documento com Microsoft Azure AI
Vamos explorar o serviço Azure AI Search index (UI) num caso de uso através de um passo-a-passo com etapas simples.

Aqui iremos fazer o seguinte:
1. Criar um recurso Azure
2. Extrair dados de um *datasource*
3. Enriquecer os dados com habilidades de IA
4. Usar o indexer do Azure no portal Azure
5. Realizar busca no indexer criado
6. Revisar os resultados armazenados numa loja de Conhecimento

Os serviços que precisamos para realizar essa tarefa são o **Azure AI Search** para gerenciar a indexação e buscas, o **Azure AI Services** para consumir os serviços de IA que vão enriquecer os dados e o **Storage Account** que será o nosso *container* de documentos.

## 1. Criar um recurso Azure
