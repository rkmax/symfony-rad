# Symfony RAD Edition

Basado en  [Symfony Empty Edition](https://github.com/gnugat/symfony-empty),
que es bastante ligera, se han agregado una serie de bundles practicamente que se usan en
todos los proyectos que estoy desarrollando ahora

## Instalación

Para crear una nueva aplicacion usando esta distribucion, descarga una copia de

To create a new Symfony application using this distribution, get a copy of
[Composer](http://getcomposer.org/) y usa el comando `create-project`:

    curl -sS https://getcomposer.org/installer | php
    ./composer.phar create-project rkmax/symfony-rad ruta/donde/instalar

Entonces solo reemplaza:

1. reemplaza`README.md` y `LICENSE`
2. a programar!

## Diferencias con la edición estandar

- sin AcmeDemoBundle
- sin Swiftmailer
- sin twig-extension
- sin Symfony requirement/configuration scripts
- sin extra code/configuration comments
- sin cache kernel
- sin firephp monolog handler
- sin chromephp monolog handler
- Sin archivos markdown de symfony (except `LICENSE` and `README.md`)
* favicons en blanco
* usa PHP 5.3.17+
* vendor binaries in `vendor/bin` instead of `bin`
* uniformized syntax in configuration
+ enabled translator fallback
* FOSRestBundle
* JMSSerializerBundle
* JMSDiExtraBundle
* FOSJsRoutingBundle
* Habilitado filtro para archivos .scss en AsseticBundle

## Further documentation

[Copyright and MIT license](LICENSE).
