# Create HTML page using Google App Scritps
Learn how you can write your first google app script to create a webpage or web based online app. You can also make chrome extensions and add-ons using scripts. Write some script to deploy them as webpage so that everyone can use it online.

![Google Script - Sramad GArdezi](https://i.imgur.com/F59FaO1.png "Google App Scripts")

# Script that fetch html page as webpage

```ruby
// Written by Sarmad Gardezi - sarmadgardezi.com
function doGet() {
  return HtmlService.createTemplateFromFile('index').evaluate();
  
  }
```

[Read Complete Article](http://thedevelopers.pk/?p=280)
