
# Git_Assignment

This is like a full real-world Git test!
## Question 1: Project Initialization & First Push 

Objective: 
Set up a new Git project and push it to a remote repository.

Scenario: 
You are starting a new Python project. You need to track your work using Git and upload it to a remote repository.

## Tasks
Create a new folder for your project
Initialize a Git repository

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/project_creation.png)

Create a file named app.py and add some Python code

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/code_created.png)

Check the current Git status
Stage the file
Commit with a meaningful message

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_status_check2.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_first_commit_app_py.png)

Create a remote repository (GitHub or similar)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/created_remote_repository_using_github_web.png)

Add the remote (origin) to your local repo
Verify the remote configuration
Push your code to the remote repository## Screenshots

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_push_which_failed.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_push_and_pull_request.png)

## Question 2: Working with Changes & History

Objective: 
Track code changes and manage commit history properly.

Scenario: 
You are enhancing your existing app.py application with new features.

## Tasks
Modify app.py by adding new functionality
Check what changes are made before staging
Stage only specific changes (if possible)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_diff_used.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_selective_staging.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/second_commit.png)

View differences in the file
Commit with a clear message
Make another change in app.py
Stage all changes
Commit again
View full commit history

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_commit_for_checking_the_logs.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_add_staging_app_py.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_log_in_details.png)

View compact (one-line) history

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_log_oneline.png)


## Question 3: Branching & Feature Development

Objective
Work with branches and manage feature development.

Scenario
You are developing a new feature separately to avoid affecting the main code.

## Tasks
Create a new branch (e.g., feature-update)
Switch to the new branch

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_branch_and_its_creation.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_switch_with_current_branch_status.png)

Modify app.py with new feature logic
Stage and commit the changes

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_feature_branch_code_changed.png)

Switch back to the main branch
Merge the feature branch into main

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_switch_to_main_and_merge_feature_branch.png)

Verify changes are merged
Delete the branch safely

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_feature_branch_deletion_after_merging.png)

Try force deleting a branch (create a dummy branch for this)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_dummy_branch_creation_and_deletion.png)


## Question 4: Handling Errors (Stash, Reset, Revert)

Objective
Learn how to manage mistakes and unfinished work.

Scenario
You are in the middle of development but need to handle urgent changes and fix mistakes.

## Tasks
Make changes to app.py but do NOT commit
Stash the changes (include untracked files)
Check the stash list
Apply the stashed changes back
Commit the changes

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_stash_stash-u_stash_list_stash_apply_and_commit.png)

Make another commit with incorrect code
Undo the last commit using reset
Make another commit
Undo a commit using revert (create a new reversing commit)
Verify the commit history


![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_reset_with_wrong_commit_part1.png)


![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_reset_with_wrong_commit_part2.png)


![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_reset_with_wrong_commit_part3.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/gt_revert_after_fixing_code.png)

![App Screenshot](https://github.com/HamidSiddiqui12/git_assignment/blob/1a709f62495463d2605b6783b0b9d2535a91fa3e/img/git_log_with_the_last_push.png)
## Footer

    Thank you!
