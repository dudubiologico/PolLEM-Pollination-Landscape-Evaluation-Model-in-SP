# POLLEM SP - Pollination Landscape Evaluation Model in São Paulo (Modelo de Avaliação da Polinização na Paisagem em São Paulo).
O objetivo deste repositório é apresentar resultados de um modelo espacialmente explícito da provisão potencial de polinização baseado na estrutura de oferta, fluxo e demanda, proposta por Metzger et al. (2021), bem como valorar esse serviço para a produção agrícola do estado de São Paulo. Esse modelo, desenvolvido no âmbito do programa Biota Síntese, supera muitas das deficiências das abordagens tradicionais ao estimar o fornecimento de polinização. O modelo foi elaborado e aplicado para todo o estado de São Paulo, de forma a possibilitar a identificação de possíveis aderências e desafios para a incorporação e utilização do modelo em políticas públicas paulistas.

A descrição do modelo e suas aplicações estão disponível na quarta Nota Técnico-científica do Projeto Biota Síntese.

# Dados incluídos neste repositório:
Camadas raster (GeoTIFF):
1.	Camadas de base
1.1.	Buffer de 20km do limite de São Paulo
1.2.	Área de vegetação nativa (binário, 0 e 1)
1.3.	Área de cultivos dependentes (binário, 0 e 1)
1.4.	Área de cultivo de soja (binário, 0 e 1)
1.5.	Área de cultivo das outras culturas temporárias (binário, 0 e 1)
1.6.	Área de cultivo de café (binário, 0 e 1)
1.7.	Área de cultivo de citrus (binário, 0 e 1)
1.8.	Área de cultivo das outras culturas perenes (binário, 0 e 1)
1.9.	Média da diversidade Shannon da paisagem
1.10.	Média da Proporção de vegetação nativa
1.11.	Altura máxima do dossel
1.12.	Valor máximo de NDVI

2.	Oferta e fluxo de polinizadores
2.1.	Oferta de polinizadores normalizado (intervalo de 0 a 1)
2.2.	Fluxo de polinizadores normalizado (intervalo de 0 a 1)

3.	Demanda de polinizadores:
3.1.	Demanda de polinizadores de todos os cultivos combinados (intervalo de 0 a 1)
3.2.	Demanda de polinizadores da soja normalizada (intervalo de 0 a 1)
3.3.	Demanda de polinizadores de outros cultivos temporários normalizada (intervalo de 0 a 1)
3.4.	Demanda de polinizadores do café normalizada (intervalo de 0 a 1)
3.5.	Demanda de polinizadores de citrus normalizada (intervalo de 0 a 1)
3.6.	Demanda de polinizadores de outros cultivos perenes normalizada (intervalo de 0 a 1)

4.	Serviço de polinização
4.1.	Serviço de polinização para todos os cultivos combinados (intervalo de 0 a 1)
4.2.	Serviço de polinização da soja (intervalo de 0 a 1)
4.3.	Serviço de polinização de outros cultivos temporários (intervalo de 0 a 1)
4.4.	Serviço de polinização do café (intervalo de 0 a 1)
4.5.	Serviço de polinização do citrus (intervalo de 0 a 1)
4.6.	Serviço de polinização de outros cultivos perenes (intervalo de 0 a 1)

5.	Déficit de Serviço de polinização
5.1.	Déficit de Serviço de polinização para todos os cultivos combinados (intervalo de 0 a 1)
5.2.	Déficit de Serviço de polinização da soja (intervalo de 0 a 1)
5.3.	Déficit de Serviço de polinização de outros cultivos temporários (intervalo de 0 a 1)
5.4.	Déficit de Serviço de polinização do café (intervalo de 0 a 1)
5.5.	Déficit de Serviço de polinização do citrus (intervalo de 0 a 1)
5.6.	Déficit de Serviço de polinização de outros cultivos perenes (intervalo de 0 a 1)

Camadas vetoriais (Shapefile)
6.	Unidade Hidrográfica de Gerenciamento de Recursos Hídricos (UGRHI):
6.1.	Soma média e desvio padrão da oferta de polinizadores nas UGRHI do estado de São Paulo
6.2.	Soma média e desvio padrão do serviço e déficit de polinização nas Unidade Hidrográfica de Gerenciamento de Recursos Hídricos (UGRHI) do estado de São Paulo
7.	Valor do serviço de polinização (ano de referência 2022):
7.1.	Valor do serviço e déficit de polinização para os municípios paulistas considerando todos os cultivos dependentes de polinização
7.2.	Valor do serviço e déficit de polinização para os municípios paulistas considerando o cultivo da soja
7.3.	Valor do serviço e déficit de polinização para os municípios paulistas considerando outros cultivos temporários
7.4.	Valor do serviço e déficit de polinização para os municípios paulistas considerando o cultivo do café
7.5.	Valor do serviço e déficit de polinização para os municípios paulistas considerando o cultivo de citrus
7.6.	Valor do serviço e déficit de polinização para os municípios paulistas considerando outros cultivos perenes
