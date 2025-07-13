# Star-Identification-ML
Identificação de Estrelas e Galáxias com Tratamento de Imagens usando 
Non-Maximum Suppression e Machine Learning 
Paulo Rodolfo Alves de Matos - Engenheiro de Computação

A astronomia moderna depende fortemente da análise de imagens para identificar e classificar 
objetos celestes, como estrelas e galáxias. Os telescópios espaciais, como o Hubble e o James 
Webb, capturam imagens de alta resolução que contêm milhões de fontes luminosas. No 
entanto, para distinguir estrelas de galáxias, é necessário um processamento eficiente das 
imagens. Uma técnica amplamente utilizada na detecção de bordas e realce de características 
é a Supressão Não Máxima (Non-Maximum Suppression - NMS), essencial na detecção de 
objetos em imagens astronômicas. 
Nesse contexto, métodos de aprendizado de máquina são fundamentais para otimizar a 
segmentação e classificação dos objetos detectados. O algoritmo DBSCAN (Density-Based 
Spatial Clustering of Applications with Noise) desempenha um papel crucial na identificação de 
agrupamentos de fontes luminosas. Como um algoritmo de agrupamento baseado em 
densidade, ele permite separar conjuntos de estrelas de galáxias, classificando-os de acordo 
com a concentração de pontos em torno de determinadas regiões espaciais. Isso é 
particularmente útil em imagens astronômicas, onde objetos podem variar significativamente 
em brilho e distribuição espacial. 
Além disso, a limiaridade é um conceito essencial no processamento de imagens astronômicas. 
A aplicação de técnicas de limiarização permite distinguir objetos relevantes do fundo da 
imagem, garantindo que apenas fontes luminosas significativas sejam consideradas para 
análise. A escolha de um limiar adequado pode ser baseada em métodos estatísticos ou 
heurísticos, sendo frequentemente combinada com aprendizado de máquina para ajuste 
dinâmico dos valores. Isso melhora significativamente a precisão na classificação de estrelas e 
galáxias, reduzindo falsos positivos e aprimorando a qualidade dos dados para investigações 
científicas. 
A integração dessas técnicas de aprendizado de máquina com processamento de imagens 
astronômicas abre caminho para descobertas inovadoras, permitindo a análise automatizada 
de grandes volumes de dados e auxiliando astrônomos na compreensão do universo. 
