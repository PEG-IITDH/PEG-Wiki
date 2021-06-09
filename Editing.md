#### Editing 
The easiest way to edit a page on this wiki is to click on the edit button on the top of the page. New pages can be created using the "create" button.  The content of a page is written in "Markdown" syntax - which means it is mostly plain text with some symbols and annotations to add formatting. For more details on syntax see the [CommonMark](https://commonmark.org/help/) syntax guide.

#### Editing Locally
If you have Ruby installed, you can clone this repo on your local machine, make edits locally, and then push changes back to Gitea.

1. To find the clone URL for the wiki, look for the clone URL on the top of the Gitea Page. Note that the URL should end in ".wiki.git"
2. Clone the repo locally
3. Install Gollum: ```gem install gollum```
4. Launch Gollum in the directory where the wiki files have been cloned: ```gollum ./```
5. View and edit the local files by pointing a browser to ```http://localhost:4567```
6. Make sure to save and then commit and push the changes upstream after all edits are done.