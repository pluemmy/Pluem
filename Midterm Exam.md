RECEIVE TEMPERATURE FROM SENSOR
IF TEMPERATURE < 18 C THEN 
SEND "Cold, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
ELSE IF TEMPERATURE > 21 C THEN
SEND "Perfect." TO DISPLAY
ELSE SEND "No! The perfect temperature for sleep is 18-21 degrees." TO DISPLAY
END
