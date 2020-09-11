#' @title Rm_Emojis
#'
#' @description Delete all emojis in a string
#'
#' @usage Rm_Emojis(Sstring)
#'
#' @param Sstring is a string
#'
#' @export
Rm_Emojis <- Vectorize(function(Sstring){
  Sstring <- gsub("[^\x01-\x7F]", "", Sstring)
  return(Sstring)
})


#' @title To_Singular
#'
#' @description Singularize all words in a tibble
#'
#' @usage To_Singular(Sstring)
#'
#' @param Sstring is a string
#'
#' @export
To_Singular <- Vectorize(function(Sstring){
  Singularity <- pluralize::singularize(Sstring)

  return(Singularity)
})
