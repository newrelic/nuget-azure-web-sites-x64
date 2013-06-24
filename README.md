nuget-azure-web-sites
=====================
The nuget package for x64 apps (of type "Web Site") running on Windows Azure.


Contribute
===========================


Setting up your local environment to contribute
---------------------------------
1. Open visual studio
2. Tools menu >> Library Package Manager >> Package manager settings
3. Under the Package Manager, click on Package sources
4. Create a source named "Local" and set the directory to where you cloned the repository (something like "c:\code\nuget-azure-web-sites")
5. Click Add then "OK"

Using the package locally
-----------------------------
1.  To use it you can open up your web app and choose >> tools >> Library Package Manager >> Package manager console
2.  In the console make sure that the source drop down is set to local
3.  Then type in "Install-Package NewRelic.Azure.WebSites.x64"
4.  Hit enter

Pull requests
--------------------
1. [Fork the repository](https://help.github.com/articles/fork-a-repo)
2. Add awesome code or fix an [issue](https://github.com/newrelic/nuget-azure-web-sites-x64/issues) with awesome code
3. [Submit a pull request](https://github.com/newrelic/nuget-azure-web-sites-x64/pulls)