# NumberGuess
create true and false constants
create variable for attempts
create keepGoing boolean
create random int called winningNumber

print "Hello, what is your name" 
take input and store as variable 'username'
print statement that greets user and introduces game
take input for guess stored as variable 'guess'
while loop: keepGoing = true
	if guess = winning number 
		attempts += 1
		print "You win! The number was {variable}"
		keepGoing = false
		if attempts < 7
			print "great job"
		elif attempts == 7
			print "you did ok"
		else
			print "that took you a while"
