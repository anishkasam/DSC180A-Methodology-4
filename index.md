Anish Kasam, akasam@ucsd.edu  
Section A11, In-Context Learning, Arya Mazumdar

<b>What is the most interesting topic covered in your domain this quarter?</b>

The most interesting topic covered in my domain this quarter was the theory that showed that under the right conditions, the query, key, and value matrices in an attention layer can emulate gradient descent. I had a basic understanding of transformers prior to the capstone, and most of my understanding was in the context of "next word prediction." However, seeing how powerful the attention mechanism can be, literally generalizing to the gradient descent algorithm was super interesting and cool to learn about.

<b>Describe a potential investigation you would like to pursue for your Quarter 2 Project.</b>

A potential investigation I'd like to pursue for my Quarter 2 Project would be some sort of systematic evaluation or benchmark of comercial models' ability to in-context learn. It would be cool to evaluate the performance of all the leading models: ChatGPT, Claude, Llama, Gemini, etc. and then try and understand how certain architectures are better suited for in-context learning compared to others.

<b>What is a potential change you’d make to the approach taken in your current Quarter 1 Project?</b>

I think one potential change that I'd like to make to my approach for the Quarter 1 Project is to expand on the different linear regression scenarios. The main goal of my Quarter 1 Project is to show that an attention layer is equivalent to an iteration of gradient descent. However, past work has also shown that a transformer's performance closely follows least squares for regular linear regression, LASSO for sparse linear regression, etc. It would be cool to verify all of these results since they are related.

<b>What other techniques would you be interested in using in your project?</b>

Some other techniques I'd be interested in using for my project would be more random/varied data generation processes. I think a lot of the papers that we've read and been trying to reproduce mostly sample from a normal distribution with zero mean and unit variance. It would be interesting to create really weird datasets, ones with large outliers or some that are completely random. Would the model continue to behave as we expect?