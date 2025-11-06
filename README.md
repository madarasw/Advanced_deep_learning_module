# Advanced_deep_learning_module
Contains the assignments and projects done under the module names Advance Deep Learning @ UOM

============================================================================================================================
1. Assignment: 
You are given the task of building a neural network that predicts whether a 6-digit number is a prime number or not.  
The neural network takes a 6-digit number as input, where each digit is treated as a separate input feature. 
The network outputs a binary prediction indicating whether the input number is prime (1) or composite (0). 
Hence, we can define the function 𝑓 that takes these 6 digits and outputs the binary 

Network architecture 
• Input Layer: 6 nodes (one for each digit) 
• Hidden Layer 1: 64 nodes with ReLU activation 
• Hidden Layer 2: 32 nodes with ReLU activation 
• Hidden Layer 3: 16 nodes with ReLU activation 
• Output Layer: 1 node with Sigmoid activation 

Weights and Biases are gibe in the W.csv and b.csv respectively. 
The network uses cross-entropy loss as the cost function for binary classification. 

Calculate the gradients of the weights and biases. Save these calculated gradients into CSV files named dw.csv and db.csv 
and submit them for grading. These gradient files should have the same formatting as the 
corresponding weight/bias file (follow the exact CSV format specified in Appendix I) but 
SHOULD NOT include the headings. If possible, use np.float32 to control the granularity of 
your gradients; otherwise, round your results to at least 16 digits.

Example: 

If the network has 2 layers
• Input Layer: 2 nodes (for an input with 2 digits) 
• Hidden Layer 1: 3 nodes with ReLU activation 
• Hidden Layer 2: 2 nodes with ReLU activation 

Weights
1.0, 1.6, 0.74                
0.8, 1.4, 0.2                    
0.01, -1.87 
0.0.1, -1.23 
0.0, -0.34 

Biases
1.0, 1.61, 0.74                               
0.01,−0.99  

The output CSV file you would submit should have the same format as above.


============================================================================================================================
2. CLASS PROJECT: 

In this project, you must develop a deep learning-based solution to the problem posed in the following challenge.

https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images/overview

Deliverables:
A report with the following sections (Maximum of 5 pages): 
Literature review (review around 5 key papers)
Proposed method (describe your approach and highlight its novelty)
Training and validation results for your model
Submission to the challenge - In the report, include a screenshot of the leaderboard showing your best score (with your group name visible)
Your group name should include the suffix UOM_. For example, a valid group name is UOM_hackers. This is so we can track your progress in the challenge.
Source code (a separate  assignment link will be created for this)
Evaluation Criteria

70% of the project marks will be allocated for your rank in the challenge's leaderboard. We will filter out submissions of the groups of this module and consider only those for ranking. The top 3 groups will get 100 marks, the next five will get 80, and the rest will get 60.
30% of the project marks will be allocated for the report.

Relevant code: 
Class_Project/ViTs - Try vision transformers for AI vs Real image detection.
Class_Project/Testing/* - Basic testing and experimeting 

