# UiPathRPA-RegEx (Regular Expression):

In this demo, we will use RegEx to find all the street names and numbers in a string containing multiple addresses. 
Print all matches to output.

Use following steps in UiPath Studio:

    I started the project as a Sequence and used an Assign for a newly created String variable.
    I used the Matches activity to identify the street names and numbers by:
        Setting the Type as Advanced
        Adding the “road”, “drive”, “avenue” and so on in the Value field;
        Using the Exactly quantifier with the value 1;
        Making sure the IgnoreCase box was checked.
    I used a For Each activity to loop through the output variable of the Matches activity and print it using a Log Message activity.
