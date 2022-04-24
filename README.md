# RPA NA AUTOMAÇÃO DE TESTES

Abaixo encontrará o passo a passo para correr o RPA em sua maquina e vê-lo a trabalhar.

# UI PATH STUDIO COMMUNITY - CERTIFICADOS ENERGÉTICOS

1 - Vamos começar por nos registrar na plataforma UI PATH para assim conseguirmos instalar o Studio Community. Acesse esse link:
https://cloud.uipath.com/portal_/register
          
2 - Depois de se registrar verá algo como isto:
  
  ![image](https://user-images.githubusercontent.com/61801971/164992020-84d0843c-f562-48d3-9953-03045cbe2eca.png)

Caso não consiga visualizar a mesma coisa carregue no link : https://cloud.uipath.com/

Agora carregue no botão azul onde diz "DOWNLOAD UI PATH STUDIO"

![image](https://user-images.githubusercontent.com/61801971/164992165-2308a2da-e562-445d-b02a-0ba00b3a1e60.png)

3- Siga os passo da instalação

4- Agora vamos precisar instalar a extensão do Google Chrome: https://chrome.google.com/webstore/detail/uipath-web-automation-224/femlfgkoahmpkceibadfboihnjmmldnb

5- Abra a aplicação do UIPath Studio Community que instalou no seu computador, você deve ver algo parecido com isso:

![image](https://user-images.githubusercontent.com/61801971/164993659-a54ab710-ed3e-4836-8006-d1df169fe8c3.png)

6- Nesta aba carregue em Clone or Check Out, como indicado na figura abaixo:

![image](https://user-images.githubusercontent.com/61801971/164993739-ef8f55b5-cc32-4ccd-9c03-e146bba56e2a.png)

7- Depois selecione a primeira opção, "Clone Repository":

![image](https://user-images.githubusercontent.com/61801971/164993769-4b457936-866c-4cd9-8e5e-91b62ccb9447.png)

8- No popup que aparecer coloque o seguinte link e carregue em open:
https://github.com/danilo21905954/a21905954_a22008013_RPA-na-automa-o-de-testes

![image](https://user-images.githubusercontent.com/61801971/164993819-2d3ab075-6e1d-48f2-8b9d-2ebfbf7f2d19.png)

9- Depois, pode ser que apareça a mensagem abaixo para autorizar que a UI Path tenha acesso ao seu Git.

![image](https://user-images.githubusercontent.com/61801971/164993245-8700516e-0dd3-422c-94c4-8b8e499630e9.png)

10- Após aceitar encontrará uma interface semelhante a esta:

![image](https://user-images.githubusercontent.com/61801971/164993921-6452cecf-e3c8-4128-a36c-cfdb6ad198af.png)

11- Para colocar o RPA em execução temos que realizar uma única mudança que é indicar o caminho para o ficheiro de input, para isso baixe o ficheiro DRM.zip que se encontra nesse repositório, descompacte ele e coloque a pasta DRM no seu ambiente de trabalho.

12- Dentro da pasta DRM há um ficheiro que terá de trocar o nome consoante o dia atual. Basta trocar apenas os numeros finais que são referentes ao ano, mês e dia. Seguir nomenclatura "DMR_CertificadosEnergeticos_YYYYMMDD", onde "YYYY" representa o ano com 4 digitos, "MM" representa o mês com 2 digitos e "DD" representa o dia com dois digitos.

12- Abra novamente a interface do UIPath Studio, e no painel lateral esquerdo carregue no ficheiro "MAIN"

![image](https://user-images.githubusercontent.com/61801971/164994593-c2e86bd7-710a-4907-af08-404680ddd793.png)

14- Na parte inferior, caso não esteja aberto, carregue em "Variables":
![image](https://user-images.githubusercontent.com/61801971/164994624-1982da62-e58c-486b-b548-71557d782dd2.png)

13- Onde está a variável com o nome Path será necessário alterar o valor default para o caminho do ficheiro input que se encontra dentro da pasta que extraimos:
![image](https://user-images.githubusercontent.com/61801971/164994258-17bd7da0-4517-46c6-ab9f-9e62d5478b52.png)

Veja na imagem que não é preciso cocolar o nome do arquivo e não se esqueça de colocar a contra barra ao fim!!

14- Agora basta carregar na seta por debaixo do botão play no canto superior esquerdo e carregue em "RUN"
![image](https://user-images.githubusercontent.com/61801971/164994316-99db11ea-095c-415e-b462-308c37edeb9b.png)
