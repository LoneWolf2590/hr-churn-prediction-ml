# hr-churn-prediction-ml
Employee Churn Prediction using Machine Learning - HR Analytics project

HR Analytics – predykcja zmiany pracy
Krótki projekt pokazujący kompletny przepływ pracy w uczeniu maszynowym dla problemu klasyfikacji w HR: przewidywanie, czy kandydat rozważa zmianę pracy na podstawie profilu (m.in. lokalizacja, wykształcenie, doświadczenie, historia zatrudnienia, szkolenia).

Dane
Wykorzystany zestaw pochodzi z Kaggle: https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists.

Metody i przepływ pracy
EDA zmiennych kategorycznych i numerycznych oraz wstępne czyszczenie.
Przygotowanie danych: obsługa braków, porządkowanie rzadkich kategorii, kodowanie cech kategorycznych, skalowanie cech numerycznych.
Podział na zbiory uczące i walidacyjne ze stratyfikacją oraz ustawienie ziaren losowych dla powtarzalności.
Budowa kilku modeli bazowych (m.in. regresja logistyczna, modele drzewiaste) z prostym strojeniem hiperparametrów.
Ocena jakości i podstawowa interpretacja (np. ważność cech, współczynniki).
Predykcje dla zbioru testowego i zapis wyników.
