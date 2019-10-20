# form
Form package for Bone Mvc Framework using `delboy1978uk/form`, but PSR-11 dependency injection capable, and with i18n 
functionality. 
## installation
Use Composer
```
composer require delboy1978uk/bone-form
```
## usage
Simply add to the `config/packages.php`
```php
<?php

// use statements here
use Bone\Form\FormPackage;

return [
    'packages' => [
        // packages here...,
        FormPackage::class,
    ],
    // ...
];
```