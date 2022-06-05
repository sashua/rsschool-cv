# Alexander Sereda

## Contacts

- **Phone**: +380 958-293-584
- **Email**: sereda.san@gmail.com
- **Discord**: @sashua
- **Location**: Ukraine (ready to relocate)
- [GitHub (sashua)](https://github.com/sashua), [Linked**in** (sashua)](https://linkedin.com/in/sashua)

## Full Stack JavaScript / React Developer

### Summary

## Skills

- HTML, CSS, JavaScript
- Webpack, Sass, SCSS
- React, Redux, React Native
- Node.js, Express
- Python, FastAPI, Flask
- PostgreSQL, MariaDB
- Git, GitHub

### Languages

- **English**: Pre-intermediate
- **Ukrainian**: Native
- **Russian**: Native

## Experience

### 1C Software Developer

**Slavutych-Service** _(Jan 2009 - Aug 2020)_

- Installed, updated, and administrated 1C/BAS software (v.7.7 to v.8.3, configurations for retail and bookkeeping, file and SQL databases)
- Modified standard and non-standard 1C/BAS configurations, creating new printing forms, reports, documents
- Integrated retail equipment with 1C/BAS configurations
- Provided user training and consulting

### IT Specialist

**Slavutych-Service** _(Mar 2006 - Dec 2008)_

- Installed and administrated OS Windows, application software
- Engineered, installed, configured and administrated Local Area Networks (TCP/IP, DHCP, DDNS, VPN)
- Connected to customer PC and configured retail and office equipment (cash register, scales, data collection terminals, printers, etc.)
- Engineered, installed and configured video surveillance systems

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
