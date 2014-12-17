jQuery.Simple-Event-Calendar
================

jQuery.Simple-Event-Calendar make it easier for you to create an calendar. Check out the demo!

###Install
```html
bower install simpleeventcalendar
```

###Setup
```html
<!-- You'll need jquery -->
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<!-- and you'll need to include equalheight -->
<script src="simplecalendar.js"></script>

<!-- and you'll need to include style.css -->
<script src="style.css"></script>

<!-- and all you'll need to do is add some divs for event-->
<div class="day-event" date-month="12" date-day="16">
<a href="#" class="close fontawesome-remove"></a>
<h2 class="title">Lorem ipsum 3</h2>
<span class="date">2014-12-16</span>
<p>Lorem Ipsum är en utfyllnadstext från tryck- och förlagsindustrin. Lorem ipsum har varit standard ända sedan 1500-talet, när en okänd boksättare tog att antal bokstäver och blandade dem för att göra ett provexemplar av en bok.</p>
<button class="read-more">Read more</button>
</div>
```

###Basic
![alt tag](http://oi59.tinypic.com/2vkivxs.jpg)
###Personal list
![alt tag](http://oi62.tinypic.com/dmbq86.jpg)

###Updates
* Personal list with print function
* Auto add '.event' class to all days that has an event 
* Uncheck calender '.day-event' checkbox when removing event from personal list

###Todo
* List days automatically based on month
* Datepicker

