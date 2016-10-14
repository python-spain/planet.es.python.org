# Instlación del planet desde cero

```
$ cd /path/to/yourenvs/
$ virtualenv planet
$ . planet/bin/activate
(env)$ pip install -r requirements.txt
```

# Construyendo el planet en el directorio build/

```
(env)$ rawdog -Wuvw -d .
```

# Cron

```
# Rawdog
*/30    *       *       *       *       cd /home/www/planet.es.python.org ; . env/bin/activate ; cd src ; rawdog -Wuvw -d .
```