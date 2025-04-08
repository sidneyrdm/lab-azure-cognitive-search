# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

### O que é mineração de conhecimento?
* As organizações tem muito conteúdo
* Os dados são bloqueados em documentos, pdfs, notas manuscritas, etc.
* A mineração de conhecimento encontra insights(palavras-chave) em escala
* Azure cognitive search é a plataforma de mineração de conhecimento alimentada por IA.


### Soluções de pesquisa cognitiva do Azure
* Ingestão de dados 
  -> Azure Blob Storage containers
    -> reconhece qualquer tipo de documento, imagem, vídeo.
  -> Azure Data Lake Storage Gen 2
  -> Azure Table Storage

* Enriquecimento e índice de IA
  -> permite uma compreensão mais profunda
  -> visão, processamento de linguagem natural, etc.
  -> a indexação torna o conteúdo pesquisável 

* Explorar
  -> pesquisa realizada em índices
  -> dentro dos aplicativos
  -> crie vizualizações de dados

* Enriquecimento de IA
  -> torna o conteúdo mais útil para fins de pesquisa
  -> o conteúdo enriquecido é criado por conjunro de habilidades como:
    -> reconhece entidades no texto
    -> traduzir texto
    -> avalie o sentimento
    -> consumido durante a indexação
    -> os dados serializados são passados ao mecanismo de pesquisa para indexação
