# Git workbook

This workbook is a collection of small HTML/CSS snapshots for practising Git operations. The files are exercise material, not a deployed website. Work through each topic on a disposable local branch or clone so experiments do not affect another project.

## Exercises

| Folder | Git concept to practise |
|---|---|
| `CreateABranch/` | Create and work on a branch |
| `FeatureWorkFlow/` | Feature workflow |
| `ForkFlow/` | Fork-based workflow |
| `Merge/` | Merge branches and inspect history |
| `MergeConflicts/` | Resolve conflicting edits |
| `ModifyStagedFile/` | Change a file after staging |
| `RemoteBranchMerge/` | Merge work from a remote branch |
| `Rebasing/` | Rebase a branch |
| `RemoveFileFromSTagingArea/` | Unstage a file |
| `RenameFile/` | Track a rename |
| `Reset/` | Explore reset behavior |
| `Stashing/` | Save and restore uncommitted work |
| `cherrypick/` | Cherry-pick a commit |
| `gitignore/` | Practise ignore rules |

The capitalization and spelling of imported folder names are retained so existing examples remain easy to compare with the source repository. `init.sh` and the root HTML file are also preserved from the original workbook.

## Safe practice setup

```sh
git clone https://github.com/sanjay81/learning-hub.git
cd learning-hub/courses/git-workbook
git switch -c practice/my-exercise
```

For history-changing exercises such as reset and rebase, use a disposable clone or create a backup branch first. These snapshots do not currently include a step-by-step exercise sheet; add one as each scenario is refreshed and verified.
