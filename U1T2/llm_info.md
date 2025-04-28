# Informações sobre o uso de modelos de linguagem

## Modelo utilizado

Google Gemini 2.0 Flash. 

## Prompt utilizado

Cada página desse arquivo contém uma receita. Para cada receita, extraia o nome e os ingredientes (ignorando a quantidade). Monte então um arquivo csv em que cada linha corresponda a uma das receitas. A primeira coluna deve conter o nome da receita. A segunda coluna deve conter uma lista com os nomes dos ingredientes. A terceira deve conter uma lista com os tipos dos ingredientes, na mesma ordem da segunda coluna. Para montar a terceira coluna, classifique os ingredientes como pertencentes a um dos seguintes tipos: proteína, carboidrato, laticínio, fruta, vegetal, gordura, condimento e outro. Como são 94 páginas, o arquivo csv deve ter 94 linhas, além do cabeçalho.
