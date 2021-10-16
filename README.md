### Hi there 👋
### Here's A little about me👽
```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    name: str = 'Laban Kiplagat'
    location: str = 'Nairobi Kenya'
    profile: str = 'Python-Django Developer, Linux User, React Dev'
    experience: str = '3+ years'
    hobbies: Sequence[str] = 'Novels', 'Coffee', 'open source', 'clean code'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'python', 'shell', 'dart', 'JavaScript',
    operation_systems: Sequence[str] = 'linux', 'Unix'
    test_frameworks: Sequence[str] = 'pytest', 'pyats', 'unittests', 'doctest', 'selenium', 'celery'
    web_frameworks: Sequence[str] = 'flask', 'django','django rest-framework', 'react.js'
    code_quality: Sequence[str] = 'flake8', 'mypy', 'pylint', 'black', 'pydocstyle'
    devops: Sequence[str] = 'jenkins', 'travis', 'docker'
    version_control: Sequence[str] = 'git'
    approaches: Sequence[str] = 'object oriented', 'asyncio'
    ongoing: Sequence[str] = 'vue.js'


@dataclass(frozen=True)
class Social:
    github: str = 'https://www.github.com/labohkip81'
    codewars: str = 'https://www.codewars.com/users/labohkip81'
    twitter: str = 'https://twitter.com/kiplagat_laban'
    linkedin: str = 'https://www.linkedin.com/in/labohkip81'
    portfolio: str = 'https://labohkip81.github.io'
    email: str = 'labankiplagat81@gmail.com' 
  
 ````
