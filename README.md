```php
<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'HuyNC',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            'PHP',
            'C++',
            'Java',
            'Javascript',
            'Typescript',
            'Laravel',
            'CodeIgniter',
            'VueJS',
            'ReactJS',
            'TailwindCSS',
            'MySQL',
            'SQLite',
            'MongoDB',
            'Redis',
            'Aws',
            'NodeJS',
            'Spring',
            'ExpressJS'
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Earn more money';
    }
}
```
