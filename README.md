# MatrixDeviation
Calculates the deviation or "noisiness" of matrix elements

# Usage:

The parent function file matCorrelation contains the function matrixcorr( 2-d array )
which calculates the "correlation" of a matrix based on the cross correlations from
neighboring rows and columns. 

The function was originally created to perform a calculation for binary matrices (2d Numpy arrays with only 0 or 1 entries),
but it can be accomodated further upon request. Note that the renormalization constant is proportional to the square of the maximum of the array.
This also clearly assumes there are no negative entries, but changes can be made to accomodate this as well if needed. 

Note: While the returned values are between 0 and 1 in this example, the most "noisy" matrix corresponds to a matrixcorr of 0.5.

The only return value (between 0 and 1 for a normalized matrix) is a float.

# Build and Dependency Info
Python 2.7

Numpy dependency

Optional Matplotlib dependency to see the calculation for randomly generated matrices.

