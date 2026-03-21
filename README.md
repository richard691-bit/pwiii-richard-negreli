# pwiii-richard-negreli
Programação Web
instalando Laravel
Caso nao tenha PHP e Composer use o comando 

 Set-ExecutionPolicy RemoteSigned para tirar alguns codigos de segurança

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.4'))


Se você já tem PHP e Compositor instalado, você pode instalar o instalador Laravel via Compositor:

composer global require laravel/installer


Criando um Aplicativo
Depois que você instalar o PHP, o Composer e o instalador do Laravel, estará pronto para criar uma nova aplicação Laravel. O instalador do Laravel solicitará que você selecione sua estrutura de teste preferida, banco de dados e kit inicial:

laravel new example-app

Depois que o aplicativo for criado, você poderá iniciar o servidor de desenvolvimento local do Laravel, o worker de fila e o servidor de desenvolvimento do Vite usando o o dev Roteiro compositor:

cd example-app
npm install && npm run build
composer run dev

Depois que você iniciar o servidor de desenvolvimento, seu aplicativo estará acessível no seu navegador da Web em http://localhost:8000.O. A seguir, você está pronto para comece a dar seus próximos passos no ecossistema Laravel.

Iniciar o XAMPP e colocar a pasta dentro do HTDoscs

Copiar a pasta .env.example e copiar e criar uma nova somente .env

depois de instalar o composer de npm install; npm run build

comandao php artisan key:generate ele gerar uma chave necessaria

rodar o banco de dadaos php artisan migrate selecionar sim

rodar o projeto, composer run dev

Controler aonde vai a logica de programação

pasta resources pasta views "Frontend" 

