# DjangoBlog

- OS X / Linux 

    ```
    curl http://peak.telecommunity.com/dist/ez_setup.py | python
    curl https://bootstrap.pypa.io/get-pip.py | python
    ```

- Windows

    http://peak.telecommunity.com/dist/ez_setup.py 和 https://raw.github.com/pypa/pip/master/contrib/get-pip.py


```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'djangoblog',
        'USER': 'root',
        'PASSWORD': 'password',
        'HOST': 'host',
        'PORT': 3306,
    }
}
```
