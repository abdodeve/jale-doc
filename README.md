

# Jale

> Site pédagogique a pour vocation de sensibiliser à l'énergie

![Jale](https://i.imgur.com/bLMGLgl.png)

Ce site pédagogique a pour vocation de sensibiliser à l’énergie, ses enjeux et ses opportunités, dans un contexte de transition énergétique. Cette transition s’opère à tous les niveaux de la chaîne énergétique. Les modes, visions, emplois et solutions sont revus en profondeur pour correspondre aux besoins du monde d’aujourd’hui et de demain : responsable, durable et solidaire.


![](header.png)

  

## Requierments

* PHP version 7 or later.

* Node.js 10 or later.

* Apache or Nginx

* MySql or MariaDB

## Uses/Features

* [Php 7+](https://www.php.net): PHP language

* [npm](https://npmjs.com) or gulp: Package manager

* [Laravel 5,7](https://laravel.com): PHP Framework for build web applications

* [Nova](https://nova.laravel.com): Administration panel for Laravel.

* [Phpunit](https://www.npmjs.com/package/uuid): Unit test

* [Vue.js 2.6](https://vuejs.org): The Progressive  JavaScript Framework

## Installation

### Backend

```sh

git clone https://github.tools.digital.engie.com/NewcorpHQJale/jale-website.git

```

```sh
cd web/www
```

```sh
composer install
```
```sh
composer dump-autoload
```
```sh
php artisan migrate
```
```sh
php artisan db:seed
```

### Frontend

```sh

npm run gulp

```

```sh

npm run dev

```

## Mechanisme

![Jale mechanisme](https://i.imgur.com/xo26pFf.png)

* Ambassadeur : Peut acceder à (/ambassadeurs) et front office (/home)
* Utilisateur : Peut acceder à front office (/home)
* Admin : Peut acceder à tous + espace admin (/admin)

## Structure
![Jale structure](https://i.imgur.com/FtXi1g7.png)

* /app : Responsable de la partie front office, contient les controllers, models etc ..
* /app/Nova : Responsable de la partie back office, contient les ressources, actions etc ..
* /app/resources : Contient les fichiers  de blade files, js, css, components (vue.js)

## Contributing

1. Clone it (<https://github.tools.digital.engie.com/NewcorpHQJale/jale-website>)

2. Create your feature branch (`git checkout -b feature/featureName`)

3. Commit your changes (`git commit -am 'Add some fooBar'`)

4. Push to the branch (`git push origin feature/featureName`)

5. Create a new Pull Request

  

<!-- Markdown link & img dfn's -->

[augurisk-image]:  https://img.shields.io/badge/augurisk--backend-v0.1-brightgreen

[augurisk-url]:  https://augurisk.io

[npm-downloads]:  https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square

[travis-image]:  https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square

[travis-url]:  https://augurisk.io
