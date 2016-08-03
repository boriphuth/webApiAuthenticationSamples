Web Api Authentication Samples
===================


When implementing authentication in web api, I found that even though there are many examples of how to do things on the web, there isn´t a comprehensive full working sample for the different authentication mechanisms.

Therefore, I decided to create this project to showcase the authentication mechanisms in web api and made it so it´s easy to reuse the code for your own projects.


I´ve added a swagger page to showcase all of the Api´s methods, just start the site and navigate to [http://localhost:[port]/swagger](http://localhost:%5Bport%5D/swagger)

Provided as part of the solution are:

 - **BasicAuthenticationFilterAttribute**: Authorization filter that can be added to Controllers or Actions to authenticate using [Basic Authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
 - **DigestAuthenticationFilterAttribute**: Authorization filter that can be added to Controllers or Actions to authenticate using [Digest Authentication](https://en.wikipedia.org/wiki/Digest_access_authentication)

