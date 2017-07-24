# drupal-console-pt-br
DrupalConsole Brazilian Portuguese Language / En Portugués de Brasil

# Versão em Português Brasileiro

## Uso

O projeto Drupal Console é instalado para cada site Drupal 8 com idioma inglês por padrão.

Para instalar o pacote Drupal Console para o idioma PT_BR, execute as seguintes instruções:

```
$ composer require drupal/console-pt-br
```

### Instalar Drupal Console

Para instalar a versão apropriada do projeto Drupal Console para sua instalação drupal, execute o seguinte comando do composer

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Instale o launcher do Drupal Console

Para evitar conflitos entre o lançamento do Drupal e ter uma versão do Drupal Console entre lançamentos importantes e menores no Drupal, um launcher do Drupal Console foi criado, para facilitar o carregamento dos comandos do Drupal Console disponíveis para cada site Drupal 8.
 
Seguindo as instruções abaixo, você pode instalar o aplicativo global para o launcher do Drupal Console.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribuir

Se você quiser contribuir com esta tradução, você deve seguir estes passos

- Fork este repositório seguindo este link [https://github.com/hechoendrupal/drupal-console-pt-br#fork-destination-box](https://github.com/hechoendrupal/drupal-console-pt-br#fork-destination-box)
- Clone seu repositório 'forkado' em sua máquina local.
- Set up upstream

Para ser atualizado com outra contribuição você deve configurar um repositório conectado com o principal usando o seguinte comando git: 

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-pt-br.git
```

Para obter a última contribuição antes para começar, você deve executar os próximos comandos:
```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push suas alterações em seu repositório 'forkado' para criar um PR por dia para evitar conflitos com outros contribuidores.

# English Version

Check instructions at [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)