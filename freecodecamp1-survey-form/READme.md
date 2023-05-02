# freecodecamp1-survey-page


## __OBJECTIVE__

 Build an app that is functionally similar to __https://survey-form.freecodecamp.rocks__


---

## __PROJECT OUTPUT__

<p class="codepen" data-height="300" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="PoyJjom" data-preview="true" data-user="devinci-it" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/devinci-it/pen/PoyJjom">
      freeCodeCamp-HTML-Forms</a> by .vince (<a href="https://codepen.io/devinci-it">@devinci-it</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"> </script>

---
![Alt text](fcc-1.png)


---

## __PROCEDURE__

---
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
```


1. You should have a page title in an h1 element with an __`id`__ of title
```html
<title id="title">
     Support Ticket 
</title>
``` 
2. You should have a short explanation in a p element with an __`id`__ of description.
```html
<p id="description"> 
    Fill out this form and one of our representative will contact you in 2-3 business days.
</p>
```

3. You should have a form element with an id of survey-form. Inside the form element, you are required to enter your name in an __`input`__ field that has an __`id`__ of _`name`_ and a __`type`__ of _`text`_.
```html
<form id="survey-form" action="https://survey-form.freecodecamp.rocks" method="post">

<div class="form-control">
            <label class="label" for="name" id="name-label" required="">
                NAME
            </label>
<input required="" type="text" class="textinput" id="name" placeholder="Enter your name">

</div>
```


3. Inside the form element, you are required to enter your email in an __`input`__ field that has an __`id`__ of email

```html

 <label class="label" for="email" id="email-label"> EMAIL ADDRESS </label>            

<input required="" class="textinput" type="email" id="email" placeholder="Enter a valid email.">
```

4. If you enter an email that is not formatted correctly, you will see an HTML5 validation error. Inside the form, you can enter a number in an __`input`__ field that has an __`id`__ of number.

``` html
<label class='label' id= "number-label" name="number-label" > SEVERITY LEVEL 
    <p class="power"> †</p>
             <input class="sev" type="number" min=1 max=3 id="number" placeholder="1"/> 
</label>
```

- If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error.


7. For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: __`id`__= "_name-label_", __`id`__ = _"email-label"_, and __`id`__="_number-label_".

```html
<label class='label' id= "number-label" name="number-label" > SEVERITY LEVEL 
    <p class="power"> †</p>
    <input class="sev" type="number" min=1 max=3 id="number" placeholder="1"/> 
            </label>
            
```


- _For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field._


9. Inside the form element, you should have a select dropdown element with an __`id`__ of dropdown and at least two options to choose from

```html
<label class="label" for="role" id="label-role">
                CONTACT PREFERENCE

            <!-- Dropdown options -->

            <select name="role" class="dropdown" id="dropdown">
                <option value="student">Call/Text</option>
                <option value="intern">Email</option>
                <option value="professional"> No Prefence.</option>
                <option value="other">Do not contact me.</option>
            </select> </label>
        

```

10. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute.

```html
        <label for="newsletter">  <sup class="power"> †</sup> Would you like to receive SMS text updates this support ticket? <em>*</em><br> </label>       
        
        <label>   
        <input type="radio" value="sub-1" name="subscribe" checked=""> Yes </label>
        <input class="radio" type="radio" name="subscribe" id="subscribe-0" value="sub-0"> No </label>

````

11. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute.
```html

<label for="inp-1" class="label">

        <input  type="checkbox" 
                id= "newsletter" 
                name="opt-in" 
                value="opt-in"/> 
              
            
            <p class="power"> † 
            I would like to receive emails from Synapse Networking Solutions  and its affiliates about promotions, products, industry resources, events and updates. <p>
            <br>
</label>

````
12. Inside the form element, you are presented with a textarea for additional comments
Inside the form element, you are presented with a button with __`id`__ of submit to submit all the inputs.

```html
<label class="label" for="details"> HOW CAN I HELP YOU?
</label>
        <textarea id="support-details" class="textarea" name="details" placeholder="Please provide relevant info that can help  resolve this issue."> </textarea>    
````


<h6>HAPPY CODING!</h6>   

