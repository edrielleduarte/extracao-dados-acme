# Extração de dados Acme

## Processo
* O desafio do bot é extrair dados de uma tabela do site da [Acme](https://acme-test.uipath.com/login)
e inserindo as informações em uma planilha geral e também em planilhas individuais conforme o WI1, WI2 e assim por diante correspondente o numeral.

       Informações necessarias: O bot esta com login e senha na qual deixei de treinamento, qualquer coisa, só alterar
      a variavel de argumento do projeto e a senha na pagina pois esta com segurança. Caso prefira, pode exceutar com email que esta
      no projeto pois como informei, é email é de treinamento.
      
   
   <b>Dicas:</b> confira se está deslogado do site e não tenha nenhuma aba aberta referente ao mesmo e confira as informações também apos realizar login, fazer o procedimento da imagem a seguir para que as informações apareça para ser extraidas:
       
   ![info](https://user-images.githubusercontent.com/80603255/167060400-65ee30bb-4805-4e95-9235-35fffc33ffab.jpg)


## Etapas

* Etapa Login: O bot ira digitar o email e senha do usuário e em seguida clicar no botão de login.

![pag_1](https://user-images.githubusercontent.com/80603255/167058131-62d315ae-d2fe-4859-be28-808f0fcf7a85.jpg)


* Etapa 2 Menu: Após login, o bot irá clicar no botão `Work Items`.

![pa_2](https://user-images.githubusercontent.com/80603255/167058365-c6792832-325d-48e5-b69a-fcc5dad6ac86.jpg)

* Etapa 3 Tabela: A partir o bot irá extrair todos os dados da tabela no site, indo pagina por pagina.

![pag_3](https://user-images.githubusercontent.com/80603255/167058461-93d2bf5c-75f5-40d3-bc2b-879b55d224b6.jpg)

* Etapa 4 Informações: O bot irá guardar os dados da coluna "Type" na qual irá ver o final do numero 1, 2, 3, 4 e 5.

![pag_4](https://user-images.githubusercontent.com/80603255/167058636-d84d8fa6-990a-4a67-9658-84952cb7d181.jpg)

* Etapa 5 Criação Planilha: Apos verificar a coluna Type, o bot ira criar uma planilha registrando todas as informações gerais
 e apos uma contendo cada WI e o seu numeral, conforme as imagens de exemplos abaixo:
 
    * Informações gerais
    
        ![pag_geral](https://user-images.githubusercontent.com/80603255/167058912-b93b1d3c-48a3-42cb-93e4-5b13ed92cc97.jpg)

    * Informações planilhas individuais
    
        ![pag_indi](https://user-images.githubusercontent.com/80603255/167058952-5c5db7c0-fe25-4716-8518-5f80161b954c.jpg)


Apos o bot é finalizado e as planilhas salvas na pasta do projeto.
