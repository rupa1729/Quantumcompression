# Quantumcompression
## Inspiration
In our day-to-day problems , we see huge amount of data growth ,but** compression of data with same quality** is difficult .The desire to have a scalable and more accessible quantum computing infrastructure motivated us. For that to happen given quantum hardware constraints and to catch up with the classical big data revolution, we chose data compression as a gateway to create hybrid 
classical-quantum nodes in the computing network.

## What it does
 _“Classical Quantum Data Compression”_ as a way to leverage quantum technologies for classical data processing . 
The procedure involves:
-Encode classical information into quantum bits using methods like **Amplitude encoding**
-Usage of **Quantum data compression algorithms** like to condense Quantum data which can help in 
-Reducing storage needs  
-Less need for larger quantum channels
-Low amount of input for further quantum algorithms.
-Decoding quantum qubits back to classical data

## How we built it
**In the front-end of the project:**
We created an interface to take classical input for encoding from the user.
 
**In the back-end:**
 First we used Amplitude Encoding to create qubits , then we demonstrated lossless quantum data compression for 4 identical qubits which were successfully condensed in log(5)(~3) qubits.
 As we relied on lossless algorithm ,decompression circuit can be obtained by complex conjugate of the compression circuit, thereby enabling retrieval of the original quantum data.
For decoding to classical data , we relied on repeated simulations to get back classical bits embedded in the probability amplitudes of decompressed qubits . At last, we get to display the decoded classical bit back in the user interface.

## Challenges we ran into
Most of the research on compression algorithms rely on initially identical qubits but the output we get from encoding barely gives identical qubits so combining those steps became a challenge that we could pursue in future.

In the decoding part , we had to repeat the simulation many times to get the classical bits but rarely we can do so in storage and retrieval systems or it might beat the edge given by compression in signal transmission.

## Accomplishments that we're proud of
We created an application to showcase the expected output.
We successfully implemented amplitude encoding and decoding , reduced the number of qubits from 4 to log(5)(~3) without any loss.


## What we learned
Application of quantum data compression algorithm on the data sets(text).
During research , we went through various classical to quantum encoding methods like basis , angle and amplitude encodings and  quantum compression algorithms, their effectiveness and limitations.
time management , team work and software skills

## What's next for Quantum data compressor
Our project is scalable in the future. We would like to implement the upgraded compression algorithm on the large datasets  in the data mining  or real world applications to maintain the same quality of data without any loss, the data sets are scalable so that we can use it on different types of  classical data eg : text ,image ,audio ,video. 
