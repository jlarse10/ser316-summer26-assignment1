**dev** (branch from main)  
5f95961 adds encouraging message

**feature1** (branch from main)  
3bbc201 adds quitting
f8dfe81 adds replay value
9df380f improves feedback
f48cf81 adds comments

**feature2** (branch from dev)  
45aa640 adds beginnings of maxAttempts
e367776 finalizes logic for maxAttempts and game over

**feature3** (branch from main)  
f1097b6, c070288, 3631e47, 1f23d1c hint feature added /w sloppy commits

**hotfix** (branch from main)  
ab7cd7b fixes randomInt

**main**  
4576c4 initial commit

**LEARNING SUMMARY**  
merge is best used for when a feature has been completed or a branch is ready to be merged with 
another. This was the case with the feature1 branch, where commits were organized and followed
a flow. Merge will be the best for maintaining a clean repository and will be my go-to.

rebase is useful when you are trying to keep a branch's history linear and reduce noise. With
feature2, this branched from dev, so it was rebased to keep the history clear. Rebase will be best
used if there may be any confusion / if the graph gets too messy.

squash is reserved for extra, unnecessary commits or when things get sloppy. This was demonstrated
in the feature3 branch where there was multiple commits for 1 feature being added / fixed. I will
reserve this command for mistakes made during commits.

cherry-pick is used when there is one specific commit that needs to be applied, usually to the main
branch, like with the "hotfix" branch. This will best be used if there is an important update that
needs to applied universally.