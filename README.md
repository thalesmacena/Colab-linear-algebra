# Linear algebra and computation
This repository aims to show experiments based on linear algebra and how various things in computing are and can be done using these concepts. All of these projects were done during the teaching of the Algebra Linear Algorithmic discipline at the Universidade Federal do Rio de Janeiro taught by professor Juliana V. Valério.

**Unfortunately the explanation and comments are still in Portuguese**

## Bouncing Ball

Bouncing ball shows how vectors and their concepts can be used to describe movement

## Aproximação por minimos quadrados / Least squares approach

The purpose of these functions is to approximate functions by the [least squares](https://en.wikipedia.org/wiki/Least_squares) method based on data sheets.

## Gram Schmidt

The purpose of these functions is to perform the [Gram Schmidt process](https://en.wikipedia.org/wiki/Gram%E2%80%93Schmidt_process) to obtain orthonormal bases and to visualize them clearly.

## Leslie
This function aims to create a [Leslie matrix](https://en.wikipedia.org/wiki/Leslie_matrix) of size N.

## Gráfico de Filmes em 2D usando SVD / 2D Film Graphics using SVD

This is my final project for the course, which aims to show an application of the [SVD](https://en.wikipedia.org/wiki/Singular_value_decomposition) (singular value decomposition) method. 

With a database of dozens of personal opinions about different films, using SVD, I can break them down into R².The advantage of doing this is that the X and Y imaginary axes (which do not cut x0 and y0) have meaning. The vertical corresponds to the mood of the films, the higher the more the genre of comedy is the user's taste, while the lower the less comedy is seen in the films. While the horizontal axis indicates whether the film is dramatic, the farther to the left the more dramatic the more to the right the less drama is seen.

This information is crucial, as I do not need any information about each film, other than the opinion of users about it, to visualize in the graph which films are most similar following the meaning of the axes. The same goes for Users, based only on their opinion about different films, it is possible to understand their preference. So films that fall close to their axis on the graph can be strong candidates for recommendations.

**The more different opinions are inserted in the Matrix A the more divergent the graph becomes and the more it is possible to notice these axes.**

More leaving the aspect of films and opinions this analysis is still significant because a matrix in *Rn* that would not be possible to be plotted and visualized is now represented in the most approximate way in R². So what would happen to the imaginary axes if we choose a different type of Matrix? What if they were BooksxWords where the values meant the word frequency in these books? Probably the information would be of great value to understand how words are used more in different genres of books. What if they were AlgorithmsxProgrammers where the values were the difficulty that these programmers have to implement these algorithms? What would be the imaginary axes of this graph?

These types of analysis have become increasingly frequent and are indexed in most major services. Like Netflix that uses something similar to hook its users with its tool. You may also have seen something similar in the Riot Games post about one of its champions


