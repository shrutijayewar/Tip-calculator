# Tip-calculator

The first line gets the element with the ID "tiplabel" and hides it. This is because the tip amount will not be displayed until the user clicks the "Calculate!" button.

The second line gets the element with the ID "calcbtn" and listens for a click event. When the button is clicked, the code in the anonymous function will be executed.

The third line of the anonymous function gets the values of the three input fields.

The fourth line calculates the tip amount by multiplying the bill amount by the service quality and dividing by the number of people.

The fifth line sets the value of the text field with the ID "totaltip" to the tip amount.

The sixth line displays the tip label by setting its display property to inline.
