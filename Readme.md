# Begginer-To-Intermediate-Js 

JavaScript is the world's most popular programming language.

JavaScript is the programming language of the Web and easy to learn.

 #### Commonly Asked Questions
> 
- How do I get JavaScript?
- Where can i download javascript?
- Is Javascript free?

**You don't have to get or download JavaScript.**
**JavaScript is already running in your browser on your computer, on your tablet, and on your smart-phone.**
**JavaScript is free to use for everyone.**

#### The Script Tag

In HTML, JavaScript code is inserted between <script> and </script> tags.

Example

```
<script>
    document.getElementById("demo").innerHTML = "My First JavaScript";
</script>    
```
we can add javascript in html with the above tag and there is also another method

#### External Scripts

javascript files have the file extension **.js**

To use an external script, put the name of the script file in the src (source) attribute of a **<script>** tag:

```
 <script src="myScript.js"></script> 
```

> **External scripts cannot contain <script> tags.**

#### External JavaScript Advantages

Placing scripts in external files has some advantages:

- It separates HTML and code
- It makes HTML and JavaScript easier to read and maintain
- Cached JavaScript files can speed up page loads

To add several script files to one page  - use several script tags:

```
<script src="myScript1.js"></script>
<script src="myScript2.js"></script> 
```

#### External References

An external script can be referenced in 3 different ways:

- With a full URL (a full web address)
- With a file path (like /js/)
- Without any path

This example uses a **full URL** to link to myScript.js:
```
 <script src="https://www.w3schools.com/js/myScript.js"></script> 
``` 

This example uses a file path to link to myScript.js:
```
 <script src="/js/myScript.js"></script> 
```

This example uses no path to link to myScript.js:
```
 <script src="myScript.js"></script> 
```


