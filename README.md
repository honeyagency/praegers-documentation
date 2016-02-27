## Dr. Praeger's Documentation

Welcome to wordpress! This should be pretty basic to understand, but there will be screenshots and images included to help you find your way throughout the site. 

You should have a Wordpress login. If so, go ahead and use it at the admin domain:
* http://www.drpraegers.com/wp-admin

You should see something like this: 
![Dashboard](http://i.imgur.com/cXCByOs.png)

This is the wordpress dashboard. Think of it as your backend “homepage” — you can get to everything from here, and it’s where wordpress will automatically take you when you login. 

So, we’re going to walk through a few things to get you up-to-speed on how the Dr. Praeger’s website works, once we go through them you’l be a *wordpress expert.* Very fancy. 

Lets get started.

### Editing a Product

**Overview**

* The URL for a product page is going to look something like this: drpraegers.com/our-food/california-veggie-burgers

* And a product page will look something like this:
	* ![Product Example](http://i.imgur.com/Nr4XcgI.jpg)

Product pages are a detailed product listing with various pieces of product meta-data. All of that information is available to you on the backend of the website. The easiest way to find the correct backend page is (once you’re already logged in):

1. Navigate to a product page
2. Click `Edit Product` on the top of your page. 
3. You’re In!

![Logging in](http://i.imgur.com/KW6czKe.gif)

Once you’re in, you can make edits and try them out without changing them on the actual website by clicking on “Preview Changes” in the top-right corner of the page. Once you’re ready to make changes, you only need to click the blue “Update” button.

Here’s a list of the fields (places to put data like Titles, Images, names, etc) available with some small explanations.

**Product Name Section**
This co-relates to the highlighted area in this image:
![Product Name](http://i.imgur.com/XANdYwn.png)
* Product Name Large (relates to `California` in the above image)
* Product Name Small (relates to `Veggie Burgers` in the above image)

**Content Section**
This  co-relates to the highlighted area in this image:
![Content Section](http://i.imgur.com/cPCLDAD.png)
* This is a simple WYSIWYG (think of these like a microsoft word editor) field that contains all of the information displayed highlighted in this image.

**Our Products Section**

* Hover Blurb
	* This is the blurb that displays on the “Our Food” page when you hover over the product you are currently editing. The text on the front-end is highlighted in this image: [Hover Blurb](http://i.imgur.com/LiILGzs.png)
* Ingredients
	* This is a plain text area that displays the product ingredients on the product page, highlighted here: [Ingredients](http://i.imgur.com/uwUa4OK.png)
* Certified Logos
	* There are a few checkboxes here for you to select. It will display image that you will [later learn how to upload](#certified-logos)
* Product Box Image
	* This is a simple image upload field. You generally won’t need to worry about changing dimensions for images (they will be provided at an appropriate resolution) and this is where you will upload them.
* Cooking Instructions Text
	* This is a plain text field for cooking instructions.
	* The words “COOKING INSTRUCTIONS” will automatically be added above your text on the page and should be omitted from this field. 
* Cooking Instruction Sections
The way this field works is by using what we call “repeaters.” Essentially, we format a few fields and—instead of limiting the fields or having too many fields—we give you the ability to “repeat” the field template. When you click `Add Instruction Section` it will add another instruction column. The added benefit is that you can drag-and-drop to re-organize all of the sections.
	* Cooking instruction Icon
		* Simple square image, uses an image uploader
	* Cooking instruction section title
		* Title that displays below the icon.
	* Preferred method
		* There should only be one checkbox checked here. This is how you highlight which method you “prefer”
	* Cooking instruction text
		* Simple text field to give cooking instructions. This ought to reflect what’s on the box.
* Nutrition Facts
	* This is a simple image uploader field.
* Secondary Product Image
	* Dimensions:  `1200 x 800`
* Has Related Recipes
	* This is a “yes” or “no” button. When the option is clicked on “yes” it will display the following fields:
	* Related Recipe
		* This has drop-downs where you can choose related recipes.
* Main Product category
	* This is a drop-down that will update the category that a product lives on on the “our food” page here: [Veggie Burgers Category](http://i.imgur.com/0RLPzWy.png)
* Product Category Checkboxes
	* These will make the product available on the checkboxes below the categories mentioned above.

### Editing a Recipe 
Using the method you learned with the “Editing a Product” section of this documentation, navigate to edit a recipe. If you forgot, [Check out how we did that here](#editing-a-product)

Here’s a list of the fields available with some small explanations.

**Header Content**
* Title
	* This is the title at the top of the page (on the backend, [you can see it here](http://i.imgur.com/Wlg4Kav.png)) 
* Blurb
	* This lives in the content editor just below the title. You can [see it on the front-end here.](http://i.imgur.com/AsG9dPv.png)

**Recipes Section**
* Recipe Category
	* This is a set of checkboxes that allows for sorting on the `/recipes/` page. It’s what controls the [toggles you see here](http://i.imgur.com/7HME3Sy.png)
* Ingredients List
	* This lives in a WYSIWYG. Use it to make a bulleted list of ingredients.
* Directions List
	* This also lives in a WYSIWYG. Use it to make a numbered list for directions.
* Additional Directions Text
	* This is an optional field, use it to add some extra directions you deem necessary. [Here’s an image of how it looks. ](http://i.imgur.com/VmXEO6N.png)
* Byline 
	* This text is also optional and lives just below the ingredients list. [Here’s an image of how it will look](http://i.imgur.com/ZR1OaV0.png)


### Updating Site Information (footer info, etc) 
This is where a lot of global information lives. If you’re ever looking to update something and can’t figure out where the field is, this is *probably* your safest place to check. To get there, go to your Wordpress dashboard (we found this in the intro) and look for an **gear** icon that has the words “theme settings” next to it. [Here’s a gif of what that process looks like](http://i.imgur.com/OsAYVGh.gif)

I’ll go over the sections one-by-one below.
 
##### Newsletter
This section is the place to edit  the content living within the popup you see when you first navigate to a page.

**Pro Tip:** You’re probably visiting the site *so* frequently that your browser no longer displays the pop-up. This is a good thing, we *really* don’t want to bother people on the internet, they can be touchy. But when you’re trying to make content updates, it can be aggravating when things don’t update. Clear your cache, all your problems will be solved.

Here’s how to clear your cache in:
* [Chrome](https://support.google.com/chrome/answer/95582?hl=en)
* [Safari](https://kb.wisc.edu/page.php?id=45060)
* [Internet Explorer](https://kb.wisc.edu/page.php?id=15141)
* [Firefox](https://support.mozilla.org/en-US/kb/how-clear-firefox-cache)

**Newsletter**
* Newsletter Heading
	* Text field * (Image Example)[http://i.imgur.com/iUEiNuf.png]
* Newsletter Content
	* Text Field * (Image Example)[http://i.imgur.com/dxYxWyw.png]


##### Contact Details
These are pretty straightforward text fields and will be used in the footer
* Address
	* Address used in Footer and contact page.
* Main Phone
* Customer Service Phone
* Main Contact Email

##### Copyright Text
These are also pretty straightforward text boxes that are used in the footer 
* Copyright Text
* Terms of Conditions Link
* Privacy Policy Link

##### Our Food & Recipe Archive Pages
This option is used to edit content on a few top-level pages.

* Our Food Title
	* This is the title you see when you navigate to our food. (Image Example)[http://i.imgur.com/keomLvP.png]
* Our Food Sub Title
	* This subtitle displays directly below the title in the above field.
* Recipe Title
	* This is the title that displays on the “recipes” page (Image Example)[http://i.imgur.com/32ts9s0.png]

##### Certified Logos
We mentioned certified logos earlier. There’s also a “repeater” section that we mentioned earlier as well. When you check `gluten free` while editing a product page, the image that displays on the front-end ((Image Example))[http://i.imgur.com/2YOBw38.png] is dictated here.

* Name
	* When we display images by themselves on the web, we need to make sure that there is a text field embedded in the image that will help people with screen-readers (an audio interface to assist the visually impaired) have a description of what is being displayed.
* Certified Logo
	* This is a simple image field.

### Editing the Home Page
Navigate to the homepage and click `Edit Page` [Like we did with products and recipes](#editing-a-product)

There are a few customizable tabs within the homepage, I’ll go through them one-by-one here.

##### Main Slider
This is the main slider displayed on the homepage. This uses the repeater field we’ve used a few times. The benefit of the repeater in this scenario is we can add sliders and re-organize them after-the-fact.
* Title
	* Centered text of the slider
* Image
	* Background image of the slider


##### Food Categories
This displays the food category slider on the homepage (image)[http://i.imgur.com/IoDJo5S.png] and utilizes a repeater field.

* Title
	* This is the title displayed in the image (in this example it’s “veggie burger”)
* Image
	* This is the image of the food.
* Content
	* This is a WYSIWYG field that contains all of the content. 
* Link
	* This is where you would add the link that is related to the food item in the slider.
* Link Text
	* Use this text field to edit what the link says. This gives more flexibility to make targeted calls to action for each food item. 

##### Kids
This is another repeater field and displays the “kids” section. ((image example))[http://i.imgur.com/CxL6uV2.png]

* Title (image)
	* This is the image title that displays on the left side of the above image.
* Content
	* This is the content block for this section.
* Link URL
	* Currently this URL directs to `/our-food/#kid-friendly`. It most likely won’t need to be changed.
* Link Text
	* This is the text field for the link.
* Image
	* This is the Image that displays on the right side of the “kids” section.

##### Values
This section displays just below the `kids` section [Image Example](http://i.imgur.com/mTEMfpD.png)
* Title
	* This is the title displayed in the section above
* Link URL
* Link Text
* Values Repeater
	* Value Item Link
		* The link that a user is directed to when they click on an icon or value title. 
	* Image
		* This is the round icon that displays above the value title.
	* Title
		* This is the value title. It is automatically styled.
	* Content
		* This is the centered text describing the value.

##### Recipes Call-To-Action
This section displays just below the `values` section [Image Example](http://i.imgur.com/QlNRM4F.png)

It contains the following fields
* Title
* Link Text
* Link URL
* Background Image
	
##### Timeline
This section displays just below the `recipes` section [Image Example](http://i.imgur.com/5nMad39.png). This section utilizes a repeater field, refer to the `Cooking Instruction Sections` piece in the first section of this document if you need a little more information of how these work.

Since this is a somewhat complex section to make a connection between backend and front-end, here is a marked-up example, go ahead and refer to it instead of text descriptions:
![Timeline Fields](http://i.imgur.com/iypue6G.png)

This section contains the following fields:
* Image
* Title
* Content
* Link
* Navigation Title
* Navigation Icon


### Conclusion
This should cover everything on the website. There are one or two pages not detailed here, but it should be very simple to infer the details of updating all of them based on how you made changes elsewhere.
