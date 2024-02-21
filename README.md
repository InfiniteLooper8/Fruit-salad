# Fruit-salad
Create a function that checks ingredients required for making a fruit salad and confirms if any servings could be made based on available fruit quantities
> This function uses arithmetic, relational and logical operators
## Step 1
**Function make_fruit_salad(number_of_servings)**
{
> *Arithmetic Operators: Determine the amount of each fruit based on servings*

- apples_needed = number_of_servings * 1 // 1 apple per serving
- bananas_needed = number_of_servings * 2 // 2 bananas per serving
- oranges_needed = number_of_servings * 3 // 3 oranges per serving

 >*Assume we have a fixed number of each fruit available*

 - available_apples = 25
 - available_bananas = 15
 - available_oranges = 33
  
## Step 2
> *Relational Operators: Check if enough fruit is available for serving*

 **enough_fruit = If (available_apples >= apples_needed) AND (available_bananas >= bananas_needed) AND (available_oranges >= oranges_needed)**

 ## Step 3
> *Logical Operator: Make fruit salad if enough fruit and servings are more than 0*

  **If (enough_fruit AND number_of_servings > 0)** 
{
    return "Yes, you can make the fruit salad."
  }
  else
  {
    return "No, you cannot make the fruit salad."
  }
}
