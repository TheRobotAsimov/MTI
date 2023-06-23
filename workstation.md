# PREPARAR LARAGON

**Server:** Nginx, phpmyadmin

**POO:** Python Java PHP

1. Laragon funciona con versiones de PHP y java "antiguas", por lo que se tienen que actualizar.
2. Se comprueba la versión llendo a la terminal y escribiendo ``node --version``
3. Instalar composer (para descargar muchas dependencias vía composer) y ``composer -v``
4. nmp es una gestión de independencias de nodejs, de igual forma ``nmp -v``
5. Se activa Nginx
6. Laravel
7. Base de datos
8. Crear proyecto ``laravel new sw_ep1 --jet`` jetstream -> inertia para SPA (Single Page Aplication) -> phpunit -> no teams -> yes dark mode 

(STACK: laravel, jetstream, inertia, vue)       (<u>tailwind</u>, bootstrap)
        Backend        Puentes     Fronted

(Angular, React, Vue: Frameworks Fronted) (CRUD: Create, Read, Update, Delete)

9. Después se ingresa al proyecto por ls y cd y code .
10. Entrar a .env
11. Ejecutar migraciones (tablas) ``php artisan migrate``
12. Ejecutar proyecto ``npm run dev``
13. Abrir una nueva terminal (El signo + que está abajo y start)
14. Para abrirlo, click derecho en laragon -> www y elegir proyecto
15. Puede que se este bloqueando el puerto 8080
16. Se registra en la página y el usuario se guarda en la base de datos