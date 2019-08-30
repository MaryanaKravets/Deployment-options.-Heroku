# Deployment-options.-Heroku

 1.   How the controller in the application by the link works (https://peaceful-wildwood-88757.herokuapp.com)

    /book - find all books
    /author - find all authors
    /{id} - find author with {id}
    "" and request parameter "genre" - find all book by genre
    /author and request body Author - add new author
    /book and request body Book - add new book
    /author/{id} - delete author by {id}
    /book/{id} - delete book by {id}
    /author/{id} and request body Author - update author
    /book{id} and request body Book- update book

  2.  How the controller in the application by the link works (https://fathomless-reaches-11765.herokuapp.com)

    /{id} - find all book of Author with {id}
    "" and request parameter "genre" - find all book by genre
    /author and request param ("authorId","authorFName","authorLName") - add new author
    /book and request param( "bookId","bookTitle","bookGenre","bookDesc","bookRate") - add new book
    /author/book and request param( "authorId","bookId","bookTitle", "bookGenre", "bookDesc","bookRate") - add book to author
    /author/{id} - delete author by {id}
    /book/{id} - delete book by {id}
    /author/{id} and request param "id" - update author {id}
    /book{id} and request param "id"- update book {id}
