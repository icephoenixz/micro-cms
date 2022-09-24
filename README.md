### 🎈Micro CMS
Gestor de contenido personalizable enfocado a entusiasta de la programación o estudiantes. Puedes crear blogs, servicios, usuarios, productos, cupones, pagos entre otras cosas.
![](https://badgen.net/badge/PHP/>=7.1/green) ![](https://badgen.net/badge/MySQL/>=5.5/green)  ![](https://badgen.net/gitlab/license/gitlab-org/omnibus-gitlab)

https://www.youtube.com/watch?v=pijIRTc6pRA&list=PLVsoX1f7YHL3Br3-0xxbLZedcYKW1zCi5&index=7

- ¿Como instalar en Plesk, cPanel, Hosting compartido  __[Ver](https://github.com/leifermendez/micro-cms/wiki/Instalaci%C3%B3n-en-cPanel,-Plesk-(Hosting-compartido))__
- ¿Quieres coloborar con el proyecto (Conocimiento)? __[Ver](https://github.com/leifermendez/micro-cms/projects/1)__

---
<a href="https://www.buymeacoffee.com/leifermendez" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

**[DEMO](https://micro-cms-codigoencasa.herokuapp.com/)**
![](https://i.imgur.com/HU2QlVL.png)


----

**Tecnologías usadas en el proyecto.**
> PHP, Laravel, MySQL, Blade, JavaScript


```text
(ADMIN):
admin@admin.com
12345678

(AGENT)
agente@agente.com
12345678

(USER)
user@user.com
12345678
```

### Requerimientos
El sistema está diseñado en PHP haciendo uso del framework Laravel, asegúrate de cumplir con requisitos del sistema.

- PHP ^7.1.3
- Base de Datos (MySQL)
- [Composer](https://getcomposer.org/doc/00-intro.md)

### Deplegar
Si cuentas con una cuenta en heroku puedes desplegar con 1 solo click

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/leifermendez/micro-cms/tree/main) 

### Iniciar
Si deseas instalar en servidor compartido (cPanel, Plesk ,etc) 
[Ver](https://github.com/leifermendez/micro-cms/wiki/Instalaci%C3%B3n-en-cPanel,-Plesk-(Hosting-compartido))


Realizar los siguientes pasos en __orden__

- `git clone https://github.com/leifermendez/micro-cms.git`
-  `cd micro-cms`
- `composer install`
- Crear `.env` basado en el `.env.example`
- `composer install`
- `php artisan key:generate`
- `php artisan migrate`
- `php artisan db:seed`
- `php artisan serve`
### Configuración
Puedes ajustar la configuración de Stripe, Mail y valores generales en el archivo `.env` el cual debes crear de forma manual, copiándote del `.env.example`

> Puedes visitarnos en https://www.codigoencasa.com/te-ayudamos-con-tu-codigo/

----
![](https://i.imgur.com/MAEzo0O.png)

![](https://i.imgur.com/PYz6TIq.png)

<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/15802366/100853143-b95c5f00-3487-11eb-8e43-e969645d2a85.gif">
</p>
