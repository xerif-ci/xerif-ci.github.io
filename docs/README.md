# What should be implemented

1. after each commit xerif will check all changed files to update the branch observer 
`$ git diff --name-only COMMIT^!` (it will print all cahged files)

2. It will allow xerif to compare all branches with possible conflicted files (comparing all lines branch by branch)
