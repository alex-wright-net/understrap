## Local Implementation

1) Create local directory and local url for project

2) Download WP Engine install, copy into local project directory

3) Copy WP Engine .gitignore file for not version controlling core WordPress files

4) Initialize git repository

5) Set GitHub remote

6) Install custom local instance of understrap:

	$ cd into root of local install

	$ git remote add understrap git@github.com:alex-wright-net/understrap.git

	$ git subtree add --prefix=wp-content/themes/xxcustom-themexx/ understrap-child dev

7) Install understrap-child