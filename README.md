# drupal8-dockerized

1. Instala Drupal con composer en la ruta drupal/
2. Cambia los accesos en el archivo docker.env
3. Modifica el archivo settings de esta forma:
  'database' => getenv('MYSQL_DATABASE'),
  'username' => getenv('MYSQL_USER'),
  'password' => getenv('MYSQL_PASSWORD'),

1. Install Drupal with composer in drupal/ path
2. Change the credentials in the docker.env file
3. Modify the file settings like this:
  'database' => getenv('MYSQL_DATABASE'),
  'username' => getenv('MYSQL_USER'),
  'password' => getenv('MYSQL_PASSWORD'),