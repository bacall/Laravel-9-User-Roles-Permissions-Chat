<div data-elementor-type="wp-post" data-elementor-id="4049" class="elementor elementor-4049">
<div class="elementor-inner">
<div class="elementor-section-wrap">
<section class="elementor-section elementor-top-section elementor-element elementor-element-bd44c2b elementor-section-full_width elementor-section-height-default elementor-section-height-default" data-id="bd44c2b" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-649cc3a" data-id="649cc3a" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-d5bd258 elementor-widget elementor-widget-text-editor" data-id="d5bd258" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <h3><img decoding="async" id="centc2" class="magictime swap" src="https://www.webprogramadorbarcelona.com/wp-content/uploads/2023/02/laravel-spatie.png" alt="Laravel Spatie Permissions and Roles"> Laravel Spatie Permissions and Roles</h3> Es un paquete que le permite administrar los roles y permisos de los usuarios en su aplicación Laravel. Proporciona una manera fácil de agregar roles, asignarlos a usuarios, verificar la autorización basada en roles y más. El paquete también incluye una directiva Blade para comprobar si un usuario tiene un determinado permiso.<br> <a href="https://spatie.be/docs/laravel-permission/v5/installation-laravel" target="_blank" rel="noopener">Documentación oficial Spatie</a><br> <a href="https://medium.com/@laraveltuts/laravel-9-user-roles-and-permissions-tutorial-example-79ee2ebd24d8" target="_blank" rel="noopener">Tutorial de permisos y roles de usuario en Laravel 9 con Spatie de @laraveltuts</a></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-544f8c8 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="544f8c8" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1f31a67" data-id="1f31a67" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-35fc813 elementor-widget elementor-widget-text-editor" data-id="35fc813" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> composer require spatie/laravel-permission composer require laravelcollective/html php artisan vendor:publish –provider=»Spatie\Permission\PermissionServiceProvider» php artisan migrate</div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-99c22a4 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="99c22a4" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-c539114" data-id="c539114" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-715b614 elementor-widget elementor-widget-text-editor" data-id="715b614" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <p><b>Modificar los siguientes archivos:</b><br>app/Models/User.php<br>app/Http/Kernel.php<br>routes/web.php</p><p><b>Vistas :</b><br>resources/views/layouts/app.blade.php</p><p><b>Se crean&nbsp;</b><b>Users Blade Pages:</b><br>resources/views/users/index.blade.php<br>resources/views/users/create.blade.php<br>resources/views/users/edit.blade.php<br>resources/views/users/show.blade.php</p></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-584c798 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="584c798" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-adb8221" data-id="adb8221" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-f23e992 elementor-widget elementor-widget-text-editor" data-id="f23e992" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <p>php artisan make:seeder PermissionTableSeeder</p><p>php artisan make:seeder CreateAdminUserSeeder</p><p><b>El contenido de los seeders están en database/seeders<br></b><br><b>Seeding database.</b><br><span style="font-size: 21px; color: var( --e-global-color-text ); font-family: var( --e-global-typography-text-font-family ), Sans-serif;">php artisan db:seed –class=PermissionTableSeeder</span></p><p><b>Seeding database.</b><br>php artisan db:seed –class=CreateAdminUserSeeder</p></div></div></div><div class="elementor-element elementor-element-0c444c0 elementor-widget elementor-widget-text-editor" data-id="0c444c0" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-c2112b2 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="c2112b2" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-772364e" data-id="772364e" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-68fa459 elementor-widget elementor-widget-text-editor" data-id="68fa459" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <h3>Instalar <img decoding="async" id="centc2" class="magictime swap" src="https://www.webprogramadorbarcelona.com/wp-content/uploads/2023/02/chatify_black.png" alt="chatify"></h3> Chatify es una plataforma de chat que permite a los usuarios crear, implementar y administrar chats de conversación. <a href="https://chatify.munafio.com/installation" target="_blank" rel="noopener">Instalación oficial</a><br><br> <a href="https://dashboard.pusher.com/accounts/sign_up" target="_blank" rel="noopener"> También necesitamos registrarnos en Pusher para las credenciales que pondremos en el archivo .env </a></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-8e1af25 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="8e1af25" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-7e95ca6" data-id="7e95ca6" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-8686845 elementor-widget elementor-widget-text-editor" data-id="8686845" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <p>composer require munafio/chatify<br> php artisan chatify:install<br> php artisan migrate</p> <p>composer require laravel/ui<br> php artisan ui bootstrap<br> php artisan ui bootstrap –auth</p> <p><b>Update </b><br> vite.config.js</p> <p><b>Update </b><br> resources/js/bootstrap.js</p> <p><b>Update </b><br> resources/js/app.js</p> <p>npm install<br> npm run build</p> <p><b>En:</b><br> resources/views/layouts/app.blade.php<br> Encima de Nombre de usuario añadir</p> <ul> <li class="nav-item">&lt;a class=»nav-link» href=»{{ route(‘chatify’) }}»&gt;{{ __(‘Chat’) }} &lt;/a&gt;</li> </ul> <p>php artisan serve</p> <p>Registrase o Login</p></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-4499424 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="4499424" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2f8fd1c" data-id="2f8fd1c" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-acc981a elementor-widget-divider--view-line elementor-widget elementor-widget-divider" data-id="acc981a" data-element_type="widget" data-widget_type="divider.default">
<div class="elementor-widget-container">
<div class="elementor-divider"> <span class="elementor-divider-separator"> </span></div></div></div></div></div></div></div></div></section>
<section class="elementor-section elementor-top-section elementor-element elementor-element-1f3e100 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1f3e100" data-element_type="section">
<div class="elementor-container elementor-column-gap-default">
<div class="elementor-row">
<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-b0e206e" data-id="b0e206e" data-element_type="column">
<div class="elementor-column-wrap elementor-element-populated">
<div class="elementor-widget-wrap">
<div class="elementor-element elementor-element-c9b0e38 elementor-widget elementor-widget-text-editor" data-id="c9b0e38" data-element_type="widget" data-widget_type="text-editor.default">
<div class="elementor-widget-container">
<div class="elementor-text-editor elementor-clearfix"> <p><b>La instalación del proyecto está en :</b><br><a href="https://github.com/bacall/Laravel-9-User-Roles-Permissions-Chat" target="_blank" rel="noopener">https://github.com/bacall/Laravel-9-User-Roles-Permissions-Chat</a></p></div></div></div></div></div></div></div></div></section></div></div></div>