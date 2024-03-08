--------------------------------------------------------------------------
README 
--------------------------------------------------------------------------

Author		- C.Greeshma (200020012, IIT Dharwad, BTech-24)

Filename	 	- ./supervised.py

Description	- HMM based POS tagger using supervised learning technique.

Usage		- python supervised.py <training_file_path> <test_file_path> 
	
Example		- Few of the sample executions are given below

		- python supervised.py 1 ./data/kannada_testing_sentences_full.txt
		- python supervised.py 1 ./data/kannada_testing_sentences_100.txt
		- python supervised.py 0 ./data/kannada_testing100.txt
		

Output		- ./output/kannada_tags.txt
		- For each word in test file, <word>_<tag> will be printed in output file.

Argument Details

	-- "training_file_path" 

		~ 0 - kannada_training
 		~ 1 - kannada_training1


	-- "test_file_path"

		~ Path of the file that contains testing sentences.
		~ Each line should contain one sentence.
		~ See ./data/kannada_testing100.txt for reference.


References : https://github.com/rajesh-iiith/POS-Tagging-and-CYK-Parsing-for-Indian-Languages/tree/master
