# NgClass
-ngClass is a directive which is used to set the class name for DOM elements
- [ngclass] =""
- common mistake -case sensitive of ngClass
                 - string quotes

- Examples 
        - simple using static class name
        - dynamic - from the component
        - array classes - to pass more than 1 class we use array [clsName,clsName2]
        - ngClass with Expression to true and false
# NgStyle
- ngStyle is used for setting the style attributes of DOM elements
- we can set one or more properties
- common mistake = [ngStyle] case sensitivity


# NgFor
- Similar to For loops that we use in other programming languages
- Don't worry about {{ }} -data binding 
- Provides local Variables in the array data
- Index - gets the current index of the current element in iteration ,its very important whenever DOM manipulation
- First - returns true if the current element is the first element in iteration
- last  - returns true if the current element is the last element in iteration
- Even  - gets the even number
- odd   - gets the odd number in iterations
<img src = "src/app/assets/images/ngFor.png">


# NgSwitch
- ngSwitch
    - build-in directive
    - starts with *ngSwitchCase
    - it is used to compare more than one expression at one time unlike ngIf which usually resolve to true or false/boolean values
    - We can have multiple checks in ngSwitch
    - *ngSwitchCase - Where we will mention about the check condition/expression
    - *ngSwitchDefault - what it should do when no condition is matching 
     can be read the value dynamically
    - Example - we can pass any value - can be integer/string etc.
    - where we make mistakes
    - missing out on *
    - for the string values - put the "'Strings'"
    - when using switch -> [ngSwitch] - look out on the case sensitivity
    <img src = "src/app/assets/images/ngSwitch-0.png">
    <img src = "src/app/assets/images/ngSwitch-1.png">
    <img src = "src/app/assets/images/ngSwitch-2.png">
