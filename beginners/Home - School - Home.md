# Home - School - Home

Alex rides the metro every day. In the morning he goes to school, and in the evening of the same day, back from school, home. In order to save a little, he buys an electronic smart card for X trips. When he wants to go to the subway, he puts the card to the turnstile. If a non-zero number of trips remains on the card, the turnstile allows to enter Alex and writes off one trip from the card. If there are no trips left on the map, then the turnstile will not let Alex in, and he (Alex) has to buy a new card on the same station for X trips and again pass through the turnstile.

Alex noted that due to the fact that the metro is full in the morning, it is expensive to buy a new card in the morning, and he may be late for school. In this regard, he wants to understand: will there be such a day that in the morning, when he went to school, Alex will find zero trips on his card.
Alex does not go anywhere else on the subway and therefore he enters the subway only at the station near the house and at the station near the school.

INPUT contains exactly 2 lines. The first one contains the word “School” or “Home”, depending on where Alex bought the card for the X trip for the first time. The second line contains the positive integer X, 1 ≤ X ≤ 1000.

OUTPUT should be output “Yes”, if there is such a day that Alex will have zero trips on the card in the morning and “No” otherwise.


| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| Home								| Yes  					 |
| 1	  						        |                        |
|-----------------------------------|------------------------|
| School 							|					     |
| 2	  						 	    | No                     |
