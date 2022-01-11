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