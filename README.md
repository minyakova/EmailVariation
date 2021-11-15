# Приложение для верификации email. 
### Валидация email и проверка DNS mx

####Обращение к классу:
use minyakova\EmailVariation\EmailVariation;
require_once('vendor/autoload.php');

$emailVar = 'Ваш email';

$app = new EmailVariation($emailVar); 
$app->run();


