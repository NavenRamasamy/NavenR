#' Performs standardization for a distribution vector
#'
#' @param dis_vec A distribution vector.
#' @return stan_dis_vec A distribution vector.
#' @examples
#' stand_dist <- standardize(c(1,3,2,4,5,3))
#' stand_dist <- standardize(c(1,2,3))
#' @export

standardize <- function(dis_vec){
  mean_dis_vec <- mean(dis_vec)
  sd_dis_vec <- sd(dis_vec)
  stan_dis_vec <- (dis_vec - mean_dis_vec) / sd_dis_vec
  return(stan_dis_vec)
}


