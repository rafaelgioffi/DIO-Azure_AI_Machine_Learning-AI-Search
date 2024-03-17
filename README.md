# DIO-Azure_AI_Machine_Learning-AI-Search
Repositório para representar uma Azure AI Search configurada.

### Passo-a-passo da configuração:
<ul>
<li>Não foi necessário criar um Resource Group pois já existia.</li>
<li>Não foi necessário criar um Azure AI Service pois já havia sido criado em outro laboratório</li>
<li>Criado um AI Search Service no tier basic ao invés do standard.</li>
<li>Criado um Storage Account standard LRS e alterada a permissão para anonymous access.</li>
<li>Criado um container com permissão container dentro do storage account</li>
  <li>Mesmo seguindo os passos, não foi possível importar os dados no AI Serach Service, foi usado um banco de exemplo usando a opção samples em data sources</li>
</ul>
