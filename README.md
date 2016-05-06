# Speech-Recognition
Columbia University
CSEE6870 Speech Recognition

Lab1
Part 1: Write a front end (Required) 
 Write a complete mel-frequency cepstral coefficient (MFCC) front end, except for the FFT, which will be provided.
Part 2: Implement dynamic time warping (Optional) 
 Write a function that implements DTW.
Part 3: Evaluate dierent front ends using a DTW recognizer (Required) 
 Run experiments on the TIDIGITS data set comparing the performance of dierent portions of the front end you implemented.

Lab2
Part 1: Implement the Viterbi algorithm 
 Given a trained model, write the algorithm for finding the most likely word sequence given an utterance.
Part 2: Implement Gaussian training 
 Implement the algorithm for reestimating the means and variances of a Gaussian.
Part 3: Implement the Forward-Backward algorithm 
 Write the forward and backward algorithms needed for training HMM's.
Part 4: Train various models from scratch, and evaluate them on various digit test sets 
 Use the code developed in the earlier parts to run a bunch of experiments.

Lab3
Part 1: Implement n-gram counting 
 Given some text, collect all counts needed for building an n-gram language model.
Part 2: Implement + σ smoothing 
 Write code to compute LM probabilities for an n-gram model smoothed with + σ smoothing.
Part 3: Implement Witten-Bell smoothing 
 Write code to compute LM probabilities for an n-gram model smoothed with Witten-Bell smoothing.
Part 4: Evaluate various n-gram models on the task of N-best list rescoring 
 See how n-gram order and smoothing aects WER when doing N-best list rescoring for Switchboard.

Lab4
Part 1: Play with FSM's and the IBM FSM toolkit
Part 2: Investigate the static graph expansion process
Part 3: Implement the Viterbi algorithm, handling skip arcs and token passing
Part 4: Add support for beam pruning and optionally rank pruning
Part 5: Evaluate the performance of various models on WSJ test data
