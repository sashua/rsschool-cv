# Alexander Sereda

## Contacts

- **Phone**: +380 958-293-584
- **Email**: sereda.san@gmail.com
- **Discord**: @sashua
- **Location**: Ukraine (ready to relocate)
- [GitHub (sashua)](https://github.com/sashua), [Linked**in** (sashua)](https://linkedin.com/in/sashua)

## Full Stack JavaScript / React Developer

## Skills

- HTML, CSS, JavaScript
- Webpack, Sass, SCSS
- React, Redux, React Native
- Node.js, Express
- Python, FastAPI, Flask
- RESTful API, JSON API, gRPC
- PostgreSQL, MariaDB
- Git, GitHub

### Languages

- **English**: Pre-intermediate
- **Ukrainian**: Native
- **Russian**: Native

## Experience

### 1C Software Developer

**Slavutych-Service** _(Jan 2009 - Aug 2020)_

### Embedded Software Developer

**Slavutych-Service** _(Mar 2006 - Dec 2008)_

### IT Specialist

**Slavutych-Service** _(Oct 2005 - Feb 2006)_

## Education

### Master of Science in Electronics

**Kharkiv National University of Radio Electronics** _(Sep 2000 - Jul 2005, Kharkiv, Ukraine)_

## Projects

### RS-School CV#1. Markdown & Git

[CV in markdown](https://sashua.github.io/rsschool-cv/cv)

### Code example

```python
import csv
from collections import namedtuple

class FancyReader:
    def __init__(self, lines, fieldnames=None):
        self.reader = csv.reader(lines)
        self.Row = namedtuple('Row', ' '.join(fieldnames or next(self.reader)))
        self.line_num = 0 if fieldnames else 1

    def __iter__(self):
        return self

    def __next__(self):
        self.line_num += 1
        return self.Row(*next(self.reader))
```
