# fsYamlPlugin
Plugin para usar el formato YAML en Framework Studio basado en el componente sfYaml (v3.0.0) de Symfony

## Ejemplo de uso
```php
<?php
use Symfony\Component\Yaml\Parser;

$model = $yaml->parse(file_get_contents('config/model.yml'));
var_dump($modelo);
```
El resultado sería la impresión de un arreglo con el contenido dispuesto en ```model.yml```. Para más información consultar los siguientes enlaces:

- [https://github.com/symfony/yaml](https://github.com/symfony/yaml)
- [http://symfony.com/doc/3.0/components/yaml/index.html](http://symfony.com/doc/3.0/components/yaml/index.html)
