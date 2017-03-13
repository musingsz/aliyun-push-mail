

```php
'mail' => [
	'accessKey' => 'gw9QdAXXXYjR1Uu', 
	'accessSecret' => 'dyOOXvXXXXXXXXAgr7hXJCr5wdBDd', 
	'accountName' => 'xxxxxxx@m.shsytour.cn', 
	'fromAlias' => 'Crewing'
	]
```

```php
use Sanyc\Aliyun\AliyunEmail;

$mail = AliyunEmail::init(config('mail'))->send('123456@qq.com', 'title', 'body');
```
