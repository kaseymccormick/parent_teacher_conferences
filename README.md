#Conference Planner#
**the problem** Parent teacher conferences for each grade level and for each teacher are planned by a peice of paper. This makes it hard to keep track of the updates for parents and teachers.

**the solution** An online signup that updates in real time and can have email reminder interaction
_technologies to use_ Ruby, Rails, Sorcery, Javascript, Ajax, -materalize- may be better to go simpler with github framework
**concerns for users**

_parents_
* see what times for each child
* sign up at a time that best suits them
* see what time signed up for
* reminded what time signed up for
* change time signed up for

_Teachers_
* need to be able to see which students at what times
* be able to block out times for lunch
* sign up parents who havent on an availabile slot




###possibly helpfull links ###
http://minmcknight.github.io/modeling/erd/2015/02/08/first.html
https://github.com/atd/rails-scheduler
https://rubygems.org/gems/rails-scheduler
https://github.com/topfunky/calendar_helper

**login**
https://github.com/NoamB/sorcery
http://railscasts.com/episodes/283-authentication-with-sorcery
https://github.com/NoamB/sorcery/wiki/Simple-Password-Authentication

*divise*
http://www.gotealeaf.com/blog/how-to-use-devise-in-rails-for-authentication

**testing**
https://robots.thoughtbot.com/how-we-test-rails-applications

**rails reading**
http://railsapps.github.io/what-is-ruby-rails.html

**materalize**
http://materializecss.com/getting-started.html

**features to have**
Administrators that can see all teachers conference schedules and be able to edit all teachers
Ability to print
email parents as a reminder
have the teachers be able to edit the conference times
parents can sign up via online or via peice of paper to teacher teacher then adds this time
always 15 minute increments
schedule doesn't lock 
when slot is taken just say spot taken
teacher should be able to see what student that slot is
administrators should be able to see what students are in slots

all administrators and teachers will have to log in for access
parents can have a login but NOT REQUIRED

**roles at play**

Administrators _can be a teacher_ _can be a Parent_

Teachers _can be a Parent_

Parents