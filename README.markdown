# Araxis Merge Workflow for Alfred 2

This is the Alfred v2 workflow for those of you who use Subversion (or CVS for that matter) for version control. It helps with the tedious task of merging code between branches.

For example, let's say you have the following directory structure:

    dev
      |- project1
      |- project1_branch
      |- project2
      |- project2_branch

With this workflow you can select any file or folder in project1, then use the hotkey to open the Araxis Merge window with the comparison of this file between preject1 and project1_branch.

### Configuration

There is not much you need to configure to make it work:

1. Configure the desired hotkey.
2. Configure your projects and branch name in the apple script:
   - Open the workflow in Alfred v2 preferences.
   - Double click the apple script to edit it.
   - **Copy the entire text to your favorite editor!** Don't edit the apple script in the Alfred editor - it won't work, it would replace your regular double-quotes with some weird ones, which would make the workflow broken.
   - Change the name of your branch to *"_branch"*.
   - Specify the list of projects in "projects" constant.

### Usage

There are 2 main ways you could use this workflow:

- Select any file(s) or folder(s) in your trunk, use the hotkey to open the merge.
- Open Alfred and type "merge* anything", Alfred would look for files in your projects and display them in the list as usual. Then you could select a file and hit Enter to open the merge.

### Requirements

- Alfred v2 Powerpack.
- Araxis Merge.

### Author

Done by [Eugene Naruta](https://github.com/enaruta).
