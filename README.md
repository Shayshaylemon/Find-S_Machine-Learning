# Find-S_Machine-Learning
This program is developed to determine whether the risk of defaulting on a loan is "high" or "low" based on a set of binary attributes using Find-S algorithm. 

Find-S algo:
1. Initialize h to the most specific hypothesis in H
2. For each positive training instance x
   - For each attribute constraint ai in h: If the constraint ai is satisfied by x, then do nothing
     else replace ai in h by the next more general constraint that is satisfied by x
3. Output hypothesis h

Attributes are: 
• Gender (Male, Female)
• Age (Young, Old)
• Student? (Yes, No)
• Previously Declined? (Yes, No)
• Hair Length (Long, Short)
• Employed? (Yes , No)
• Type Of Colateral (House, Car)
• First Loan (Yes, No)
• Life Insurance (Yes, No)

My hypothesis space H consists of all possible conjunctions over the nine attributes. Dataset "9Cat-Dev.labeled" is used to develop and test my code. 
