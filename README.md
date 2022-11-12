In this project, I performed image compression through two beautiful concepts - Singular Value Decomposition (SVD) and K Means Clustering.
The code files will give a background behind each of the concepts used. The repository also contains the images used for reference. 

Please use the notebooks to play around with the K values to see how the compressed image looks like. Find below the results from the compression which shows the original image against the compressed image. It also shows the Compression ratio (for SVD) and the compressed file sizes (for K Means) to give a sense of how compressed the images are for the chosen K.

# Singular Value Decomposition (SVD)

### I) <ins>Comparison for Black and White images: </ins>

#### Lower number of Singular Values


![image](https://user-images.githubusercontent.com/104417912/201446022-594ff6f0-26c5-4036-81db-90b306d4ab51.png)


#### Higher number of Singular Values


![image](https://user-images.githubusercontent.com/104417912/201445538-b370a6df-a223-4a19-8886-d99f3ee63b37.png)

### II) <ins>Comparison for Color images: </ins>


#### Lower number of Singular Values


![image](https://user-images.githubusercontent.com/104417912/201447431-d6d4a767-cddc-470a-ac0c-220ba322c1a1.png)


#### Higher number of Singular Values


![image](https://user-images.githubusercontent.com/104417912/201446150-04741019-8bf3-4c3d-b60a-3bd0e7a3f932.png)


# K Means Clustering

### I) <ins>Comparison of the images: </ins>

![image](https://user-images.githubusercontent.com/104417912/201450344-91482d57-1af1-45e6-b2fd-ac822e705829.png)


![image](https://user-images.githubusercontent.com/104417912/201450355-30d9241b-84b8-4b5b-8525-c32f94f8235f.png)


![image](https://user-images.githubusercontent.com/104417912/201450372-47b5068b-5348-4472-9313-53d419f94270.png)

### II) <ins>Comparison of the file sizes: </ins>

![image](https://user-images.githubusercontent.com/104417912/201450536-544c370e-a63a-4102-83ce-ea00002fb28c.png)


