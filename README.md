Console.class.php
=================

All of Firefox(/Chrome)'s console functions


Usage:

```php
Console::time('test');
Console::log('test%ding', 22);
Console::dir($_SERVER);
Console::log('test%cing', 'color: teal');
Console::trace();
Console::timeEnd('test');
```

Here's what that would look like in Chrome

![Console.class.php output](http://i.imgur.com/vf9kUWW.png)