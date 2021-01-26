### Hi there - i'm Bernhard 👋

```php
<?php

namespace Roizan;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Seitwerk',
                'position' => 'Senior Software & Systems Engineer - Instructor',
                'fuel' => 'Espresso Shots' 
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Zend::class,
            Symfony::class,
            Bash::class,
            Gitlab::class,
            Docker::class,
            Azure::class,
            CommandLine::class,
            CICD::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Spark the joy of IT in my apprentices ;)';
    }
    
    public function getSportsAndHobbies(): array
    {
        return [
            CrossFit::class,
            Rowing::class,
            Motorcycles::class
        ];
    }
}
```

:motorcycle: :motorcycle: :motorcycle: 
