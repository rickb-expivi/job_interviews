# General
* What programming language do you prefer?
* What languages can you work with? Describe experience.
* Do you keep up with current trends and advances in the field? / How do you keep your programming and technical knowledge up to date?
* What is your field of expertise and what would you like to learn more about?
* What frameworks do you prefer? Why?
* Thoughts/experience with unit testing?

# C++

## How would you improve this?
```
vector<int> GenerateSequence(int minValue, int maxValue)
{
	vector<int> v;
	for(int i = minValue; i < maxValue; i++)
		v.push_back(i);
	return v;
}
```

* `assert(minValue <= maxValue);`
* `i <= maxValue`
* pre-allocation
* `iota`
* 
# PHP

## What is the differnce between $y and $$y?
```
$y = 'q';
$$y = 100;

echo $y;
echo $$y;
echo $q;
```
q, 100, 100

## How many arrays are there in PHP?

 1. Indexed
 2. Associative
 3. Multi-dimensional

## What is the difference between include() and require()
If the function require() cannot access the file then it ends with a fatal error. However, the include() function gives a warning, and the PHP script continues to execute.

## What are the scope levels & their definitions?
1. **public** - Visible to any other code accessing the class
2. **private** - Visible only in its own class
3. **protected** - Visible only to classes parent(s) and classes that extend the current class

## How to prevent SQL injections?
Check & escape user input

## What is the result of `016 / 2`?
7

## What does the keyword `final` mean?
Functions cannot be overwritten, class cannot be extended.
