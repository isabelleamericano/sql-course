### SQL LAB
# Where In The World Is Carmen Sandiego?, Part III


	Good Work, Gumshoe! Interpol gives you its greatest thanks.

	As we speak, agents are swarming the Santa Monica Municipal Airport, intercepting Carmen Sandiego on her flight from Brasilia.

	... 

	But wait! Carmen Sandiego has foiled us again!

	A truck bearing the logo 'Sakila' was seen leaving the airport, before our agents could intercept it. Hmm Sakila ... a DVD rental company known as a front for V.I.L.E. 


## The Chase

Figure out where Carmen's headed, so we can catch her and finally bring her in. Follow the clues! **Write down both the commands you used and the actual answers. CHALLENGE: Write a single SQL query that _only_ returns the answer.**


**Clue #1:** 

	Passenger: "She was renting DVDs on Sakila.com during the entire flight! 

We know that Carmen Sandiego rented at least one film, so she must be a customer. Could she also be a staff member? **Which customers (if any) have the same last name of a staff member?**


**Clue #2:** 

The staff members checked out, so we must now find which customer is Carmen Sandiego!
	
	Passenger: "I looked over her shoulder. She was renting from the store that had the fewest films in its inventory!"

Quick! We must swarm the store to intercept Carmen as she picks up the DVDs! Gumshoe -- which Sakila store number has the fewest number of films available to rent in its inventory?


**Clue #3:** 

Due to your sleuthing, Interpol agents swarmed the Sakila store! But, the DVDs must have been shipped to her home address.

	Passenger: "She opened her history and she's rented at least 40 movies!"

Which customers have rented at least 40 movies?



**Clue #4:**

She got cocky again and left another note:

	Of those who rented at least 40 movies, I am me!
	I am the only one of them who got a movie for free!

We're counting on you, gumshoe. 

What is Carmen Sandiego's home address, including address, city, and country? Find out where she'll pick up the DVDs, send us the info, and we'll take care of the rest!





**BONUS 1**

Which actor is in the most films?



**BONUS 2**

Which category did this actor perform most in?
