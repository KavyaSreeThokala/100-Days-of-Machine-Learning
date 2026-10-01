📚 What I Learned
Today I learned about Tensors, their dimensions, and how they are used to represent data in Machine Learning and Deep Learning.

🧠 What is a Tensor?
A tensor is a data structure used to store numerical data in multiple dimensions.
You can think of a tensor as a generalization of:
A single number → Scalar
A list of numbers → Vector
A table of numbers → Matrix
Higher-dimensional arrays → Tensors

For example:
10
is a scalar.
[10, 20, 30]
is a vector.
[
 [1, 2, 3],
 [4, 5, 6]
]
is a matrix.

A tensor can have even more dimensions.

📐 Tensor Dimensions

The number of dimensions is commonly called the rank or number of axes of a tensor.
0D Tensor — Scalar

A single value:
x = 10
Shape:
()

1D Tensor — Vector
A single list:
x = [10, 20, 30]
Shape:
(3,)

2D Tensor — Matrix

Rows and columns:

x = [
    [1, 2, 3],
    [4, 5, 6]
]

Shape:

(2, 3)

2 rows and 3 columns.
3D Tensor
For example:
x = [
    [
        [1, 2],
        [3, 4]
    ],
    [
        [5, 6],
        [7, 8]
    ]
]
Shape:
(2, 2, 2)

🖼️ Tensors in Images

Images are commonly represented using tensors.

For a grayscale image:
Height × Width
Example:
28 × 28
For a color RGB image:
Height × Width × Channels
For example:
224 × 224 × 3
where:
3 → Red, Green, Blue
A batch of RGB images can have another dimension:
Batch × Height × Width × Channels
For example:
32 × 224 × 224 × 3
This represents:
32 images
224 × 224 pixels
3 color channels

🤖 Why are Tensors Important in Deep Learning?
Deep learning models work with numerical data.
Tensors allow us to represent:
Images
Text embeddings
Audio
Video
Tabular data
Model weights
Activations

Deep learning frameworks such as PyTorch and TensorFlow use tensors extensively.

🔑 Important Tensor Properties

Some important properties of a tensor are:

Shape: Tells us the size along each dimension.
x.shape
Example:
(2, 3)
means 2 rows and 3 columns.

Number of Dimensions
x.ndim
Data Type
x.dtype
For example:
torch.float32

Device
In frameworks such as PyTorch, tensors can be stored on:
CPU
GPU
Example:
x.device

🧠 Tensor vs Array

A NumPy array and a tensor can look very similar.

However, tensors in deep learning frameworks such as PyTorch provide functionality designed for neural-network computation, including operations that support automatic differentiation and GPU acceleration.

📌 Key Takeaways
A tensor is a multidimensional numerical data structure.
A scalar is a 0D tensor.
A vector is a 1D tensor.
A matrix is a 2D tensor.
Higher-dimensional data can be represented using higher-dimensional tensors.
Images can be represented using tensors.
PyTorch and TensorFlow use tensors extensively.
shape tells us the size of each dimension.
ndim tells us the number of dimensions.
Tensors can be processed on CPUs and GPUs.

💻 Practical Work

I practiced creating tensors using:

NumPy
PyTorch

I also explored:

Tensor shape
Number of dimensions
Data type
Basic tensor representation

🔍 My Learning Reflection

Today I understood that tensors are the basic data structure used to represent numerical data in deep learning.

I learned how scalars, vectors, matrices, and higher-dimensional arrays can be represented as tensors and how tensors are used to represent images and other types of data.
