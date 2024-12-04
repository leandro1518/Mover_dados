Script de Processamento de Arquivos

O que o script faz?

->Procura subpastas que começam com "BK_".

->Renomeia arquivos que começam com "df" (adiciona a data de modificação no nome). -.Move os arquivos renomeados para uma pasta chamada "Dados_Tratados". ->Registra tudo isso num arquivo CSV chamado "rel_cargas.csv". ->Ignora arquivos duplicados.

Antes de usar Instale as bibliotecas necessárias: pip install pandas

Organize as pastas: ->Base: Coloque os arquivos em C:\Users\Admin\Desktop\BACKUP (ou outro caminho, é só ajustar no código).


->Saída: A pasta Dados_Tratados será criada automaticamente.
->Como usar? ->Coloque os arquivos nas subpastas que começam com BK_.
->Ajuste o caminho base no código, se necessário. !!Execute o script.
