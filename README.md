# Kommandos

```Bash
# Django Version prüfen
$  py -m django --version
```

```Bash
# Virtuelle Umgebung erstellen
$ pipenv shell
```

```Bash
# Django installieren
$ pipenv install django
```

```Bash
# Projekt erstellen
$ django-admin.py startproject Projektname
```

```Bash
# Server starten
$ python manage.py runserver
```

```Bash
# Applikation erstellen
$ python manage.py startapp_news
```

```Bash
# Migration Datei erstellen
$ python manage.py makemigrations
```

```Bash
# Migration ausführen
$ python manage.py migrate
```

```Bash
# Admin erstellen
$ python manage.py createsuperuser
```

# Arbeiten mit der pipenv shell
```Bash
# Abfrage von Datensätzen
$ Meldung.objects.all()
$ umfrage = Meldung.objects.get(title="Umfrage zu Python")
$ umfrage.kommentar_set.all()
$ Kommentar.objects.filter(meldung__id = 6)
```
