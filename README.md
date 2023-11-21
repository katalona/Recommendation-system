
# Цели
В этом проекте показано знакомство с рекомендательными системами и алгоритмами для их построения.

Для построения системы рекомендаций фильмов были использованы данные [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
Описание датасетов можно найти [здесь](Recommendation-system/datasets/README.md)


## Предобработка данных
* Данные о фильмах [tmdb_5000_movies](Recommendation-system/datasets/tmdb_5000_movies.csv) и каст фильмов [tmdb_5000_credits](Recommendation-system/datasets/tmdb_5000_credits.csv) объединены и оставлены только те фильмы, которые вышли в "релиз".

## Алгоритмы для построения рекомендательных систем

### На основе оценок пользователей

### На основе содержания(Content Based Filtering)

Использована библиотека scikit-learn

### На основе сходства между пользователями(Collaborative Filtering)

Использована библиотека surprise

