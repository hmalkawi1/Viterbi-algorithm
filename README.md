This Viterbi algorithm is used on a hidden Markov model to detect C/G rich regions in a DNA sequence.

should be able to test your code running the following commands:

`python a3_template.py "small.txt" `

`python a3_template.py "ecoli.txt" `


The program will output a file in the following format:

The first line is the (natural) log probability of the sequence,as calculated by HMM.logprob(). 

The second and third lines is number of inferred 0 and 1 states respectively in your inferred sequence of states. 

The fourth line is a sequence of states (0 or 1) with the highest probability of outputting the observed sequence, calculated using the Viterbi algorithm. 
