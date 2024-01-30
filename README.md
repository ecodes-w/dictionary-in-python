# Lab Instructions: Mapping key-values to Dictionary data structures 


> #### **To run your Python code**
> - Select your Python file in the Visual Studio Code file tree 
> - You can right click the file and select "Run Python File in Terminal" 
>   or run the file using the smaller   
    play button in the upper right-hand corner 
>   of VSCode.  
    (Select "Run Python File in Terminal" in the provided button dropdown)
> - Alternatively, you can follow lab instructions which use python3 commands to run your code in terminal.
> 
 <br><br> 

## Exercise Instructions

1. Open the `comprehensions.py` file

2. Implement the `to_mod_list()` function by using the `map()` function to apply `mod()`
   to all elements within `employee_list`.  
    Assign the result of it to a new variable called `map_emp`. Convert `map_emp` to a list and return it. 
   - The `mod()` function returns a string value for example such as `“Lisa_Cold Storage”` from the dictionary passed to it. <br><br>

3. At this point you should have a list of the values such as: `“Lisa_Cold Storage”` mentioned above.  
But that is no good for a username with the whitespace present in it.  
    - Implement the `generate_usernames()` method by using list comprehension and the `replace()` over `mod_list`  
  to replace all spaces `(" ")` with underscores `("_")`. 
    - Return the resulting list. <br><br>

4. We want to create a dictionary that stores employees' first initials and IDs. 
    - Implement `map_id_to_initial()` by using dictionary 
comprehension over the `employee_list` to create a dictionary   
where each key is the 
first letter of an employee's name and the value is the employee's ID.<br><br>

5. Run the script by opening the terminal and executing the command:
    ```
    python3 comprehensions.py
    ```

<br>



