# Script Genérico ArcGIS Pro Notebook – Identificação de Tipo de Logradouro Próximo
✅ Objetivo Automatizar a associação de pontos amostrados (ex: indivíduos) ao tipo de logradouro mais próximo (rua, avenida, etc.) usando shapefiles e ferramentas do ArcPy no ArcGIS Pro Notebook, com código genérico para uso por qualquer usuário.

🧾 Título: Script Genérico ArcGIS Pro Notebook – Identificação de Tipo de Logradouro Próximo
✅ Objetivo
Automatizar a associação de pontos amostrados (ex: indivíduos) ao tipo de logradouro mais próximo (rua, avenida, etc.) usando shapefiles e ferramentas do ArcPy no ArcGIS Pro Notebook, com código genérico para uso por qualquer usuário.

ℹ️ Como usar
Abra seu notebook no ArcGIS Pro.

Cole o código acima.

Digite os caminhos completos dos shapefiles.

Clique em “Executar”.

Acompanhe o progresso no console.

📌 Plano do Código (Pseudocódigo)
Importar bibliotecas e configurar ambiente

Receber caminhos dos shapefiles via interface interativa

Copiar pontos para novo shapefile (backup)

Adicionar campo de tipo de logradouro

Criar camada dos logradouros e aplicar índice espacial

Iterar sobre pontos para encontrar o logradouro mais próximo

Atualizar shapefile com resultados

Exibir resumo dos tipos de logradouro encontrados

🧪 Requisitos
ArcGIS Pro (com licença ativa)

Notebook aberto no ambiente do ArcGIS Pro

Shapefile de pontos e shapefile de logradouros com campo NM_TIP_LOG (https://www.ibge.gov.br/geociencias/downloads-geociencias.html?caminho=recortes_para_fins_estatisticos/malha_de_setores_censitarios/censo_2022/base_de_faces_de_logradouros_versao_2022_censo_demografico/shp)


A interface é simples e permite reuso sem editar o código-fonte.

