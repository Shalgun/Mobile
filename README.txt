README BICOS

OBS.: O banco de dados do Web é diferente do Mobile por alguns conflitos que tivemos e não conseguiremos juntar os 2 a tempo, entretanto pretendemos contiuar trabalhando no projeto após apresentação do TCC.

------------ MOBILE-------------

LOGIN CLIENTE MOBILE

email: ogaua@gmail.com
senha: Ricardo@123

-----------------------

LOGIN FREELANCER MOBILE

cpf: 212.357.370-12
senha: Ricardo@123

-----------------------

Passos para instalação do mobile:

1° Download do flutter: https://docs.flutter.dev/get-started/install/windows;

2° Crie uma pasta com o nome "src" no C: e descompacte o zip;

3° Após isso, no visual studio code, vai baixar as extensões "Code Runner", "Dart" e "Flutter";

4° Abra o android studio, clique nos três pontinhos e vá em SDK Manager, em seguida, no SDK Tools, encontre a opção Android SDK Command-line Tools, marque a caixa e salve;

5° Vá nas variáveis de ambiente do windows, e em path, adicione a localização do bin (C:\src\flutter\bin);


------------ BANCO MOBILE-------------

NOME DO ARQUIVO DO BANCO: 'api-tcc ENTREGA.rar'

Para o banco do mobile funcionar é necessário baixar algumas coisas disponíveis nesses sites:

https://www.apachefriends.org/pt_br/index.html
https://getcomposer.org/download/

Aqui um vídeo para auxiliar:

https://www.youtube.com/watch?v=X4aaPtEbeVM

-----------------------

Dentro do projeto tem q mudar o arquivo '.env' para conectar com seu MYSQL, isso deve ser feito colocando os seus dados aqui:
DB_CONNECTION=mysql
DB_HOST=*Host*
DB_PORT=*Porta*
DB_DATABASE=*Nome do banco*
DB_USERNAME=*Nome do usuário*
DB_PASSWORD=*Senha*

Exemplo de preenchimento:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3307
DB_DATABASE=bdtcc
DB_USERNAME=root
DB_PASSWORD=12345

-----------------------

Depois de conectar com o banco só precisa criar uma tabela com o mesmo nome que foi colocado no '.env' no MYSQL, e usar o comando 'php artisan migrate'.

O comando para abrir o server é 'php artisan serve', para fechar é só pressionar 'Control + C'.

------------ WEB-------------
LOGIN CLIENTE WEB

email: milena@gmail.com
senha: m

-----------------------

LOGIN FREELANCER WEB

email: choi@gmail.com
senha: c

-----------------------

Para o WEB funcionar é necessário baixar os 3 arquivos presentes na pasta 'WEB DOWNLOADS' no próprio GITHUB, na url:

