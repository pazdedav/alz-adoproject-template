1. On the source Azure DevOps, browse to the root of the wiki page board -> wiki and click clone wiki

![Clone_Wiki](https://user-images.githubusercontent.com/19664186/118852638-3dd65900-b8d3-11eb-8127-d05910fe3046.png)

2. Copy the git url and the credentials

![clone repo](https://user-images.githubusercontent.com/19664186/118852827-6a8a7080-b8d3-11eb-8796-48a017fcbe5f.png)

3. On the target Azure DevOps, browse to Repos -> Files
Choose import a repository

![import_repo](https://user-images.githubusercontent.com/19664186/118852902-7fff9a80-b8d3-11eb-83c2-724d34b0c476.png)

4. In the pop up window, type in the Clone URL, tick Requires authentication then the username and password.
Import a git repo
![import_git](https://user-images.githubusercontent.com/19664186/118852938-8857d580-b8d3-11eb-84d1-25f7946a2fc8.png)

5. This takes a 'short' amount of time depending on how large your wiki is. For my wiki of 200 text-heavy pages, it took about 1 second. but Azure DevOps will send you an email confirming when it is complete.
Note: this process works migrating from one Azure DevOps organisation to another.
