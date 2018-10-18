# React coding test

The goal is to implement a simple book search application in React using
[Google book http api](https://developers.google.com/books/docs/v1/reference/volumes/list)

## Part 1: Book search

* Implement a one page application which displays a input text for serch terms
  and a search button;
* Tapping on search loads the first 40 search results in a list. Each result
  displays at least:

  * Title
  * Author
  * Description
  * Categories
  * Thumbnail

## Part 2: Infinite scroll

* When scrolling to the bottom of the page, application automatically loads the
  next 40 results;

## Notes

* We will pay **a lot of attention** to code quality, maintainability,
  testability (cough... write tests...cough) and best software engineering practices;

* We expect the app to be usable but will not judge the quality of design/UX and do not
  expect any styling;

* You can use any library you believe is relevant to the completion of the
  tasks;

* The [search endpoint](https://developers.google.com/books/docs/v1/reference/volumes/list)
  does not need any authentication to query it:

  * Example: [https://www.googleapis.com/books/v1/volumes?q=jules+vernes](https://www.googleapis.com/books/v1/volumes?q=jules+vernes)

* The google book search api allows calls from any origin so you should not
  need any proxy from same domain of your react application:

  * [test-cors.org](http://www.test-cors.org/#?client_method=GET&client_credentials=false&server_url=https%3A%2F%2Fwww.googleapis.com%2Fbooks%2Fv1%2Fvolumes%3Fq%3Djules%20vernes&server_enable=true&server_status=200&server_credentials=false&server_tabs=remote)
