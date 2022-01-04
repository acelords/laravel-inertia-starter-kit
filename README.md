# Laravel Inertia Starter-Kit
A frontend and backend (admin-client) dashboard based on 
- Laravel 8 
- Inertiajs
- Laravel Sanctum
- Laravel Jetstream
- Laravel Fortify
- Vue 3
- TailwindCSS 
- Material Design Icons 

The project is also REST-API ready; meaning all end-points have been tested and ready to be consumed by a mobile or desktop app.

Some key technologies and tooling used include:
- `Pest` - PHP testing library
- `Jest` - Javascript testing library
- `Laravel Mix` - compile assets
- `Laratrust` - provide roles and permissions based authorization
- `Redis` - key-value based super-fast storage
- `Supervisor` - automated task runner (linux)

## Links & Demo
- [Demo Link 1](https://inertia-skeleton.acelords.space)
- [Purchase Link 1](https://store.acelords.space?search=laravel-inertia-skeleton)
- [Feature List](https://inertia-skeleton.acelords.space/admin/features)

![Screenshot 1](admin-screenshots/admin-dashboard-1.jpg)

## Features
You can check [more features here](https://inertia-skeleton.acelords.space/admin/features) for the latest features incorporated in the project.

- Light/Dark Themes
- SEO content management for frontend pages.
- Sitemap Generator (Automated via Laravel Scheduler)
- Admin Dashboard
    - Users Management
    - Settings
        - ENV file (CRUD)
        - Configurations
        - Organisations (CRUD)
        - SEO (CRUD)
        - Roles (CRUD)
        - Permissions (CRUD)
        - System Info (Superadmin) - Update the ENV file straight from admin dashboard
        - Reset System
            - Clear Redis
            - Clear cached views
            - Refresh configurations (settings)
            - Update configurations (settings)
            - Truncate and Reset configurations (settings)
            - Update permissions
            - Seed Demo data
    - Profile Management
- Client Dashboard
    - Profile Management



## Dependencies
Here are the dependencies used in the project
#### composer.json
```json
"require": {
    "php": "^7.3|^8.0",
    "acelords/jetstream": "2.5.0.1",
    "acelords/keygen": "^2.0",
    "acelords/laratrust": "6.3.1.1",
    "africastalking/africastalking": "^3.0",
    "agog/osmose": "^2.1",
    "artesaos/seotools": "^0.20.2",
    "doctrine/dbal": "^3.0",
    "fideloper/proxy": "^4.4",
    "fruitcake/laravel-cors": "^2.0",
    "guzzlehttp/guzzle": "^7.4",
    "highideas/laravel-users-online": "^3.0",
    "inertiajs/inertia-laravel": "^0.4.3",
    "kreait/laravel-firebase": "^3.4",
    "laravel-notification-channels/fcm": "~2.0",
    "laravel-notification-channels/webpush": "^5.1",
    "laravel/framework": "^8.77",
    "laravel/horizon": "^5.7",
    "laravel/sanctum": "^2.13",
    "laravel/slack-notification-channel": "^2.3",
    "laravel/socialite": "^5.2",
    "laravel/tinker": "^2.5",
    "maatwebsite/excel": "^3.1",
    "predis/predis": "^1.1",
    "rap2hpoutre/laravel-log-viewer": "^2.0",
    "spatie/laravel-query-builder": "^4.0",
    "tightenco/ziggy": "^1.0"
},
"require-dev": {
    "barryvdh/laravel-ide-helper": "^2.9",
    "facade/ignition": "^2.5",
    "fakerphp/faker": "^1.9.1",
    "kint-php/kint": "^4.0",
    "mockery/mockery": "^1.4.2",
    "nunomaduro/collision": "^5.0",
    "pestphp/pest": "^1.21",
    "pestphp/pest-plugin-laravel": "^1.1",
    "phpunit/phpunit": "^9.3.3"
},
```

#### package.json
```json
"devDependencies": {
    "@inertiajs/inertia": "^0.10.0",
    "@inertiajs/inertia-vue3": "^0.5.1",
    "@inertiajs/progress": "^0.2.6",
    "@tailwindcss/forms": "^0.4.0",
    "@tailwindcss/typography": "^0.5.0",
    "@vue/compiler-sfc": "^3.0.5",
    "axios": "^0.21",
    "browser-sync": "^2.27.7",
    "browser-sync-webpack-plugin": "^2.3.0",
    "laravel-mix": "^6.0.6",
    "lodash": "^4.17.21",
    "postcss": "^8.4.5",
    "postcss-import": "^12.0.1",
    "sass": "^1.45.1",
    "sass-loader": "^12.4.0",
    "tailwindcss": "^3.0.0",
    "vue": "^3.0.5",
    "vue-loader": "^16.1.2"
},
"dependencies": {
    "animate.css": "^4.1.1",
    "chart.js": "^3.7.0",
    "daisyui": "^1.20.0",
    "date-fns": "^2.27.0",
    "epic-spinners": "^1.1.0",
    "notiwind": "^1.2.4",
    "numeral": "^2.0.6",
    "pluralize": "^8.0.0",
    "sweetalert2": "^11.3.3",
    "vue-chartkick": "^1.1.0",
    "vue-cookie-comply": "^0.0.3",
    "vue-final-modal": "^3.4.3",
    "vue3trend": "^1.0.0"
}
```

## Credits
- [AceLords](https://acelords.space)
- [Lexx YungCarter](https://twitter.com/UnderscoreLexx)

## Contact
- [Official: info@acelords.space](mailto:info@acelords.space)
- [Personal: lexxyungcarter@gmail.com](mailto:lexxyungcarter@gmail.com)

## Links
- [AceLords Store](https://store.acelords.space)
- [AceLords Website](https://acelords.space)
- [Github Projects](https://github.com/acelords)

![Screenshot 2](admin-screenshots/admin-settings-sitemaps.jpg)
