## Seven Seas Module Two Week One Review

Seven seas...<br>
Seven restful routes...<br>
Seven days of studying web frameworks...<br>
And now it's time to review with a Sinatra to Rails challenge!

## What You Have Now

You've been provided with the Sinatra Seven Seas application. It has full CRUD actions for the resource 'sea' and an MVC framework. Take a few minutes to look through the app and familiarize yourself with the code. Then, fire up shotgun in terminal and see how it looks!

Notice all the fancy styling? That comes from a popular front-end styling framework called <a href="http://getbootstrap.com/">Bootstrap</a>. If you look in <code>'app/views/layout.erb'</code>, you'll see the Bootstrap styling linked. All of the css classes used in the application come from Bootstrap.

Don't worry if the styling seems a bit magical right now; your focus will be mainly on the MVC structure.

## Goal
Your job is to recreate the Seven Seas application in Rails. To a user, the Sinatra and Rails apps should be indistinguishable.

Feel free to copy/paste where applicable from Sinatra to Rails; you won't see that advice often in a Learn lab, but the goal of this lesson is to become aware of the similarities and differences between Rails and Sinatra applications.

## Caveats and Tips

 - In order to give your Rails Seven Seas Bootstrap styling, simply copy the stylesheet line from the Sinatra <code>'app/views/layout.erb'</code> head, and move it to <code>'Rails-Seven-Seas/app/views/layouts/application.html.erb'</code>.
 - We've built Rails new and edit forms for you, since Rails forms have some built-in security features with conventions we have to follow. Take a look at the code, still, and try to relate it to the Sinatra forms.
 - Use <code>rails s</code> to start a server and <code>rails c</code> to enter a console. Confirm your assumptions early and often!

## Instructions
 - Where do we start with any Sinatra or Rails application? <code>bundle install</code>, of course!
 - Next, you'll need a database populated with the seven lovely seas from the Sinatra application. Think about what code can be recycled from the Sinatra app.
 - In Rails, routes are separated from controllers. Because Rails is awesome, the routes.rb file contains a link to the Rails documentation for routes. Since you're building full CRUD for a sea, add all seven RESTful routes to this file.
 - Now, your job is to work out the MVC--Model, View, Controller--part of this app. When making your model, controller, and views, remember that naming conventions are very important in Rails!

## Stuck?
  - Run <code>rails c</code> to check and update your data
  - Run <code>rails s</code> and test your code in the browser
  - Use byebug (it's just like pry) to check your controller actions
  - Check the (excellent) <a href="http://guides.rubyonrails.org/">Rails documentation</a> or Google the error
