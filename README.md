# Descrição
Este é um simples CRUD via linha de comando para cadastro de clientes 
usando apenas PHP e a ORM Doctrine para a manipulação de entidates e bancos de dados.

## Como executar a aplicação
Para executar a aplicação é necesserio apenas  realizar a instalação dos requisitos via composer com o comando:

```composer install```

Em seguida é necessário criar o banco dados através do comando:

```vendor/bin/doctrine orm:schema-tool:create```

E a partir disso para inicie a aplicação através do comando:

```php aplication.php```

Caso alguma alteração seja realizada você pode tambêm checar se seu código está seguindo 
os padrões PSR2 através do comando:

```composer run phpcs```

## Requerimentos
- PHP ^7.2.27
- Composer
- Doctrine 2.7
- JMS Serializer ^3.8
