# Araxis Merge v1.0

This is the Alfred v2 workflow for those of you who use Subversion for version control. It helps with the tedious task of merging code between branches.

For example, let's say you have the following directory structure:

    dev
      |- project1_trunk
      |- project1_branch
      |- project2_trunk
      |- project2_branch

With this workflow you can select any file or folder in in project1_trunk, then use the hotkey to open the Araxis Merge window with the comparison of this file between preject1_trunk and project1_branch.

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

Select any file or folder in your trunk, use the hotkey to open the merge.

### Requirements

- Alfred v2 Powerpack.
- Araxis Merge.

### Author

Done by [Eugene Naruta](https://github.com/enaruta).
