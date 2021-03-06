# Ecoleta

## Sobre o projeto

A aplicação ecoleta foi um projeto desenvolvido durante a semana Next Level Week. É uma aplicação completa, desde o backend ao frontend (web e mobile), utilizando TypeScript junto a tecnologias como: nodejs, React Js e React Native.

O objetivo da aplicação é para que os locais que fazem coletas de coisas recicláveis se cadastrem através da interface web, informando o local e items coletados pela empresa. Enquanto na interface mobile os usuários pode procurar por empresas em locais específicos e que coleta itens específicos através de filtros de seleção.

### Frontend Web:

O frontend web feito com React Js é composto por duas páginas, uma de Boas vindas e outra para o cadastro da empresa.

#### Imagens:

##### Página de boas vindas:

<img src='images/img_web_01.png' alt='HomeImg' />

##### Página de Cadastro: 

A página de cadastro permite o upload de imagens utilizando a biblioteca react-dropzone:

<img src='images/img_web_02.png' alt='RegisterImgUpload' />

Além de possuir integração com a biblioteca de mapas Leaflet, e também com a api do IBGE para listar estados e cidades:

<img src='images/img_web_03.png' alt='HomeImg' />

### Frontend mobile:

O frontend mobile foi desenvolvido com React Native e possui 3 telas, uma de boas vindas onde o usuário irá filtrar por estado e cidade os pontos de coleta cadastrados, a segundo mostra os pontos de coleta em um mapa onde o usuário poderar filtrar por itens coletados, após selecionar o ponto de coleta a terceira tela será exibida, mostrando informações detalhadas do ponto.

#### Imagens:

##### Tela de boas vindas:

A tela inicial também possui uma integração com a api do IBGE:

<img src='images/img_mobile_01.png' alt='HomeMobileImg' width='300' />

##### Tela de listagem de pontos:

<img src='images/img_mobile_02.png' alt='ListMobileImg' width='300' />

##### Tela ponto selecionado:

<img src='images/img_mobile_03.png' alt='HomeMobileImg' width='300' />
