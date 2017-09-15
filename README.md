# Laravel 5.5 (5.4) Basic Template with Bootstrap 4 (BETA)

- Derived from [Bootstrap starter template](http://getbootstrap.com/docs/4.0/examples/starter-template/)

- Create new Laravel project
```
	$ laravel new PROJECT
```

- Switch into new PROJECT, create Authentication layer, remove bootstrap-sass and install bootstrap 4.0.0-beta and popper.js (needed for tooltips)
```
	$ cd PROJECT
	$ php artisan make:auth
	$ npm uninstall --save bootstrap-sass
	$ npm install --save bootstrap@4.0.0-beta popper.js
```

- Clone the repo, copy it's content to PROJECT and overwrite existing files
```
	$ cd ..
	$ git clone git@github.com:TinoN/lv-bootstrap4-template.git
	$ cp -r lv-bootstrap4-template/* PROJECT/
```

- Install PROJECT dependencies
```
	$ cd PROJECT
	$ npm install
	$ npm run dev
```

- Run PROJECT in Browser
```
	$ php artisan serve
```

*Any comments, corrections and/or questions are welcome!*
