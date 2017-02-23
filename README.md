Do a pull to repo
Then execute npm install -g backstopjs
Then run backstop genConfig -> this command should create backstop_data folder and backstop.json file.

You can update the json file to have the URL you wanna test and the selectors that your testing.

Then run backstop reference. This will generate the reference pngs for various devices.

Then running backstop test will do a test on the URL and show you the test resuult. 
