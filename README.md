# VolumeConeRadHeight

Suppose your math professor asks you to create a calculator to determine the volume of a cone based on its height and radius. To make it more charming you decide that your program will ask the user’s name before asking for the needed data to calculate the volume. You must use the formula shown below where r is the radius and h is the height of the cone.

The height and the radius must be whole numbers, but the volume must be a double precision real number with three decimal digits.

To solve this problem your program must perform the following tasks:
Declares a global constant variable called PI above main() that holds value 3.141592
Declares a variable named name that holds text
Declares variables named height and radius that hold whole numbers
Declare a variable named volume that holds double precision real numbers
Prompts the user "May I get your first name please?: "
Read the value from the keyboard and stores it in name
Prompt the user "Thanks ", name, ", now enter radius and height of the cone please: "
Read the values from the keyboard and stores them in radius and height respectively
Call function volume_cone() to calculate the volume of the cone and assign the result to volume Call function print_data() to print the values entered by the user and the volume of the cone

1) To calculate the square of a number you must define a value-returning function named square( ). It receives a real number and returns its squared value (a real number). You must use it to calculate the square of the radius. Do NOT use pow() in THIS FUNCTION to determine the square of the value received.
2) To calculate the volume of the cone you must define a value-returning function named volume_cone(). It receives the radius and the height of the cone (whole numbers) and returns the calculated volume (a real number) . To round the volume use the round_off() function that you created for lab 6 (see below please). Implement the formula for the volume of the cone exactly as it is displayed above.
3) To round a number define a value-returning function named round_off( ). It receives the number to be rounded (a real number) and the number of decimal digits that the number should be rounded to (a whole number), and returns the number rounded to the specified number of decimal digits.
4) To print the data you must define a void function named print_data( ). It receives the name (text), the radius of the cone (a whole number), the height of the cone (a whole number), and the volume of the cone (a real number). After formatting the output to display the volume in fixed format with three decimal digits it displays the following message (n, r, h, and v are the name, the radius, the height, and the volume respectively):


FOR TESTING

enter : Emma 
enter : 5 5
display should be : 

May I get your first name please?: Emma

Thanks Emma, now enter radius and height of the cone please: 5 5

Ok Emma

For a radius: 5 and a height: 5 the cone's volume is 130.900

Testing your solution
