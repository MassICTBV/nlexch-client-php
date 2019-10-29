nlexch-client-php
==============

A simple PHP client for Crypto Trade Site NLexch.com

Quick example
=============

```php

<?php
require_once('lib/nlexch-client.php');

try {
  $client = new NLexchClient(array(
                  'access_key' => 'Your access key',
                  'secret_key' => 'Your secret key'
            ));
  //var_dump($client->get('/api/v2/markets.json');
  //var_dump($client->get('/api/v2/members/me.json'));
  //var_dump($client->post('/api/v2/order/delete.json',['id' => 1]));
}
catch (Exception $e) {
  die($e);
}

```

API Document
=============

[API_v2](https://www.nlexch.com/documents/api-v2)
