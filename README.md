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
                'company' => '奇艺集团',
                'position' => 'Software Engineer Front-End'         
            ]
        ];
    }

    public function getTechnologies(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            Vuejs::class,
            ReactJS::class,
            TailwindCss::class,
            Bootstrap::class,
            Materialize::class,
            Css::class,
            Less::class
            Sass::class,
        ];
    }
    
    public function getTools(): array
    {
       return [
         Insomnia::class,
         Postman::class,
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
  
 
