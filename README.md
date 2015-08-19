# Programming-Assignment-2

How to run the script:

'''sh
m <- matrix(runif(16),nrow=4,ncol=4)  #Creates a 4x4 matrix filled with random numbers
cache <- makeCacheMatrix(m)           #Create the special matrix
cacheSolve(cache)                     #Returns the inverse
cacheSolve(cache)                     #The function is called again, now it will
                                      #return the cached data
'''
