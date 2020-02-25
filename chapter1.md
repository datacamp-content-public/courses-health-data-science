---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

Calculations with variables
Remember how you calculated the money you ended up with after 7 years of investing $100? You did something like this:

100 * 1.1 ** 7
Instead of calculating with the actual values, you can use variables instead. The savings variable you've created in the previous exercise represents the $100 you started with. It's up to you to create a new variable to represent 1.1 and then redo the calculations!

`@instructions`
Create a variable growth_multiplier, equal to 1.1.
Create a variable, result, equal to the amount of money you saved after 7 years.
Print out the value of result.

`@hint`
To create the variable growth_multiplier, use growth_multiplier = 1.1.
In the example code block of the assignment, replace 100 with savings and 1.1 with growth_multiplier: savings * growth_multiplier ** 7.
Use the print() function to print the value of a variable.

`@pre_exercise_code`
```{python}
# Create a variable savings
savings = 100

# Create a variable growth_multiplier
growth_multiplier=1.1

# Calculate result
result = savings*growth_multiplier**7

# Print out result
print(result)
```

`@sample_code`
```{python}

```

`@solution`
```{python}
# Create a variable savings
savings = 100

# Create a variable growth_multiplier
growth_multiplier = 1.1

# Calculate result
result = savings * growth_multiplier ** 7

# Print out result
print(result)
```

`@sct`
```{python}

```

---

## Create a list

```yaml
type: NormalExercise
key: a2f32bf19c
xp: 100
```

<!-- Guidelines for contexts: https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->

As opposed to int, bool etc., a list is a compound data type; you can group values together:

```
a = "is"
b = "nice"
my_list = ["my", "list", a, b]
```
After measuring the height of your family, you decide to collect some information on the house you're living in. The areas of the different parts of your house are stored in separate variables for now, as shown in the script.

`@instructions`
<!-- Guidelines for instructions https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
- Create a list, areas, that contains the area of the hallway (hall), kitchen (kit), living room (liv), bedroom (bed) and bathroom (bath), in this order. Use the predefined variables.
- Print areas with the print() function.

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- You can use the variables that have already been created to build the list: areas = [hall, kit, ...].
- Put print(areas) in your script to print out the list when submitting.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Create list areas
areas=[hall,kit,liv,bed,bath]

# Print areas
print (areas)

```

`@solution`
```{python}
# Area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Create list areas
areas = [hall, kit, liv, bed, bath]

# Print areas
print(areas)
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
Nice! A list is way better here, isn't it?
```
