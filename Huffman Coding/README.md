# Python Implementaion of Huffman Coding

Consists **compress** and **decompress** function.

# Testing / Running the program / How it works

1. This contains the implementation of Huffman Algorithm in python program. 

2. It contains both the compression and decompression function.

3. It contains a sample text file 'sample.txt' which is around 865KB.

4. After compression, a new file will be created 'sample.bin' which is the compressed version of the text file in the same folder as well as the decompressed file too, which is a new text file but it has the same content as 'sample.txt'.

5. Run the python code 'useHuffman.py' to compress & decompress the given sample file. For eg. open terminal and run 'python3 useHuffman.py' or 'python useHuffman.py'.

6. The above command will perform compression and decompression on the sample.txt file present here. Both the compressed and decompressed file will be present at the same location.

7. To run the code for compression of any other text file, edit the 'path' variable in the 'useHuffman.py' file.

8. For now, the *decompress()* function is to be called from the same object from which the *compress()* function was called. (as the encoding information is stored in the data members of the object only) 
