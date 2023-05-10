# Demographic Analysis of the Academy Award Nominations

Using two different datasets, ’The Oscar Award’ and ’Academy Awards Demographics’, three networks
were created in order to see how movies, actors, and directors are related to each other.

## Datasets

1. The Oscar Award Dataset

The Oscar Award dataset consists of records scraped from the Academy Award Database and is freely
available on Kaggle website. It contains all nominees and award winners since the first ceremony in 1927 until
92nd ceremony in 2020. Original dataset, before preprocessing, has 10395 entries which include numerous
nominees sorted by the year of the ceremony in the ascending order. As shown in the OscarAward (EDA) Python notebook, dataset contains 7 features which
are:

*  ’year_film’ - the year when the movie was released
*  ’year_ceremony’ - the year when the ceremony was held
*  ’ceremony’ - the number of the ceremony
*  ’category’ - the category in which person/movie/organization was nominated
*  ’name’ - the full name of the nominee
*  ’film’ - the name of the movie
*  ’winner’ - holds value ’True’ if nominee won an award, and ’False’ otherwise


2. Academy Awards Demographics Dataset

The Academy Awards Demographics dataset is freely available on data.world website; moreover, it contains
demographic information of the winners of Academy Award in various categories since 1928 as shown in the Demographics(EDA) notebook. It has 27
variables and some of them include information about religion, race, age, sexual orientation, etc. The winners
that are considered are the winners in the following categories: Best Actor, Best Actress, Best Supporting
Actor, Best Supporting Actress, and Best Director.


## Networks and Their Properties

The networks were built using Python NetworkX Library (Demographics(Winners Network),Oscar Award(Film Network), and Oscar Award(Person Network) notebooks) as well as Gephy software.
![image](https://github.com/sarakartalovic/The-Academy-Award-Network-Analysis/assets/83169121/94c40ca6-2d8f-4e8c-86a2-7a959ad61f35)
![image](https://github.com/sarakartalovic/The-Academy-Award-Network-Analysis/assets/83169121/25edafc9-5ad5-4352-b3c2-32dfe2e0b3c1)
![image](https://github.com/sarakartalovic/The-Academy-Award-Network-Analysis/assets/83169121/4de9e334-b9b8-4967-8f6b-880f0d71f8b2)
