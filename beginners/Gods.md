# Gods

## Complexity 26%

Archaeologists have found a set of ancient copies of ancient manuscripts with myths - various stories about ancient gods. Unfortunately, the scribes of these manuscripts were not particularly literate and managed to make exactly one spelling mistake in each name — that is, exactly one of the letters of the divine name was replaced with some other letter. Archaeologists were able to make a list of the correct spelling of the names of the gods, as well as they were able to write out all the proper names from the manuscripts. However, to compare the two lists - over their strength. Help them with this!

INPUT contains the number N - the number of god names in the list. The next N lines are the names of the gods. Next comes a line containing the number M - the number of “suspicious” words written out from the manuscripts. The next M lines are “suspicious” words. Each of the names of the gods and “suspicious” words is a sequence of K capital letters of the English alphabet (1 ≤ N, M, K ≤ 30).

OUTPUT displays N numbers — for each divine name, the number of “suspicious” words, which are the name of the given god with one error, is output.


| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 3         						| 2 1 0	      			 |
| ZEUS	 							|						 |
| POSEIDON 							|						 |
| AFINA     						|						 |
| 4 								|						 |
| ZEVS	 							|						 |
| POSEYDON  						|						 |
| AVYNA								|						 |
| ZERS								|						 |
