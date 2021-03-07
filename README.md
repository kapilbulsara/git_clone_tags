# Git Clone Tags

This simple script clones tags into individual repositories or branches depending on your choice. 

## Why? 

One scenario where this could be useful is when creating plugins or mods for existing projects. One may want to test the plugin with different versions of the main project. Here,  we are assuming that tags will equate to different releases. 
The git way would be to create multiple branches within a single repository, however, to have demos of different versions, it may be useful to create separate repositories for each tag. Both options are available. 

## Usage 

`git_clone_tags <repo_source> <destination_folder> [repo|branch]`	

