# secNB_BreastCancer
Secure Naive Bayes Breast Cancer (training and classification)
The source code for the original and the improved secure training and classification algorithms based on Naive Bayes over the Breast Cancer dataset.
1) At the SourceNBBreastCan.cpp file comment out the #define POLYSWITCH and the #define IMPROVEDTRAINING lines to get the source code which was used for experimentation purposes      of the journal paper:
   Kjamilji, Artrim, Erkay Savaş, and Albert Levi. "Efficient Secure Building Blocks With Application to Privacy Preserving Machine Learning Algorithms." IEEE Access 9 (2021): 8324-8353.
2) If the pre-processing identifiers POLYSWITCH and IMPROVEDTRAINING are defined (i.e. if the lines #define POLYSWITCH and the #define IMPROVEDTRAINING
   are left uncommented at the SourceNBBreastCan.cpp file), then it is the improved version of 1) used for experimental purposes of the journal paper:  
   TBD 
 
Link to the paper(s):
1) https://ieeexplore.ieee.org/document/9314152
2) TBD

Video presentation(s) of the paper:
1) https://www.youtube.com/watch?v=P_GxSmAwDfg&list=PLN2gEfNq4GvfUYJx1aBE7R8bIAXt4JK2P
2) TBD

Link to the dataset:
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29 

Open the solution using Visual Studio 2017. Set the SEALExamples as the start-up project. The implementation uses Microsoft's SEAL library v3.2 found in https://github.com/microsoft/SEAL
For better communication and computation costs (performances), run the code in Release mode. 

For any inqueries you can contact me by artrimq@gmail.com or artrimk@sabanciuniv.edu
