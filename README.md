# project2_LSTM
Final project - 2021 Fall

II. Generate and use your own custom dataset

[Rules for determining your dataset]
  ●	Make a nontrivial input-output relationship with time dependency
    ○	the dimensions of the input should be larger than 5. 
    ○	Input and output can be limited/unlimited, discrete/continuous, whatever. 
    ○ Your output should also be time dependent.
■	For instance, Y(t) = X(t)^2 + X(t)/2 - X(t-2) + 3X(t-1)
  ●	Generate training (more than 10,000 samples) and testing datasets (more than 2,000 samples) based on your function.

[What you need to do]
  ●	Write a code for regression to approximate your function by designing custom RNNs. Whatever RNN architecture is ok. 
  ●	Show your more than two efforts to improve the inference accuracy of the deep learning approach. The efforts include
    ○	controlling your learning rate
    ○	modifying your neural network architecture
    ○	Etc
