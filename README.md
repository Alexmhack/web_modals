
# web_modals
enabling modals in website

# Project Objective
Every website has cookies system, and website has to show an notification about the cookies policy
that website uses for its users so for that, website shows the notification about the cookies
policy once on any page that tha user has visited and not every time the page reloads and also
not on a certain page but on each page that website has but only once.

We can accomplish this objective using the lessons we learned in the brandflow about the page url,
we can set the starting of the page url and then show our new users the cookie policy once on each
url of our website.

# Creating cookie modal
Goto sidenav > modals > lists. Click on add button and name our modal Cookie modal and select Show
only once, this is obvious because we want to show our modal only once. Paste the code from
cookie_info.html and paste in the code section of our modal, save the modal.

# Creating trigger
Once our modal is created we need a condition for triggering the modal, the condition is simply 
the new user condition which has page url for localhost, save and publish changes.

# Testing
Refresh the browser and you will see the cookie button and info, refresh the browser again, this 
time you will not see the cookie bar.

# Creating scroll condition
If a user visites your website and starts reading article, then we would want to suggest him more 
articles that are related to the current one but only if the user has shown interest in that 
current article, this thing can be achieved with scroll condition

If the user has scrolled more than 60% of the article than we will show him more articles.

Goto automation > condition and then create a new rule named Scroll 60% condition and select type 
= Scroll % equals 60 and then save.

# Creating related article modal
Goto modals > lists. Create new modal named Related article modal and paste the related_
article.html code in the code section and save it > add trigger and select condition to scroll 
60% > save > publish changes.

# Creating time delay condition
Many users just scroll down the page very quickly finding the thing they want in the article and
not read the whole article for that we can set the time spent by the user on the website.

We create the Delay time condition from automation > condition > new rule > Delay 20 condition > 
type: Delay time = 20 > "Do something if user spents 20 seconds on the page".

Add the trigger to the modal Delay 20 and save it.