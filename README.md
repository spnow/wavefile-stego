# Wavefile Stego

A simple steganography tool to hide ASCII text files in wave files.

- [Running on UNIX/Linux]
	- [Encoding a text file in a wave file]
	- In terminal, navigate to this directory, then type "python3 wave_encode.py TEXTFILE WAVEFILE" where TEXTFILE is an ASCII text file in the working directory, and WAVEFILE is a .wav file in the working directory.
	
	- To bring up the help text, type "python3 wave_encode.py --help"
	
	- [Decoding a wavefile]
	- In terminal, navigate to this directory, then type "python3 wave_decode.py WAVEFILE OUTFILE" where WAVEFILE is a .wav file that has a message hidden in it, and OUTFILE is an empty text file.
	
	- To bring up the help text, type " python3 wave_decode.py --help"
	
- [Running on Windows]
Has not been tested yet, sorry. 
