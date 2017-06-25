# Assignment-15.4

Write a GraphQL query to fetch Books from 81 to 90.

{
  bookStore {
    books(after: "YXJyYXljb25uZWN0aW9uOjc5", before: "YXJyYXljb25uZWN0aW9uOjkw") {
      edges {
        cursor
        node {
          id
          title
        }
      }
    }
  }
}
