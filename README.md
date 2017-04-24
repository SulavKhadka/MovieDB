# MovieDB
A Movie Website made for a database class group project.

### Contributors:
- Sulav Khadka
- Matt Miller
- Harrison Wainright

# Description
For this project we had 2 main components:
- Movie Database
- Website

We created our movie database in MySQL. There were 7 tables in the database:

| Tables_in_movies |
|------------------|
| crew             |
| genre            |
| movies           |
| tags             |
| user_rating      |
| users            |
| watchlist        |

Each table consisted of several columns:

Crew:

| movie_id | position | name                   |
|----------|----------|------------------------|
|        1 |        1 | Tony Scott             |
|        1 |        2 | Don Simpson            |
|        1 |        2 | Jerry Bruckheimer      |
|        1 |        3 | Jim Cash               |
|        1 |        3 | Jack Epps, Jr.         |
|        1 |        4 | Tom Cruise             |
|        1 |        4 | Val Kilmer             |
|        1 |        5 | Chris Lebenzon         |
|        1 |        5 | Billy Weber            |
|        2 |        1 | Tony Bancroft          |
|        2 |        1 | Barry Cook             |
|        2 |        2 | Pam Coats              |
|        2 |        2 | Chris Bender           |
|        2 |        3 | Chris Sanders          |
|        2 |        3 | Philip LaZebnik        |
|        2 |        4 | Mulan                  |
|        2 |        5 | Micheal Kelly          |
|        3 |        1 | John Musker            |
|        3 |        1 | Ron Clements           |
|        3 |        2 | Howard Ashman          |
|        3 |        3 | Roger Allers           |
|        3 |        3 | Gerrit Graham          |
|        3 |        4 | Ariel                  |
|        3 |        5 | Mark Hester            |


Genre:

| movie_id | genre           |
|----------|-----------------|
|        1 | Drama           |
|        1 | Action          |
|        2 | Fantasy         |
|        2 | Comedy          |
|        2 | Drama           |
|        3 | Fantasy         |
|        3 | Romance         |

Movies:

| movie_id | title                    | release_date | duration | language | summary                                                                                                                                                                                              |
|----------|--------------------------|--------------|----------|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | Top Gun                  | 1986-05-16   | 109      | English  | Movie about two best friends who are Naval pilots                                                                                                                                                    |
|        2 | Mulan                    | 1998-06-19   | 88       | English  | Girl disgraces family, but makes up for it big time                                                                                                                                                  |
|        3 | Little Mermaid           | 1989-11-17   | 92       | English  | Mermaid wants legs to date a guy, makes huge mistake                                                    

Tags:

| movie_id | tag        |
|----------|------------|
|        1 | pilot      |
|        1 | friends    |
|        1 | navy       |
|        1 | planes     |
|        1 | war        |
|        2 | animated   |
|        2 | war        |
|        2 | dragon     |
|        2 | daughter   |
|        2 | family     |
|        3 | sing       |
|        3 | love       |
|        3 | voice      |
|        3 | mermaid    |
|        3 | ocean      |


User Rating:

| movie_id | user_id | rating | review                                                 |
|----------|---------|--------|--------------------------------------------------------|
|        2 |       3 |      3 | Great movie really spoke to me                         |
|        2 |       2 |      1 | Not a huge fan of this movie, bad plot                 |
|       10 |       5 |      4 | Fantastic soundtrack on this movie, great!             |
|        8 |       3 |      2 | Cinemetography was forgetfull                          |

