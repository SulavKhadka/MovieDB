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
|        4 |        1 | Victor Fleming         |
|        4 |        1 | Mervyn LeRoy           |
|        4 |        2 | William Horning        |
|        4 |        3 | Bert Lahr              |
|        4 |        3 | Jack Haley             |
|        4 |        4 | Judy Garland           |
|        4 |        4 | Ray Bolger             |
|        4 |        5 | Blanche Sewell         |
|        5 |        1 | John McTiernan         |
|        5 |        2 | Joel Silver            |
|        5 |        3 | Jeb Stuart             |
|        5 |        3 | Steve Souza            |
|        5 |        4 | Bruce Willis           |
|        5 |        4 | Alan Rickman           |
|        5 |        5 | Frank Urioste          |
|        6 |        1 | Richard Donner         |
|        6 |        2 | Joel Silver            |
|        6 |        3 | Jeffrey Boam           |
|        6 |        3 | Robert Kamen           |
|        6 |        4 | Mel Gibson             |
|        6 |        4 | Danny Glover           |
|        6 |        5 | Battle Davis           |
|        7 |        1 | John Lee Hancock       |
|        7 |        2 | Gil Netter             |
|        7 |        3 | John Lee Hancock       |
|        7 |        4 | Sandra Bullock         |
|        7 |        4 | Tim McGraw             |
|        7 |        5 | Mark Livolsi           |
|        8 |        1 | Peter Barsocchini      |
|        8 |        2 | Don Schain             |
|        8 |        3 | Gordon Lonsdale        |
|        8 |        4 | Zac Efron              |
|        8 |        4 | Vanessa Hudgens        |
|        8 |        5 | Seth Flaum             |
|        9 |        1 | Roger Allers           |
|        9 |        2 | Don Hahn               |
|        9 |        3 | Irene Mecchi           |
|        9 |        4 | Matthew Broderick      |
|        9 |        4 | James Earl Jones       |
|        9 |        5 | Ivan Bilancio          |
|       10 |        1 | Stephen Herek          |
|       10 |        2 | John Hughes            |
|       10 |        3 | John Hughes            |
|       10 |        4 | Glenn Close            |
|       10 |        4 | Jeff Daniels           |
|       10 |        5 | Trudy Ship             |
|       11 |        1 | Francis Coppola        |
|       11 |        2 | Albert Ruddy           |
|       11 |        3 | Mario Puzo             |
|       11 |        4 | Marlon Brando          |
|       11 |        4 | Al Pacino              |
|       11 |        5 | Peter Zinner           |
|       12 |        1 | Frank Darabont         |
|       12 |        2 | Niki Marvin            |
|       12 |        3 | Stephen King           |
|       12 |        4 | Tim Robbins            |
|       12 |        4 | Morgan Freeman         |
|       12 |        5 | Richard Bruce          |
|       13 |        1 | Christopher Nolan      |
|       13 |        2 | Emma Thomas            |
|       13 |        3 | Jonathan Nolan         |
|       13 |        4 | Christian Bale         |
|       13 |        4 | Micheal Caine          |
|       13 |        5 | Lee Smith              |
|       14 |        1 | Sidney Lumet           |
|       14 |        2 | Henry Fonda            |
|       14 |        3 | Reginald Rose          |
|       14 |        4 | Henry Fonda            |
|       14 |        4 | Lee Cobb               |
|       14 |        5 | Carl Lerner            |
|       15 |        1 | Steven Spielberg       |
|       15 |        2 | Steven Spielberg       |
|       15 |        3 | Steven Zaillian        |
|       15 |        4 | Ben Kingsley           |
|       15 |        4 | Liam Neeson            |
|       15 |        5 | Micheal Kahn           |
|       16 |        1 | Quentin Tarantino      |
|       16 |        2 | Lawrence Bender        |
|       16 |        3 | Quentin Tarantino      |
|       16 |        4 | John Travolta          |
|       16 |        4 | Uma Thurman            |
|       16 |        5 | Sally Menke            |
|       17 |        1 | David Fincher          |
|       17 |        2 | Art Linson             |
|       17 |        3 | Jim Uhls               |
|       17 |        4 | Brad Pitt              |
|       17 |        4 | Edward Norton          |
|       17 |        5 | James Haygood          |
|       18 |        1 | Robert Zemeckis        |
|       18 |        2 | Steve Tisch            |
|       18 |        3 | Eric Roth              |
|       18 |        4 | Robin Wright           |
|       18 |        4 | Tom Hanks              |
|       18 |        5 | Arthur Schmidt         |
|       19 |        1 | Christopher Nolan      |
|       19 |        2 | Emma Thomas            |
|       19 |        3 | Christopher Nolan      |
|       19 |        4 | Leonardo DiCaprio      |
|       19 |        4 | Ellen Page             |
|       19 |        5 | Lee Smith              |
|       20 |        1 | Martin Scorsese        |
|       20 |        2 | Irwin Winkler          |
|       20 |        3 | Martin Scorsese        |
|       20 |        4 | Robert De Niro         |
|       20 |        4 | Ray Liotta             |
|       20 |        5 | Thelma Schoonmaker     |
|       21 |        1 | Jonathan Demme         |
|       21 |        2 | Kenneth Utt            |
|       21 |        3 | Ted Tally              |
|       21 |        4 | Jodie Foster           |
|       21 |        4 | Anthony Hopkins        |
|       21 |        5 | Craig McKay            |
|       22 |        1 | The Wachowski Brothers |
|       22 |        2 | Joel Silver            |
|       22 |        3 | The Wachowski Brothers |
|       22 |        4 | Laurence Fishburne     |
|       22 |        4 | Keanu Reeves           |
|       22 |        5 | Zach Staenberg         |
|       23 |        1 | Christopher Nolan      |
|       23 |        2 | Emma Thomas            |
|       23 |        3 | Jonathan Nolan         |
|       23 |        4 | Matthew McConaughey    |
|       23 |        4 | Anne Hathaway          |
|       23 |        5 | Lee Smith              |
|       24 |        1 | Frank Darabont         |
|       24 |        2 | David Valdes           |
|       24 |        3 | Frank Darabont         |
|       24 |        4 | Tom Hanks              |
|       24 |        4 | David Morse            |
|       24 |        5 | Rachard Bruce          |
|       25 |        1 | Steven Spielberg       |
|       25 |        2 | Frank Marshall         |
|       25 |        3 | Lawrence Kasdan        |
|       25 |        4 | Harrison Ford          |
|       25 |        4 | Karen Allen            |
|       25 |        5 | Micheal Kahn           |
|       26 |        1 | Ridley Scott           |
|       26 |        2 | Douglas Wick           |
|       26 |        3 | David Franzoni         |
|       26 |        4 | Russell Crowe          |
|       26 |        4 | Joaquin Phoenix        |
|       26 |        5 | Pietro Scalia          |
|       27 |        1 | Christopher Nolan      |
|       27 |        2 | Suzanne Todd           |
|       27 |        3 | Christopher Nolan      |
|       27 |        4 | Guy Pearce             |
|       27 |        4 | Carrie Moss            |
|       27 |        5 | Dody Dorn              |
|       28 |        1 | Mel Gibson             |
|       28 |        2 | Mel Gibson             |
|       28 |        3 | Randall Wallace        |
|       28 |        4 | Mel Gibson             |
|       28 |        4 | Sophie Marceau         |
|       28 |        5 | Steven Rosenblum       |
|       29 |        1 | Guy Ritchie            |
|       29 |        2 | Matthew Vaughn         |
|       29 |        3 | Guy Ritchie            |
|       29 |        4 | Brad Pitt              |
|       29 |        4 | Dennis Farina          |
|       29 |        5 | Jon Harris             |
|       30 |        1 | James Gunn             |
|       30 |        2 | Kein Feige             |
|       30 |        3 | James Gunn             |
|       30 |        4 | Chris Pratt            |
|       30 |        4 | Zoe Saldana            |
|       30 |        5 | Fred Raskin            |

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
|        4 | Fantasy         |
|        4 | Adventure       |
|        5 | Thriller        |
|        5 | Action          |
|        6 | Thriller        |
|        6 | Action          |
|        7 | Drama           |
|        7 | Sport           |
|        8 | Drama           |
|        8 | Music           |
|        9 | Drama           |
|        9 | Music           |
|       10 | Drama           |
|       10 | Adventure       |
|       11 | Crime           |
|       11 | Action          |
|       12 | Action          |
|       12 | Crime           |
|       13 | Crime           |
|       13 | Action          |
|       14 | Crime           |
|       14 | Justice         |
|       15 | Thriller        |
|       15 | Drama           |
|       16 | Crime           |
|       16 | Drama           |
|       17 | Action          |
|       17 | Drama           |
|       18 | Drama           |
|       18 | Comedy          |
|       19 | Action          |
|       19 | Thriller        |
|       20 | Crime           |
|       20 | Thriller        |
|       21 | Horror          |
|       21 | Thriller        |
|       22 | Action          |
|       22 | Drama           |
|       23 | Drama           |
|       23 | Science Fiction |
|       24 | Mystery         |
|       24 | Crime           |
|       25 | Action          |
|       25 | Adventure       |
|       26 | Action          |
|       26 | Adventure       |
|       27 | Thriller        |
|       27 | Mystery         |
|       28 | Action          |
|       28 | War             |
|       29 | Comedy          |
|       29 | Thriller        |
|       30 | Action          |
|       30 | Superhero       |
