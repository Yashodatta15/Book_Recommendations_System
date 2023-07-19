# Book_Recommendations_System
![Screenshot 2023-07-19 192849](https://github.com/Yashodatta15/Book_Recommendations_System/assets/118357421/b4d9815b-9997-450f-bd74-a08859e18fe8)
The Book Recommendation System using Cosine Similarity is a machine learning model designed to suggest relevant books to users based on their preferences. The system utilizes the concept of cosine similarity to measure the similarity between the book features and recommend books that are most similar to the ones the user has shown interest in.

The dataset for the model consists of the following columns:

`1. Book Title: The title of the book, representing its name or main topic.`

`2. Book Author: The name of the author who wrote the book.`

`3. Year of Publication: The year when the book was published, providing information about its release date.`

`4. Publisher: The name of the publishing company responsible for releasing the book.`

`5. Image URL: A link to an image of the book's cover, which enhances the user experience by providing visual context.`

The Cosine Similarity algorithm measures the cosine of the angle between two non-zero vectors in an n-dimensional space. In the context of the Book Recommendation System, each book's features (title, author, publication year, and publisher) are transformed into numerical vectors. The cosine similarity between any two book vectors is then calculated to determine their similarity.

When a user indicates their preferences or provides information about a book they enjoyed, the model calculates the cosine similarity between that book's vector and all other book vectors in the dataset. The books with the highest cosine similarity scores are considered the most similar and are recommended to the user.

By leveraging cosine similarity, the Book Recommendation System can suggest books that align closely with the user's interests, enabling more personalized and relevant reading recommendations. The system can be further improved with regular updates to the dataset, user feedback, and incorporation of other factors such as user ratings and reviews to enhance the recommendation accuracy and user satisfaction.
