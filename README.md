The project is about making an expense calculator.
HTML;
In html the layout for the expense calculator is made
Containing the 
    -> Title of the project"expese calculator"
    -> Input fields for entering the description and the the type of amount
    -> A dropdowm list for choosing the type (income or expense)
    -> Button for adding the entered amount into the list
    -> Button for editing and deleting the added data
    -> Three radio buttons containing all,income,expense
    -> These radio buttons show only the respective type from the list
    -> Then total income and expenses is shown
    -> And net balance is calculated from that
    
CSS;
    The html layout is hown in the web browser as per our wish by making the changes using css

JavaScript;
All the functions that take place in the expense calculator are made in js
    -> Fist it is startded with an empty array
    -> Then a funtion is created for adding the entry to the list
    -> Then the code for calculating total income,expensesand netbalace is made
    -> A list is created for each addentry 
    -> the entries are filtered by there type(all,income,expense)
    -> These are then stored in the local storage
    -> A funtion is made for showing these datas in the webpage
    -> Then the function for editing deleting the existing datas are made
    -> when the dom iis loaded the inputs are made empty
