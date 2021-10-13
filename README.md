Run tests:
```shell
vendor/bin/phpunit tests/Functional/
```
## How to configure Symfony

Add to config/services.yaml
```yaml
    YaPro\DoctrineConverter\:
        resource: '../vendor/yapro/doctrine-converter/src/*'
    YaPro\Helper\:
        resource: '../vendor/yapro/helpers/src/*'
```
