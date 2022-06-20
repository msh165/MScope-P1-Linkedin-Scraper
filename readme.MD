You will have to enter the password and profile email on your own. If the site is not working, linkedin probably must've 
changed the site architecture since this was written.
Please do check if the tag ID's and classes are matching. 
I will try to keep this updated (No promises though).

It accepts a list of URL's and gives output in a dataframe which you can download as a csv

Requirements - 
You need beautifulsoup, requests and selenium pre installed.

You also need to download chrome webdriver similar to the version of the chrome browser you have(you can use other webdrivers also but you'll need to tweak the code accordingly). Type about:: in your browser to get the version number and download accordingly.
Store this file in a folder called "Driver" inside the folder you have the main code in.

There are 2 major functions written - 
profile_scrap2(url) - Takes one URL, scraps all its data and outputs in a dictionary
dict_df(url) - Takes a list of URLs, uses the profile_scrap2 to get its dictionary and then inputs into a dataframe. It then returns the data frame

You need a list of linkedin profile URL's to get the information.

You can convert that into a csv file and download it to your desktop

Finally, I refer to it as libot. Hence the name at the end of the repo.
