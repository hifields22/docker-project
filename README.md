# Study Blog

### This is an application designed to helps users study a particular subject by using flashcards and discussing topics with other users. 

| Endpoint paths | Methods            | Parameters                  |
| -----------    | -----------        | -----------                 |
| /posts         | GET, POST          | post, userId                |
| /posts/id      | GET, PUT, DELETE   | postId                      |
| /comments      | GET, POST          | comment, postId, userId     |
| /comments/id   | GET, PUT, DELETE   | commentId                   |
| /user          | POST               | user                        |
| /user/id       | GET, PUT, DELETE   | userId                      |
| /reviews       | GET, POST          | review, userId, flashcardId |
| /reviews/id    | GET, PUT, DELETE   | reviewId                    |
| /flashcards    | GET                | userId                      |
| /flashcards/id | GET                | flashcardId                 |

1. Originally, the project was designed more to be a flashcard application only, but over time, it came to include a blog feature, too. 
2. I ended up choosing an ORM to implement the project, because I am more familiar with backend languages as opposed to raw SQL. 
3. In the future, I am considering adding functionality that related flashcards and reviews to one another. Also, I am considering making it possible for users to follow each other. 
