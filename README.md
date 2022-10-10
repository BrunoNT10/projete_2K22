# projete_2K22
Repositório com os códigos desenvolvidos no projeto CEPEG (Controle de equipamentos de proteção nas empresas em geral)

## Projeto - CEPEG (Controle de equipamentos de proteção nas empresas em geral)

### Como o projeto funciona?

O CEPEG tem por objetivo realizar o controle do uso dos EPI's (Equipamentos de Proteção Individual) nas empresas. Mas como isso é feito? Nós desenvolvemos uma inteligência artificial utilizando a linguagem Python juntamente com a biblioteca OpenCV (Open Computer Vision - Visão Computacional Aberta) que faz uma análise de imagens dos funcionários da empresa, verificando se ele está usando todos os equipamentos. Para isso, foi desenvolvido um sistema de detecção de logotipos, em que cada equipamento de proteção possui seu próprio logotipo, que foi treinado para ser identificado usando Machine Learning da biblioteca OpenCV. Dessa forma, são colados nos equipamentos esses logotipos, e a nossa inteligência artificial faz a identificação deles.

Na imagem abaixo, é possível visualizar o funcionamento da identificação:

![Bruno Nunes Teixeira7-10-2022](https://user-images.githubusercontent.com/90159649/194877732-f1f7a456-5b14-4bfd-a278-03daace2c947.png)

Após a identificação, se o funcionário estiver utilizando todos os equipamentos de proteção, ele é liberado para entrar na sua área de serviço. Caso ele não esteja usando todos os EPI's, desenvolvemos um bot que automaticamente envia uma mensagem pelo Whatsapp para algum número pré-cadastrado, que pode ser de algum superior da empresa ou qualquer pessoa que tenha autoridade para decidir o que deve ser feito. 

Outro ponto importante é que são gerados relatórios individuais (cada funcionário tem seu próprio relatório) no formato .xlsx (Arquivos de Excel) para a empresa conseguir visualizar como os funcionários estão utilizando os equipamentos de proteção na empresa.

![imagem_excel](https://user-images.githubusercontent.com/90159649/194878942-a6932579-9d6a-4c94-a000-7edaeef80611.png)

Por fim, todos esses dados estarão disponíveis em uma página web, para que a empresa consiga acessá-los de uma maneira fácil, tornando mais viável o controle do uso dos equipamentos de proteção na empresa.
