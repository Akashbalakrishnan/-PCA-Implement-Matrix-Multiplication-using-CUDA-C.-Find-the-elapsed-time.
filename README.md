# -PCA-Implement-Matrix-Multiplication-using-CUDA-C.-Find-the-elapsed-time.
Implement Matrix Multiplication using GPU.

## Aim:
To implement Matrix Multiplication using GPU.

## Procedure:
### Step 1 :
Include the required files and library.

### Step 2 :
Declare the block size and the size of elements .

### Step 3 :
Introduce Kernel function to perform matrix multiplication.In the kernal function,decalre the row column size and initialize the sum to be 0,then using for loop calculate the sum.

### Step 4 :
Intoduce a Main function, in the main method declare the required variables and Initialize the matrices 'a' and 'b'.Allocate memory on the device and then copy the input matrices from host to device memory and set the grid and block sizes . Launch the kernel,Copy the result matrix from device to host memory ,Print the result matrix and the elapsed time followed by freeing the device memory.

### Step 5 :
Save the program and execute it .

## Output:

Result:
