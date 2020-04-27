# Visualiacao-do-output-do-WRF-no-QGIS
Manual para a visualização do output do WRF (formato netcdf) no QGIS  
  Autor: Vinicius De Martin Sarnaglia  

**1. Download do QGIS**
  - O QGis deve ser baixado no seguinte link: https://www.qgis.org/pt_BR/site/forusers/download.html  
  - Escolha a última versão stanfalone e que sej compatível com o seu sistema operacional.  
  - Instale e abra o software.  

**2. Instalação do complemento GIS4WRF**
  - Acesse a opção "Gerenciar e Instalar Complementos..."  

![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/1.png)  

- Localize e instale o complemento GIS4WRF  

![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/2.png)  

- Após clicar no botão do complemento no canto superior direito, ele abrirá no canto inferior esquerdo, e um mapa de fundo será carregado.  

![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/3.png)  

**3. Carregamento dos resultados**
  - Os resultados em netcdf devem ser carregados com base no seguinte caminho (talvez seja necessário adicionar a extensão .nc ao nome do arquivo). Localize o arquivo e adicione ao projeto (pode demorar certo tempo devido ao tamanho do arquivo).
  
![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/4.png)  

**4. Seleção dos parâmetros**
  - Os resultados serão carregados na aba "View" do GIS4WRF. Ao clicar no parâmetro desejado, ele será automaticamente carregado no mapa. A barra horizontal indica a data e horário ao que o resultado se refere. As variáveis destacadas em branco são as que possuem resultados apenas em uma camada (o resultado pode parecer deslocado, mas ao se dar o zoom adequado ao resultado, ele aparecerá na localização correta).

![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/5.png)  

  - As variáveis destacadas em verde são as que possuem resultados para mais de uma camada. Quando tais variáveis forem escolhidas, as camadas poderão ser selecionadas. Também é possível interpolar as camadas, mas, infelizmente, a interpolação não gerou nenhum raster (ao menos para mim).

![complemento 1](https://github.com/NQualiAr/Visualiacao-do-output-do-WRF-no-QGIS/blob/viniciusdms-imagens/6.png)  




