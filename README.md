Create an application that interacts with local data storage (for example, with localStorage, but not required) is required. The application must load into the repository 10,000,000 strings of length 100, randomly generated from letters in random case.

The application must have an input line with which the user will search the repository. Processing data from the user should be implemented as follows:
The user enters a string into the form.
[Clicks on the search button].
The application returns the number of lines that start the same as the user's query.

For example, if the user entered the string "A", and the storage contained the strings "AAA", "A", "BA", then it should display the number 2 to the user.

What is the asymptotic behavior of your search algorithm? Can you make it faster linear? Explain.

User input should be implemented using Vuex, in other cases, you can use any other libraries and technologies. It will be cool if you use a framework for styles (Vuetify, Element UI, ...) with custom styles. In response, send an archive with the code or a link to the repository.
