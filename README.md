

```php
'aliyun-mail' => [
	'accessKey' => 'gw9QdAXXXYjR1Uu', 
	'accessSecret' => 'dyOOXvXXXXXXXXAgr7hXJCr5wdBDd', 
	'accountName' => 'xxxxxxx@mail.xxxyu.com', 
	'fromAlias' => 'Crewing'
	]
```

```php
use Sanyc\Aliyun\AliyunEmail;

$mail = AliyunEmail::init(Yii::$app->params['aliyun-mail'])->send('xxx@gmial.com', 'title', 'body')
```
