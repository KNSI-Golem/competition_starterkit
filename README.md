# competition_starterkit
StarterKit na konkursy wewnątrzkołowe (in progress)

## konfiguracja środowiska

https://github.com/KNSI-Golem/GolemBootcamp2020 analogicznie jak tutaj, plik `requirements.txt` jest tylko do tego sample notebooka, jeśli potrzebujecie więcej paczek (np. pytorcha) to możecie je zainstalować za pomocą `pip install <nazwa_paczki na pypi.org>`

## instrukcja do kodu i struktury

```
code
|
|---data
|   |---test.csv
|   |---train.csv
|
|---kaggle_output
|   |---sample_submission.csv
|
|---sample_notebook.ipynb
```

### data

Csvka `train.csv` zawiera wszystkie dane, z których możecie skorzystać do trenowania Waszych modeli predykcyjnych
Dane z `test.csv` posłużą jako wejście do Waszych modeli, output z nich musi mieć taki kształt jak w `kaggle_output/sample_submission.csv`

### kaggle_output

Plik `sample_submission.csv` zawiera przykładowy output Waszych modeli, który macie wysłać jako rozwiązanie w konkursie

### sample_notebook.ipynb

Prosty notebook ładujący dane, przepuszczający je przez prosty model i wrzucające je do pliku `sample_submission_2.csv` (nieumieszczone na repo)

## instrukcja do kaggla

Link: https://www.kaggle.com/t/f81a890cfa014f96920352982f488cab
Kaggle jest bardzo prosty i przyjemny w obsłudze. Wystarczy założyć konto, wejść w link, pobrać dane (które już macie tu na repo), a gdy przyjdzie wrzucać rozwiązania – wrzucacie plik o takiej strukturze, jaką generuje Wam notebook. Można wrzucać 4 rozwiązania na dobę. Have fun!
