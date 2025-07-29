# Evaluations-of-beliefs-in-free-form-text

Designed & implemented a simple pipeline for measuring beliefs in free-form text, and 
sense-check this pipeline with diverse hand-crafted test cases. 

The pipeline would, for example, 
take as input proposition P and free-form text T (e.g. a short essay), and outputs a real in [0,1] 
indicating to what extent T agrees/disagrees with P. The pipeline can be prompting-based, 
logprob-based, embedding-based, or anything else you think makes sense - whatever does the 
job well.
