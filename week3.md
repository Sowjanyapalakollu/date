my_vector <- c(1, 2, 3, 4, 5)
reversed_vector <- rev(my_vector)
cat("Original Vector:", my_vector, "\n")
cat("Reversed Vector:", reversed_vector, "\n")
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)
concatenated_vector <- c(vector1, vector2)
cat("Vector 1:", vector1, "\n")
cat("Vector 2:", vector2, "\n")
cat("Concatenated Vector:", concatenated_vector, "\n")
my_vector <- c(5, 10, 15, 20, 25, 30)
count_in_range <- sum(my_vector > 10 & my_vector < 20)
cat("Vector:", my_vector, "\n")
cat("Count in Range (10, 20):", count_in_range, "\n")
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)
combined_by_row <- rbind(vector1, vector2)
combined_by_col <- cbind(vector1, vector2)
cat("Combined by Row:\n", combined_by_row, "\n")
cat("Combined by Column:\n", combined_by_col, "\n")
my_vector <- c(5, 12, 8, 15, 20)
greater_than_10 <- my_vector > 10
cat("Vector:", my_vector, "\n")
cat("Values Greater than 10:", greater_than_10, "\n")
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)
first_element <- my_list[[1]]
second_element <- my_list[[2]]
cat("First Element:", first_element, "\n")
cat("Second Element:\n", second_element, "\n")
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)
my_list$additional_element <- "New Element"
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)
my_matrix <- matrix(c(vector1, vector2), nrow = 2, byrow = TRUE)
cat("Matrix:\n", my_matrix, "\n")
my_matrix <- matrix(1:9, nrow = 3)
my_array <- as.vector(my_matrix)
cat("Matrix:\n", my_matrix, "\n")
cat("1-dimensional Array:", my_array, "\n")
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))
cat("Array:\n", my_array, "\n")
my_array <- array(1:24, dim = c(2, 3, 4))
cat("3-dimensional Array:\n", my_array, "\n")
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))
second_row_second_matrix <- my_array[2, , 2]
element_3_3_first_matrix <- my_array[3, 3, 1]
cat("Array:\n", my_array, "\n")
cat("Second Row of Second Matrix:", second_row_second_matrix, "\n")
cat("Element at 3rd Row, 3rd Column of 1st Matrix:", element_3_3_first_matrix, "\n")
array1 <- array(1:3, dim = c(1, 3))
array2 <- array(4:6, dim = c(1, 3))
array3 <- array(7:9, dim = c(1, 3))
combined_array <- rbind(array1, array2, array3)
cat("Combined Array:\n", combined_array, "\n")

