# Symfony3Redis

Simple Example Redis with Symfony 3.3

## Install with Composer

```
    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar install or composer install
```

## Getting Redis on URL

Set persistent key: ```http://127.0.0.1:8000/redis/set?key=a&value=1```

Set non-persistent key: ```http://127.0.0.1:8000/redis/set?key=a&value=1&ttl=10```

Get key's value: ```http://127.0.0.1:8000/redis/get?key=a```

Get key's TTL: ```http://127.0.0.1:8000/redis/ttl?key=a```

Make key persistent: ```http://127.0.0.1:8000/redis/persist?key=a```

Delete key: ```http://127.0.0.1:8000/redis/delete?key=a```

Expire key (TTL optional): ```http://127.0.0.1:8000/redis/expire?key=a&ttl=10```

