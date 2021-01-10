# dh-link-creator

# WHAT?
dh-link-creator is a simple, single-page app completely built with HTML, CSS, and JS to create shareable links that will make a copy of an individual's repo to the user's UC Berkeley DataHub instance.

Example Link/Badge (Will open UC Berkeley DataHub in this tab): 

[![DataHub](https://i.ibb.co/s5V7XbX/badge-logo.png)](http://datahub.berkeley.edu/hub/user-redirect/git-sync?repo=https://github.com/SoyCarlos/Intro-To-Making-Data&subpath=Intro-to-Making.ipynb)

# WHO & WHY?
I am Carlos Eduardo Ortega, current senior at UC Berkeley entering my final semester. I am also a a Peer Consultant under CDSS DSUS. We host a good amount of workshops, and as such, end up making a good amount of DataHub links. This will hopefully make it a bit easier and not require us to remember the exact format.


# HOW?
[![DSUS Consulting](https://i.ibb.co/s5V7XbX/badge-logo.png)](https://data.berkeley.edu/consulting/)

There are two user input text fields here:
1. Link to Github Repo
	- Ex: https://github.com/ds-peer-consulting/fa20-intro-to-python-library-workshop 

2. Subpath to Notebook File (Optional)
	- Ex: intro-to-python.ipynb
	- Ex: path/to/notebook.ipynb


Link to the github repo should be the main page of the repo that is being shared, note that it does not end in .git, it is only the URL. 

The subpath is optional. Adding the subpath will automatically open the notebook when someone clicks the link, otherwise it opens up to the copied directory in DataHub. Note, whitespaces are weird. If your subpath to the notebook contains a whitespace it might work, but it is not guaranteed. It is recommended to rename files to remove any whitespaces prior to creating the DataHub Link. Also, even if the link does work, the badge will not attach the hyperlink correctly, so it is better to just rename your file.

By the nature of DataHub, clicking the link will not update a repo that has had any changes and the repo cannot be copied into a user's DataHub directory if they have another folder already by the same name. To be able to copy over the repo the user will have to rename or remove the folder that shares the name with the repo. DataHub links should only be shared once the repo is finalized and ready to share. 


Submit an issue if you find any bugs or requests, or tweet me.


# To-Do:
1. Improve badge logo 💤
2. Make site pretty 💤

### Attributions
Bear icon from Mozilla, CC BY 4.0 <https://creativecommons.org/licenses/by/4.0>, via Wikimedia Commons