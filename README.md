Download Link: https://assignmentchef.com/product/solved-functional-overload
<br>
<strong><u>Objective</u></strong>: The aim of this assignment is to have you become more familiar with how to define functions, as well to further develop your critical thinking skills. You are required to write <strong><em>eight</em></strong> functions as specified below. However, it will be up to you to define the function and make sure that they are working as intended. Do note that the names of the function <strong><em>MUST</em></strong> be spelled as they are shown, along with any given parameter as well.




<strong><u>Required Functions</u></strong>




<h2>is_int(data)</h2>

<em> </em>

<strong>Description</strong>: Given some information (can be a string, or a float, etc) in the form  of the parameter data, determine if it is an integer data type. If it is, return <strong>True</strong>.  Otherwise, return <strong>False</strong>.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value</strong>: Return <strong>True</strong> if the passed parameter data is an integer data type.

Otherwise, return <strong>False</strong> if it is not.




<h2>            is_even(n)</h2>




<strong>Description</strong>: Given an integer <em>n</em>, determine if it is an even integer, or an odd integer. The mathematical definition of an even integer is one such that the  following condition is met: <em>n</em> = 2<em>k</em> for some <em>k</em>. Likewise, for an odd integer the  following condition must be met: <em>n</em> = 2<em>k</em> + 1 for some k. <strong>Note that, based on these  definitions you must determine if the operation of <em>n</em> and 2 returns a 0 (for even)  or a 1 (for odd).</strong> This operation is one you are already aware of.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value</strong>: Return <strong>True</strong> if the passed integer n is even. Otherwise, return <strong>False</strong>. <em>string_contains_char(str, ch) </em>

<em> </em>

<strong>Description</strong>: Determine if the passed string <em>str</em> contains the character <em>ch</em>.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value: </strong>Return <strong>True</strong> if the passed character is found within the string.  Otherwise, return <strong>False</strong>.




<h2>            find_distance_traveled(time, rate)</h2>

<em> </em>

<strong>Description: </strong>Given a <em>time </em>(in minutes) and a <em>rate </em>(in feet per minute), determine  the distance traveled. This is a well-known formula in mathematics, and as a  refresher it is the following: <em>distance = time * rate</em>.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value</strong>: This function must return a float data type. Please disregard the  precision of the computed value.




<h2>             print_travel_data(dist, time, rate)</h2>




<strong>Description</strong>: Of the three parameters, one will be guaranteed to be a zero. With  the other parameters (which will be positive and non-zero), calculate the value of  the “missing” parameter and print it to the screen. For example, if the parameter  <em>dist</em> is equal to 0, calculate the distance traveled. If the parameter <em>time</em> is equal to  0, calculate the time spent traveling.




<strong>Output</strong>: As examples, if the <em>dist</em> parameter is found to be 0, print the following string, excluding quotation marks: “Distance traveled: 12.00 feet”. If the <em>time</em> parameter is found to be 0, “Time spent traveling: 2.50 minutes”. If the <em>rate</em> parameter is found to be 0, “Rate traveled: 22.37 feet per minute”. <strong>NOTE THAT THESE ARE SAMPLE OUTPUTS AND THAT THE NUMERICAL VALUES MUST COME FROM THE VALUES YOU COMPUTED</strong>. Do note that this output contains formatted output, and that the floats must be to a precision of 2 decimal points.




<strong>Return Value</strong>: None. This is a void function.




<h2>            fahrenheit_to_celcius(f)</h2>




<strong>Description</strong>: Given a temperate <em>f</em> that is in degrees Fahrenheit, convert it to its  equivalent value in degrees Celsius. Please reference the following formula:  <em>C = (F – </em>32) * (5.0/9.0).




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value:</strong> This function must return the equivalent Celsius temperature as a  float data type. Please disregard the precision of the computed value.




<h2>            find_floor_distance(floorOne, floorTwo)</h2>




<strong>Description</strong>: Two floors in a building will be passed to this function. The distance  between these floors must be found. For example, if the 5<sup>th</sup> floor and the 3<sup>rd</sup> floor  are passed, the distance between them is 2 floors. During testing, note that a value  of 0 may be passed into the function. For the purposes of this assignment, assume  that this cannot occur. As such, return a -1. In addition, if the calculated distance  is found to be negative, convert it to a positive.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value</strong>: Return the value of the distance between both floors. If either of  the values of the parameters is 0, return a -1.




<strong>Special Restriction</strong>: Do <strong>NOT</strong> use the <em>abs() </em>function.




<h2>             find_inclusive_sum(start, end)</h2>




<strong>Description</strong>: Given a <em>start</em> and an <em>end</em>, determine the inclusive sum between them.  For example, the return value of <em>find_inclusive_sum(1, 5)</em> would be 15 as 15 = 1 +  2 + 3 + 4 + 5. Note that this sum <strong>CANNOT</strong> be negative, which can only happen if  the <em>end</em> is greater than the <em>start</em>. If this occurs, return a -1. If the <em>start</em> and <em>end</em> are equal to one another, return the value itself. For example,  <em>find_inclusive_sum(5,5) </em>will return 5.




<strong>Output</strong>: This function should not print anything onto the screen.




<strong>Return Value:</strong> Return the inclusive sum of the specified numbers. Return -1 if <em>start</em>  is greater than <em>end</em>.