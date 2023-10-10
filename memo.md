clé passwd = hackathon
"username": "admin@api.com",
"password": "password"

```shell
    # juste pour hasher un password rapidement 
    php bin/console security:hash-password
```
```shell
    # installation de la debug barre
    composer require --dev symfony/profiler-pack
```
```shell
    # installation d'easy admin
    composer require easycorp/easyadmin-bundle
```
```shell
    # création d'un utilisateur
    php bin/console make:user
```
```shell
    # création d'un controlleur (pas nécessaire car vide)
    php bin/console make:controller Login
```
```shell
    # installation du http client
    composer require symfony/http-client
```
```shell
    # bundle des fixtures
    symfony composer req orm-fixtures --dev
```
```shell
    # JWT plus d infos sur l installation en desous
    composer require lexik/jwt-authentication-bundle
        openssl genpkey -out config/jwt/private.pem -aes256 -algorithm rsa -pkeyopt rsa_keygen_bits:4096
        openssl pkey -in config/jwt/private.pem -out config/jwt/public.pem -pubout
```
JWT: https://openclassrooms.com/fr/courses/7709361-construisez-une-api-rest-avec-symfony/7795148-authentifiez-et-autorisez-les-utilisateurs-de-l-api-avec-jwt
```shell
    # Nelmio doc Api
    composer require nelmio/api-doc-bundle
```
Nelmmio: https://openclassrooms.com/fr/courses/7709361-construisez-une-api-rest-avec-symfony/7795180-documentez-votre-api-avec-nelmio
```shell
    # Twig asset non présent dans le --webapp
    composer require twig asset
```