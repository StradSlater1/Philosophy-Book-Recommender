# Philosophy-Book-Recommender
I am quite a fan of Philosophy. Specifically, I like ethics, philosophy of mind and metaphysics. Sometimes I will read a book and enjoy the experience so much that I just want to find similar books to give me a similar experience. So, using a dataset of books from good reads, and a sentence transformer model, I created a Philosophy Book Recommender that allows you to find similar books to a book you have read and enjoyed. 

# Methods
- Data Cleaning
- Machine Learning
- Natural Language Processing

# Technologies Used
- Python
- Pandas
- Matplotlib
- Scikitlearn
- StandardScaler
- KMeans
- SentenceTransformer
- Util


# Project Description
- Goodreads dataset of 10,000 books was reduced to a list of Philosophy books that were not fiction
- K-means clustering was done to filter out books with low ratings and a low amount of ratings
- The Genres and Descriptions of each book were combined into one column "Descriptions_Genres"
- "Descriptions_Genres" data was placed into a Sentence tranformer model
- A function was made where you can input a book and the amount (n) of recommendations you want. Cosine similarity scores are computed between the chosen book and all the other books. The n top books with the highest cosine similairty scores are returned.

# Example of Final Product
- List of Book Titles and Index:
![List of Books](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/4ee2fe61-ef5a-4ce6-95d5-5cf7e862e94c)

- Searching for the 10 most similar books to "The Selfish Gene" (searched for by index)
![The Selfish Gene 10](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/606313c1-94a5-49eb-a84b-e7a5b18f7cb6)

- 10 most similar books to "The Selfish Gene"
  ![selfish gene similar](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/fb7b858a-05b1-44a9-8af0-9f4118125419)

- Description of "The Selfish Gene" compared to that of the 3 most similar books
  ![sg](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/12fdf15c-8749-45fb-9670-11b131590060)
  ![sg book 1](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/36d6b0b0-f5a7-4797-9f41-6f379273c90e)
  ![sg book 2](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/36e88e87-23ae-4d28-9baa-7b6964ae8985)
  ![sg book 3](https://github.com/StradSlater1/Philosophy-Book-Recommender/assets/140914261/3f41604c-f02e-4b4a-a8ac-4c310e104a63)





