# Investigating Fandango Movie Ratings
🇬🇧
## Overview

This project investigates the discrepancies in movie ratings on the Fandango platform compared to ratings from other sources such as Rotten Tomatoes, IMDB, and Metacritic. By analyzing and visualizing the data, we aim to determine whether Fandango inflated ratings for certain movies.

## Data

The project uses two CSV files:  
- **fandango.csv**: Contains Fandango's movie ratings and votes.  
- **all_sites.csv**: Contains ratings from Rotten Tomatoes, IMDB, and Metacritic.

## Methodology

1. **Data Cleaning**: We cleaned and normalized the ratings across different platforms to a common scale of 0-5.
2. **Data Analysis**: We explored the distribution of ratings, compared platforms, and visualized the differences.
3. **KDE & Distribution**: We visualized the distribution of ratings and identified discrepancies between Fandango and other platforms.

## Key Findings

Fandango consistently displayed ratings of 3-4 stars for films that were clearly underperforming. This suggests that Fandango might have inflated ratings to encourage ticket sales for poorly rated movies.

## Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib

## Installation

```bash
pip install -r requirements.txt
```

# Исследование рейтингов Fandango
🇷🇺
## Обзор

Этот проект исследует различия в рейтингах фильмов на платформе Fandango по сравнению с рейтингами с других источников, таких как Rotten Tomatoes, IMDB и Metacritic. Анализируя и визуализируя данные, мы пытаемся определить, завышал ли Fandango рейтинги для некоторых фильмов.

## Данные

Для проекта использовались два CSV-файла:  
- **fandango.csv**: Содержит рейтинги и количество голосов на Fandango.  
- **all_sites.csv**: Содержит рейтинги с Rotten Tomatoes, IMDB и Metacritic.

## Методология

1. **Очистка данных**: Мы очистили и нормализовали рейтинги на разных платформах до общей шкалы от 0 до 5.
2. **Анализ данных**: Мы исследовали распределение рейтингов, сравнили платформы и визуализировали различия.
3. **KDE и распределение**: Мы визуализировали распределение рейтингов и выявили различия между Fandango и другими платформами.

## Основные выводы

Fandango часто показывал рейтинги 3-4 звезды для фильмов, которые явно были неудачными. Это указывает на то, что Fandango мог завышать рейтинги, чтобы стимулировать продажи билетов для плохо оценённых фильмов.

## Требования

- Python 3.x
- pandas
- seaborn
- matplotlib

## Установка

```bash
pip install -r requirements.txt
```
