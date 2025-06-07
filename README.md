# audio-aed-mfcc-rf
Lab 2 Sergeeva
# Audio Event Detection with MFCC and Random Forest

## Задача

Распознавание звуковых событий по аудиофайлам с использованием MFCC-признаков и классификатора Random Forest. Звуковые события взяты из набора UrbanSound8K.

## Использованные признаки

- **MFCC (Mel-Frequency Cepstral Coefficients)** — извлечены из аудиофайлов
- Статистические характеристики (среднее, стандартное отклонение и др.)

## Классификаторы

- Random Forest
- Подбор гиперпараметров с помощью GridSearchCV

## Результаты

- F1 score на тренировочной выборке: **1.0**
- F1 score на валидации после настройки: **~0.49**

## Содержимое

- `audio_aed_rf_mfcc.ipynb` — ноутбук с кодом и экспериментами
- `features/features_mfcc.pkl` — сохранённые MFCC-признаки
- `models/rf_model.pkl` — обученная модель Random Forest
