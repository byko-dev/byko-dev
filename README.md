![MasterHead](https://camo.githubusercontent.com/ba9f3bd30647e352a3f5e1e45eb45c6ec7bad6155cd16aaedf4a426738da0ca5/68747470733a2f2f696e646f616e616c79746963612e636f6d2f7374617469632f696d616765732f62616e6e6572722e676966)

```php
<?php

namespace BykoDev;

class About extends Me
{
    public function getInfo(): array
    {
        return [
            'name' => 'Kacper Nowak',
            'contact' => [
                'email' => 'byko.dev@gmail.com',
                'linkedin' => 'https://www.linkedin.com/in/byko-dev/'         
            ],
            'portfolio' => 'https://byko-dev.github.io/'
        ];
    }

    public function getSkills(): array
    {
        return [
            Java::class,
            Javascript::class,
            SpringBoot::class,
            ReactJS::class,
            Laravel::class,
            Php::class,
            Docker::class,
            Bootstrap::class,
            PostgreSQL::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

### 📊 GitHub Stats:
<p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=byko-dev&show_icons=true&theme=dark&locale=en&layout=compact" alt="byko-dev" /></p>

<p align="center"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=byko-dev&theme=dark" alt="byko-dev" /></p>
<p align="center"> <img src="https://komarev.com/ghpvc/?username=byko-dev&label=Profile%20views&color=0e75b6&style=flat" alt="byko-dev" /> </p>
