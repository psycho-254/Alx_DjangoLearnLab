from bookshelf.models import Book

# Create a book instance  - Here's the code for creating a Book instance:
book = Book.objects.create(
    title="1984",
    author="George Orwell",
    publication_year="1949-01-01"
)


# And here's the output

<Book: 1984 by George Orwell>
