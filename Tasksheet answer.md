#Task sheet

##Question 3a

1. function: GetPlayerName()
2. creating a while loop controled by a boleen value of a 'valid' if statement.
3. I created a 'valid' variable with boleen 

choice: REFERENCE
valid: BOLEENE
PlayerName: STR
Functon: GetPlayerName():
	output('')
	choice = GetcHOICEfROMuSER('Do you want to add your name to the high score table? (y or n): ')
	IF choice == 'y' THEN
		valid = FALSE
		WHILE valid == FALSE DO
			OUTPUT 'Please enter your name:'
			PlayerName = INPUT
			IF PlayerName != '' THEN
				valid = TRUE
			ELSE
				OUTPUT 'Enter a valid name'
			OUTPUT()
	Else if pLAYERnAME == 'N' THEN
		PlayerName = FALSE
	RETURN: PlayerName
END FUNCTION
				



notes