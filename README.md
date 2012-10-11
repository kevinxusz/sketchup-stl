sketchup-stl
============

A SketchUp Ruby Extension that adds STL (STereoLithography) file format
import and export.

To get the code and make a change, here are some steps.

// Get a local copy of the files. This will create a sketchup-stl folder.
git clone https://github.com/SketchUp/sketchup-stl.git
cd sketchup-stl
git branch editing-readme             // Makes a new branch.
git checkout editing-readme           // Makes that branch active.
git add README.md                     // Marks README.md for edit.

// Use your favorite editor to edit README.md. Then...

git commit -m "Editing our README"    // Records changes in the local branch.
git checkout master                   // Changes back to master.
git merge editing-readme              // Merges your branch into master.
git branch -d editing-readme          // Deletes that temporary branch.
git push                              // Submits to repository. Yay!