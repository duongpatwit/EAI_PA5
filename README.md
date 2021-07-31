# EAI_PA5

### Part 1

`What is your MSE/MAE with linreg vs tuned network?`\
my mse: 11.08, tuned mse: 24.29 \
\
`What happens to your train and test results if you add 5 hidden layers with 128 neurons each?`\
The Mean Squared Error dropped significantly (around half)\
<br>
### Part 3

`If I apply pooling of 2 (2,2 window with a stride of 2) to a (6,6) array, what is the resulting size?` \
(3,3)\
<br>

### Part 4

`What is my output size if: Input = (100,100), kernel size=(2,2), stride of 1 and no pooling? `\
(99,99)\
\
`How many weights do I have if I have 24 such filters stacked (conv2_24)?`\
96\
\
`What is a better idea: To use one larger kernel (7,7) or multiple stacked smaller ones, 3x(3,3)? `\
multiple stacked smaller ones are better\
\
`Solve for the padding (P), in terms of I, F and S, if we want the input and output size to remain the same. `\
P = (S*times(I-1)-I+F)/2
