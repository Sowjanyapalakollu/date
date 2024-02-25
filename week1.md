u <- 4
v <- 8
add_result <- u + v
subtract_result <- u - v
multiply_result <- u * v
divide_result <- u / v
power_result <- u ^ v
cat("Addition:", add_result, "\n")
cat("Subtraction:", subtract_result, "\n")
cat("Multiplication:", multiply_result, "\n")
cat("Division:", divide_result, "\n")
cat("Power:", power_result, "\n")
u <- c(4, 5, 6)
v <- c(1, 2, 3)
add_result <- c(5, 7, 9)
subtract_result <- c(3, 3, 3)
multiply_result <- c(4, 10, 18)
divide_result <- c(4, 2.5, 2)
power_result <- c(4, 25, 216)
u <- c(8, 9, 10)
v <- c(1, 2, 3)
w <- u + 0.5 * v
w <- w ^ 2
w <- (u + 0.5 * v) ^ 2
w <- u + v
w <- w / 2
w <- w + u
w1 <- u^3
w2 <- u - v
w <- w1 / w2
w <- (u + v) / 2 + u
w <- u^3 / (u - v)
df <- data.frame(
  Student = c("Name1", "Name2", "Name3"),
  Age = c(20, 22, 21),
  Weight = c(70, 75, 68),
  Height = c(175, 180, 170),
  Sex = c("Male", "Female", "Male")
)
df$Sex <- ifelse(df$Sex == "Male", "Female", "Male")
df1 <- data.frame(
  Name = c("Person1", "Person2", "Person3"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160),
  Sex = c("Male", "Female", "Male"),
  Working = c("Yes", "No", "Yes"),
  stringsAsFactors = FALSE
)
df_combined <- cbind(df, df1)
n_rows <- nrow(df_combined)
n_cols <- ncol(df_combined)
data_classes <- sapply(df_combined, class)
class_state_center <- class(state.center)
df_state_center <- as.data.frame(state.center)
class_state_center <- class(state.center)
df_state_center <- as.data.frame(state.center)
df_vectors <- data.frame(
  Column1 = c(3, 1, 5),
  Column2 = c(8, 2, 7),
  Column3 = c(6, 4, 9)
)
df_vectors_ordered <- df_vectors[order(df_vectors$Column1), ]
mat <- matrix(c(1, 2, 3, 4, 5, 6), nrow = 2)
df_matrix <- data.frame(mat)
rownames(df_matrix) <- paste("id", 1:nrow(df_matrix), sep = "_")
colnames(df_matrix) <- paste("variable", 1:ncol(df_matrix), sep = "_")
df_VADeaths <- as.data.frame(VADeaths)
df_VADeaths$Total <- rowSums(df_VADeaths)
df_states <- data.frame(
  abb = state.abb,
  area = state.area,
  division = state.division,
  name = state.name,
  region = state.region,
  row.names = names(state.abb)
)
colnames(df_states) <- gsub(".*\\.", "", colnames(df_states))




