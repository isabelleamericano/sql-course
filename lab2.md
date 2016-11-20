### SQL LAB
# Where In The World Is Carmen Sandiego?, Part II


	Good Work, Gumshoe! Interpol gives you its greatest thanks.

	As we speak, agents are swarming the Santa Monica Municipal Airport, 
	intercepting Carmen Sandiego on her flight from Brasilia.

	... 

	But wait! Carmen Sandiego has foiled us again!


We're going to use what we've learned already about SQL aggregate functions, grouping, and JOINing tables, and apply it – to chase down and capture an elusive and world-reknowned thief.

Follow the clues, **write down both the commands you used and the actual answers.**

And figure out where Carmen's headed, so we can catch her and bring her in.


## The Chase

**Clue #1:** Someone fitting Carmen Sandiego's description just passed through the country with the highest life expectancy in the world. Which **continent** is she hiding in?

```
-- YOUR SQL QUERY GOES HERE
```

**Clue #2:** Interpol got word that Carmen is hiding in a country that has bigger problems than apprehending her. **On the same continent as #1**, which **country**'s GNP decreased the most since last year?

```
-- YOUR SQL QUERY GOES HERE
```

**Clue #3:** Carmen Sandiego wants to blend in. So, she must be hiding in the district of the country from #2 with the second-highest total population (not wanting to be too obvious). Which **district** is she in? (Note: Each city belongs to one district.)

Confirm you are on the right track -- exactly 3 cities are part of the district!

```
-- YOUR SQL QUERY GOES HERE
```

**Clue #4:** Immediately once you discover the district, agents flood the area to put Carmen Sandiego behind bars once and for all. Agents surround a suspicious ACME van, but ... again she eludes them! She's getting cocky again -- too cocky for her own good:

```
	Where I am now, I am finally content.
	Oh boy -- I didn't even leave the continent!
	
	I am relaxing in a place
	Where the district, city, and country are all the same.
	If you do not find me,
	You have only yourself to blame!
```

It's up to you, Gumshoe! Interpol is ready to spring on your word -- which **city** is Carmen Sandiego hiding in? **WHERE IN THE WORLD IS CARMEN SANDIEGO?**

```
-- YOUR SQL QUERY GOES HERE
```


###Follow-Up Challenges

* **Clue #1.** Which continent has the highest average life expectancy? (Hint: use AVG)
		
		``` -- YOUR SQL QUERY GOES HERE ```

* **Clue #2.** Which country in the world had the largest **increase** in GNP?
		
		``` -- YOUR SQL QUERY GOES HERE ```

* **Clue #3.** How many country districts contain exactly 18 cities?
		
		``` -- YOUR SQL QUERY GOES HERE ```

