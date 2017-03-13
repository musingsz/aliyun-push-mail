```php
 require: 
 "musingsz/aliyun-push-mail":"0.6"
  ```

```php
'aliyun-mail' => [
	'accessKey' => 'XXXXXXXXXXXXXXX', 
	'accessSecret' => 'XXXXXXXXXXXXXXXXXXXXXXXXXXX', 
	'accountName' => 'xxxxxxx@mail.xxxyu.com', 
	'fromAlias' => 'Crewing'
	]
```

```php
use Sanyc\Aliyun\AliyunEmail;

$mail = AliyunEmail::init(Yii::$app->params['aliyun-mail'])->send('xxx@gmial.com', 'title', 'body')
```
