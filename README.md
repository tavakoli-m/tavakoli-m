## Hi, I'm `Mohammad Reza Tavakoli` (FullStack Developer) <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50">

```php
<?php

use Tavakoli;

class About extends Tavakoli
{
    public string $name = "Mohammadreza";

    public int $age = 18;

    public function Languages(): array
    {
        return [
            HTML::class,
            CSS::class,
            JAVASCRIPT::class,
            TYPESCRIT::class,
            PHP::class,
        ];
    }

    public function Databases(): array
    {
        return [
            MySql::class,
            Redis::class,
        ];
    }

    public function Frameworks() : array
    {
        return [
            Laravel::class,
            NextJs::class,
            LiveWire::class
        ]
    }

    public function Libraries() : array
    {
        return [
            React::class,
            TailwindCss::class,
            ReactQuery::class
        ]
    }

    public function Tools() : array
    {
        return [
            Git::class,
            GitHub::class,
            Docker::class
        ]
    }
}
```
