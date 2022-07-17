<!-- Your title -->
## Hi, I'm Luis Fernando, a Developer 🚀 from Brazil.

<!-- Your badges
You can use the website to generate badges: https://shields.io/
-->

<div align="center">
  https://img.shields.io/github/followers/Manrriquez?style=social
</div>

&nbsp;




```php
<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
