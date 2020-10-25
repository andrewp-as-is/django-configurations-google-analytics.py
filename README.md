<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-configurations-google-analytics.svg?maxAge=3600)](https://pypi.org/project/django-configurations-google-analytics/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-configurations-google-analytics.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-configurations-google-analytics.py/actions)

### Installation
```bash
$ [sudo] pip install django-configurations-google-analytics
```

##### `settings.py`
```python
from configurations import Configuration
from django_configurations_google_analytics import GoogleAnalyticsMixin

class Base(GoogleAnalyticsMixin,Configuration):
    # GA_ID = 'UA-XXXXXXXX-Y'
```

##### `.env`
```bash
DJANGO_GA_ID="UA-XXXXXXXX-Y"
```

##### Templates
```html
{% load google_analytics %}
...
{% google_analytics %}
```

#### Links
+   [django-configurations](https://github.com/jazzband/django-configurations)

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
