The Cyclic Hunffman Algorithm is an original version of the compression algorithm that plans to create an encryption system by adding repetitive steps to the classical Hunffman algorithm

This algorithm works with a dictionary that will recount the compressed bit values and assign them to letters in groups of 8 bits in order to repeat the classic Hunffman compression. This process is used to reprocess the compressed bits. If the number of bits resulting from the compression process is not exactly divisible by 8, it saves the excess bits in an output file to make divisibility possible. The process is repeated by assigning the appropriate bits to letters and each repetition creates a loop. At the end of the process, the number of all cycles and a key value of 21 bits are obtained. The text is also fragmented with a solution table and an output table. These complex operations can be used as an encryption system. 
Follow the steps below to encrypt the code into the br encryption system:

Once the process is complete, use the values found in any loop of your choice (it is recommended to take the mode of the user's numeric cipher) as the key value.
Perform key value matching during the key decryption process (hash function can be used)
