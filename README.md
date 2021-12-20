# UnityGitSetup
Steps to set up git to work correctly with Unity projects (with git bash)

## Step 1
Initialize the git repo.

## Step 2
Add a .gitignore file. Paste the contents of the provided .gitignore file of this repo into your own.
This removes all unnecessary files and folders from VCS.

## Step 3
Add a .gitattributes file. Paste the contents of the provided .gitattributes file of this repo into your file.
This file tells git to treat asset files as binary, so they aren't merged automatically.

## Step 4
Add a .gitconfig file. Paste the contents of the provided .gitconfig file of this repo into your file. Remove ".exe" if you're not on Windows.
This file tells git to use UnityYAMLMerge.

## Step 5
Add an entry to your PATH environment variable (if you haven't already).
The value should be the path to your Unity "tools" folder. E.g. C:\Program Files\Unity\Hub\Editor\\<unity_version>\Editor\Data\Tools

## Step 6
Change the following settings in Unity.
In Edit > Project Settings > Editor menu, choose Force Text under Asset Serialization Mode.
In Edit > Project Settings > Version Control menu, choose Visible Meta Files under Mode.

## Step 7
Save and add your Unity project files to VCS (and pray that everything works).
