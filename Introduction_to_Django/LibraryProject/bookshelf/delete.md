# Here's the command to delete the book:

from bookshelf.models import Book  #Import the model

book = Book.objects.get(id=1) # retrieve the books

book.delete() # delete the book

Book.objects.get(id=1) # try retrieving the book again 

# Here's the output:

(1, {'bookshelf.Book': 1})


