# INSTRUCCIONES DE INSTALACION 
1. Crear el proyecto laravel (version 6 superior)
```php
    composer create-project laravel/laravel mi-proyecto-laravel "7.*"
```

2. Instalar laravel/ui para el front-end

```php
    composer require laravel/ui --dev
```

3. Indicar que el front-end por default será escrito con Vue

```php
    php artisan ui vue 
```

4. Instalacion de frameworks necsarios para el proyecto 
    * Instalación de Vue
    ```js
        npm install vue
    ```

    * Instalación de vue-router
    ```js
        npm install vue-router
    ```

     * Instalación de tailwindcss
    ```js
        npm install tailwindcss --save-dev
    ```

