# jQInstaPics - Showcase your Instagram photos using jQuery #


## About ##

jQInstaPics is a simple jQuery plugin that enables you to display your latest Instagram photos on your website or blog.

##Usage ##

### HTML: ###

    <ul id="instagram"></ul>

Create an empty unordered list and give it an ID of choice.

### CSS: ###

    #instagram {
    	margin:0;
    	padding:0;
    	overflow:hidden;
    }
    
    #instagram li {
    	list-style:none;
    	float:left;
    	margin:0 20px 20px 0;
    }

These are the most basic styles necessary to create a horizontal list of images.

### Scripts/Initialisation: ###

    <script src="http//code.jquery.com/jquery-1.7.1.min.js"></script>
    <script src="jqinstapics.js"></script>
    
    <script>
    $("#instagram").jqinstapics({
      "user_id": "Your User ID",
      "access_token": "Your Access Token",
      "count": 5
    });
    </script>

The Instagram API requires 2 pieces of information to display photos from a user feed. These are the User ID and an Access Token. How do you get these, you say? Don't worry, I've created a nifty tool that will allow you to obtain both (see website docs).


## License ##

Copyright (c) 2012 Crafted Pixelz

Licensed under the MIT license