# Desafio04 - Azure Cognitive Search Utilizando AI Search para indexação e consulta de Dados

O objetivo é criar uma pesquisa usando o AI Search, para consiga identificar palavras chaves, sentimentos, indexação, consulta de dados, etc. 

Utilizando essa documentação: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

Passo 1: Criar um recurso do Azure AI Search pelo portal. 

Passo 2: Criar um recurso do Azure AI Services.

Passo 3: Criar uma conta de armazenamento, o storage accounts e configura-lo. 

Passo 4: Dentro do storage accounts, criar um container e configura-lo.

Passo 5: Abrir o container, clicar em upload para carregar os arquivos. 

Passo 6: Ir até o AI Services - AI Search e importar os dados.

Passo 7: Após todas as configurações, consultar o índice no search explorer.

Comandos feitos na aula: 

    search=*&$count=true   
    (A consulta de pesquisa retorna todos os documentos no índice de pesquisa, incluindo uma contagem de todos os documentos no campo @odata.count)

    search=locations:'Chicago' 
    (Consulta as ocorrências filtrando por Chicado)

    search=sentiment:'negative' 
    (Consulta as ocorrências com sentimento negativo)
