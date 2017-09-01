### DateTime Drill
***

#### Objective

This drill proposed you are working for a company that opened two new branches, one in New York and another in London. The company wants a script that will check the current time of the headquarters in Portland, OR and use this time to determine whether the other two branches are open or closed based on the hours of operation in their respective timezones.

#### Steps Taken

To even get started with writing this script I had to look up all the documentation on the DateTime class and functions in Python. Once I had a good understanding of them I was able to see they had some limitations that would make implementation more difficult than need be, and some searching found that the pytz Python library would be of help, so I also read up on the pytz documentation. With both libraries understood I was finally able to write out the script.

#### The Result

A working script that prints out to the shell the current local times for each branch and whether the NY and London branches are open. From this exercise I learned how complicated it can be to work with timestamps. If you stick to dealing with timestamps in UTC/Unix time it is much more simple. However when you start dealing with local times and timezones things get tricky and you have to make sure that timezone information is being preserved with the timestamp data when you want to convert timestamps between local times. I also saw how important it is to thoroughly read up on library documentation when using unfamiliar libraries. Without fully understanding the documentation you risk data being mishandled or programs behaving unexpectedly.

[Return to portfolio](https://github.com/zfregin/portfolio)
