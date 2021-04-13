## Welcome to Alexandria

Alexandria is a small side project to allow someone to search for books in the net, and if necessary save his/her preferences locally for future reference.

### A Brief History

![Image](images/logo.jpg)

The great **library of Alexandria**, located in modern-day Alexandria, Egypt, was one of the largest libraries of the ancient world. It is said that during its hey day the library used to around 400,000 scrolls.
While the ancient times have come and gone, humanity's quest for knowledge is still far from over. But now we have more elegant and efficient ways to search for book, sitting at the comfort of our home. 
We can browse and look for books, make notes, tag them, and keep for future reference as book-marks.
Project Alexandria is a small show-case of such capabilities, with a tribute to its much richer and greater ancestor.

### Core Functionalities

At basic level, Alexandria provides 
- A set of APIs (based on python FastAPI) to google for books, based on author names, genre, ISBN ID etc.
- A local database running behind the scene, which may be used to stored some meta data about the search results, with necessary notes/tagging
- The APIs as well as the underlying database are spun up docker containers so that it may be run anywhere
- In future this may also be extended to have a formal UI where user may navigate and do the same steps, in a more friendlier way


**Bold** and _Italic_ and `Code` text

### Underlying Technologies/References

1. For more details on how to use _Google Books API_, [check out the documentation](https://developers.google.com/books/docs/v1/using).
2. For more details on how _FastAPI_ works, [check out the documentation](https://fastapi.tiangolo.com).