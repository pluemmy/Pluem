SET mystNumb = 3
SEND "please send input number" TO DISPLAY
RECEIVE guess_number FROM KEYBOARD
IF guess_number >10 THEN
SEND "Too high! Your guess must be between 1 and 10"
ELSE
IF guess_number < mystNumber THEN
SEND "Too low! Your guess must be between 1 and 10" TO DISPLAY
ELSE IF guess_number = Number THEN
SEND "Correcct Guess!"
END
