testtest
========

test 'test' 

  is this a code block
  
maybe?

    cachemean <- function(x, ...) {
            m <- x$getmean()
            if(!is.null(m)) {
                    message("getting cached data")
                    return(m)
            }
            data <- x$get()
            m <- mean(data, ...)
            x$setmean(m)
            m
    }
    
???

  test <- function(x, ...){
  }
  
  s <- NULL
  

