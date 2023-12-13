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
                'company' => 'SWM - Stadtwerke München',
                'position' => 'Cloud Engineer',
                'fuel' => 'Espresso Shots' 
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Terraform::class,
            Bash::class,
            Gitlab::class,
            Docker::class,
            Azure::class,
            AWS::class,
            GoogleCloudServices::class,
            CommandLine::class,
            CICD::class
        ];
    }

    public function getLegacyKnowledge(): array
    {
        return [
            Php::class,
            Zend::class,
            Symfony::class,
            SoftwareArchitecture::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Beeing a part of changing the world to a greener and more sustainable future, while still trying to spark the joy of IT in my apprentices ;)';
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
