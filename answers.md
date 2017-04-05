### 1) Which of the following is the correct syntax for selecting all the div tags on the page:
**A.) $(div) (answer)**

B.) $(#div)

C.) $(.div)

D.) None are correct
### 2) What is selected by the following selector: $(".tag")
**A.) All tags with a class of "tag" (answer)**

B.) All tags with no class set

C.) The tag with an ID of "tag"

D.) None are correct
### 3) Which of the following jQuery statements will cause an alert() with the content of 'Clicked the abc button' when a button with the ID of 'abc' is double clicked?
A.) $("button#abc").click(function() { alert('Clicked the abc button'); });

B.) $("button").dblclick(function() { alert('Clicked the abc button'); });

C.) $("button:abc").dblclick(function() { alert('Clicked the abc button'); });

**D.) None of the above (answer)**
### 4) Which of the following jQuery statements will remove only the hover() event from an image tag that is contained in a div with an ID of 'content'?
A.) $(div#content image).unbind("hover");

**B.) $(div#content image).remove("hover"); (answer)**

C.) $(div#content image).bind("hover");

D.) None of the above
### 5) What is the best definition for event delegation in jQuery?
A.) Event delegation allows us to attach a single event listener, to multiple elements, that will fire for a selector.

B.) Event delegation allows us to attach multiple event listeners, to a parent element, that will fire for some descendants matching a selector, whether those descendants exist now or are added in the future.

**C.) Event delegation allows us to attach a single event listener, to a parent element, that will fire for all descendants matching a selector, whether those descendants exist now or are added in the future. (answer)**

D.) None are accurate definitions of event delegation
### 6) Which jQuery statement will cause each button clicked to become hidden?
A.) $("body").on("click", "hide", function() { $(button).hide(); });

B.) $("body").on("button", "click", function() { $(this).exec(); });

**C.) $("body").on("click", "button", function() { $(this).hide(); }); (answer)**

D.) None of the above.
### 7) Which of the following jQuery statements replaces the current contents of a div control with an ID of 'login' with a button with an ID of 'submit' with text of 'Login'?
A.) $("div#login").append('Login');

B.) $("div#login").add('Login');

C.) $("div#login").html('Login');

**D.) None of the above (answer)**
### 8) Which of the following jQuery statements adds a label control to the end of the content of a paragraph tag that has a class of 'message'?
A.) $("p,message").append('Update Successful!');

**B.) $("p.message").add('Update Successful!'); (answer)**

C.) $("p#message").html('Update Successful!');

D.) None of the above
### 9) Which jQuery statement sets the text of a button control to 'Save'?
A.) $("button").val("Save");

B.) $("button").txt("Save");

**C.) $("button").text("Save"); (answer)**

D.) None of the above
### 10) Which jQuery statement sets the selected value of a list control to the item with the value of 'college'?
**A.) $("list").val("college").change(); (answer)**

B.) $("list").text("college").change();

C.) $("select").val("college").change();

D.) $("select").text("college").change();

E.) None of the above
### 11) Which of the following jQuery statements will move a div with a class of 'content' to a div with ID of 'left'?
A.) $(".content").appendTo("#left");

**B.) $(".content").append("#left"); (answer)**

C.) $(".content").moveTo("#left");

D.) None of the above
### 12) Which of the following jQuery statements will move a label with ID of 'message' to the end of a paragraph with ID of 'content'.
A.) $("label#message").append("p#content");

B.) $("label#message").moveTo("p#content");

**C.) $("label#message").appendTo("p#content"); (answer)**

D.) None of the above
