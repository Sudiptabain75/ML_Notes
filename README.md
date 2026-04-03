Tensor হলো একটা multi-dimensional data container
মানে এটা সংখ্যাগুলো রাখার একটা smart box.
Tensor হলো একটা multi-dimensional data container, মানে এটা সংখ্যা রাখার box 📦 (0D, 1D, 2D, 3D… সব হতে পারে)।
Scalar (single number), Vector (list), Matrix (table)—সবই আসলে tensor-এর special case।
Deep Learning-এ (যেমন TensorFlow, PyTorch) সব data tensor আকারে থাকে এবং model এই tensor নিয়েই কাজ করে।
উদাহরণ: একটা image = 3D tensor (height × width × color channels)।
সহজ উদাহরণ: [1,2,3] = 1D tensor (vector), [[1,2],[3,4]] = 2D tensor (matrix)। 
