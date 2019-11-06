# Novidades Laravel 6

Code Experts [Canal no Youtube](http://youtube.com/CodeExpertsLearning).

1. Prepanando o ambiente
    + prepare o git-flow
    > git flow init
    + crie o env 
    > cp env.exemple .env
    + crie ao database
    + configure os dados do mysql no .env
    + rode o composer
    > composer install*
    + crie a chave
    > php artisan key:generate
    + crie as tabelas e com o dados (demorado)
    > php artisan migrate --seed


1. Video [Finalizando com Prática, nosso Primeiro CRUD](https://www.youtube.com/watch?v=sWI0o-KeVmc&list=PLswa9HeoJUq_4_JRdmfHj5Z2Ssq3LUqL0&index=6)
    + Criar Controller com *resource* (recursos)
    > php artisan make:controller PostController -r
    + Criar as rotas em **web.app**
    ```sh
    # Rotas geradas automaticamente para nosso CRUD
    Route::resource('post', 'PostController');
    ```
