## GIT COMMANDS

```git push -u origin main```
- sets the upstream
- means you don't have to restate the 2nd part

main = master (updated term) (main branch)

```git add . ```
- add the same file you added last time

```git remote -v``` 
- tells you what remote git repo folder is connected to

origin 
- means GitHub itself

## DEBUGGING STRATEGIES

LABEL your console.logs
- ```console.log("Args: ", args)``` > ```console.log(args)```
- much easier to keep track

## GENERAL CODE TIPS

for of is the best option for looping through arrays
forEach of traditional for loops are good when you need to reference the index

```process.exit()``` will stop the current execution
- better than ```return``` since exit process is more explicit than returnnothing

Single Responsibility principle: each function should have a single goal
- better to have several small functions
- more reusability and increased modularity 

## FUNCTIONS BEST PRACTICE

1. Give your functions precise verb/action based names
2. Use camelCasedNames (like this one)
3. Properly indent the function code
4. Functions should focus on a single task: returning a value or causing a side effect. Break your function into additional smaller functions if you find it doing two or more things
  - One single task could be to compute and return a value (eg: zeroPad)
  - Another single task could be to perform a side effect such as logging a message to the screen (eg: printFarmInventory)
5. Data needed by Functions should be passed in as parameters/arguments (i.e. local scope) instead of being accessed directly