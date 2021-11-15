# Приложение для верификации email. 
### Валидация email и проверка DNS mx

####Установка:
composer require minyakova/test-composer-package

####Обращение к классу:
use minyakova\EmailVariation\EmailVariation;
require_once('vendor/autoload.php');

$emailVar = 'Ваш email';

$app = new EmailVariation($emailVar); 
$app->run();


