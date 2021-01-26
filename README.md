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
                'position' => 'Software & Systems Engineer - Instructor'         
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
            Docker::class,
            Azure::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Spark the joy of IT in my apprentices ;)';
    }
}
```

