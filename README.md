# APD – Laborator

Proiect de laborator pentru disciplina Achiziția și prelucrarea datelor.
Nod de achiziție a temperaturii bazat pe Arduino Uno.

## Autor

Bulearca Mihnea-Stefan Grupa I

## Hardware

Arduino Uno R3, senzor de temperatură TMP36

## Note

Parolele și cheile de acces nu trebuie să ajungă niciodată într-un repository, chiar dacă acesta este privat pentru ca poate expune datele oricarui colaborator de catre un hacker care iti poate sparge contul.

## Parametri

- **`SENSOR_PIN`** (`A0`) – Definește pinul de intrare analogică la care este conectat senzorul.
- **`SAMPLE_PERIOD_MS`** (`500`) – Perioada de eșantionare exprimată în milisecunde (frecvența de citire a datelor de la senzor).
- **`SERIAL_BAUD`** (`9600`) – Viteza de comunicație pe portul serial (exprimată în bauds / biți pe secundă).
- **`LED_PIN`** (`13`) – Definește pinul digital la care este conectat LED-ul de stare.
Comunicație serială la 19600 baud