<div align="start">
  
    
```php
<?php

namespace Manrriquez;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Default',
                'position' => 'Default'         
            ]
        ];
    }

    public function getTechnologies(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            Jquery::class,
            Vuejs::class,
            ReactJS::class,
            TailwindCss::class,
            Bootstrap::class,
            Html::class,
            Css::class,
            Sass::class,
        ];
    }
    
    public function getTools(): array
    {
       return [
         Insomnia::class,
         HeidSql::class,
         PhpStorm::class,
       ];
    }
    
    public function getSO(): array
    {
       return [
         Windows::class,
         Linux::class,
       ];
    }
    
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
  
  </div>
  
 
