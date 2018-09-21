# Github-Profile-Search
A quick and simple GitHub Profile Search app written in Angular.


## Getting started
1.  Make sure you have node  and npm installed
1.  Fork this repository 
1.  If you do not have latest angular cli installed, run `npm install -g @angular/cli`
2.	Run `npm install`
3.	Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


# This app fetches data and displays a user profile list
1.	Github user api: `https://api.github.com/search/users?q=eric` takes a search string to search users in github. The search string could be passed as parameter q
4.	The main search component querires the above mentioned api
5.	Using the search results, it displays the total number of github users
6.  It displays the first 10 users in the results
