## Author :Dr. Thyagaraju G S ,  Context Innovations Lab  

Problem : Implement and demonstrate the FIND-S algorithm for finding the most specific hypothesis based on a given set of training data samples. Read the training data from a .CSV file.

### Algorithm : Find-S, a Maximally Specific Hypothesis Learning Algorithm
Step1: Initialize h to the most specific hypothesis in H
Step2: For each positive training instance x
        For each attribute constraint ai in h
	          If the constraint ai in h is satisfied by x  then do nothing
            else replace ai in h by the next more general constraint that is satisfied by x
Step3 : Output hypothesis h

# Reference : Machine Learning , Tom M Mitchell
