## Day 1
Create the repistory (MIT)  
Change the source to master and the theme to the best looking one.  
Add the link to the website portion on edit (upper middle right)  
???  
Github should basically be set-up  

???  
Install a lot of things  

## Day 2  
*Learn about git*  
<ol> <li>Version control system</li>  
<li> history of changes to your files</li>  
<li>View, apply, and remove those changes</li>  
<li<Keep all your project files in one repository</li></ol>  

Save file = commit.  
-name = -m 'message'  

Creates snapshots on the timeline of the project.  
Git keeps track of what the file looked like at different points in time.  

Each commit has a label that points to it.  
HEAD = label for "you are here" (read as most recent)  
You can assign messages to commits.  
Messages are like writing a caption for your snapshot.  

Git is the versioning system/command line tool, github is a hosting service, task managing "cloud" for projects  

_**git + github = awesome**_  

*Github*  
Allows you to share code with others, and an online place to store your code.  
Can use git to help manage team's work - can allow you to keep changes separate before it's added in  

Repository - collections of files that you've told git to pay attention to  
Generally, one project = one repository  

_**how to add a clone to another repository**_ (actions in terminal)  
cd desktop  
ls - shows what the list on your desktop is  
ls -a shows the hidden files (things with .infront of them)  
git clone + link  

cd + new name  
ls (to see what's inside)  


*use code . to open VS*  

__*Git status - use a lot*__ - Let's you know if there are any changes that need to be made since your last commit  
git remote -v - Lets you know what is being fetched or pushed  
git add <file> - to update what wil be committed  
git checkout -- <file> - to discard changes in working directory  
git reset HEAD <file> - to unstage (revert back)  
git commit -m '<add or update file markdown examples>'   
  git add <file name>  
  git update 'what you did here'  
git push - to publish local commit  
git commit -m "your message goes here"  
git push origin master -   

*git flow*  
A-C-P  

__*HTML*__ - hyper text markup language  
This is what you use to structure your webpage.  
Semantic elements are descriptors that tell you where to put things.  
- < article> < /article>  
- < div> < /div>  

< Head>< /Head> Title, metadata, link style, js  

### example of html page  
<*!DOCTYPE html>  
<*html>  
  <*head>  
    <*title>htmldemo</*title>\
  <*/head>\
  <*body>\
    <*header>\
      <*h1><*/h1>\
      <*nav>\
        <*ul>\
          <*li><*/li>\
          <*li><*/li>\
        <*/ul>\
      <*/nav>\
    <*/header>\
    <*main>\
      <*img src="yourimagelinkhere">\
      <*/img>\
    <*/main>\
      <*h2><*/h2>\
      <*p><*/p>\
    <*footer>\
      <*p>&copy<*/p>\
    <*/footer>\
  <*/body>\
<*/html>\

## Day 3

__*CSS*__  - cascading style sheets
(#thing) {  
    write like this;  
}  

__ margin _  
|-----------|  
|-content--|<-border  
|-----------|  
_ padding _  

(#) is an ID   
- Only ever use once for html  

. is a class  
- you can group two classes that are doing the same thing   

<*a> -anchor tag  
- Anything you've clicked on is through an anchor tag  
- Assists with links and other hyperlink activities  

w3schools.com / mdn - help with things you're particularly bad at 

With padding you can have 4 values: follows top right bottom left. The first value will apply to the top of the element. The second value will apply to the right, etc etc.  

CSS is the ability to realize that there is an invisible block around each html element. Which allows you to create rules that control the way that each indiviual box and their contents are presented.  

CSS elements have selectors and declarations. A selector indicates what part of the html code are going to be being applied, and the delcaration indicates how the elements referred to in the selector should be styled.  

Inside the declaration (or the curly brackets: {}) there is a property and value. The property indicates the aspects of the element you want to change and the value specifies the settles you want to use for the chosen properties.  

<*link>  
- Does not need closing tag (empty element)  
- Tells the browser where to find the css file used to style the page  

<*href>  
- Specifies the path to the CSS file  

<*type>  
- Attribute specifies the type of document being linked to  

<*rel>  
- Specifies the relationship between the HTML page and the file it is linked to.  

CSS reads top to bottom, with bottom taking precedence. If you !important in front of your tag it will take precedence. CSS also values specificity over everything. More specific selectors are to be valued higher.  

__*Color*__  - google color selector, coolors.co, color.adobe.com/create/color-wheel,  
*RGB values* - rgb(100,100,100)  
*Hex codes* - #ee3ee80  
*Color names* - DarkCyan  
*Hue* - literally changes the color entirely  
*Saturation* - Refers to the amount of gray in a color. At max sat there is no gray, at min sat there is almost all gray.  
*Brightness (see also value)* - Refers to the amount of black in a color. At max brightness there is no black, at minimum brightness there is almost no non-black color (read dark).  

__*Contrast*__  
*Low contrast* - Text is harder to read with lower contrast. A lack of contrast is particularly a problem with color blindness and seeing impairments. Poor monitors or poorly lit rooms also suffer.  

*High contrast* - Text is easier to read. If there is too much contrast it makes it difficult to read. Too much popping.  

*Medium contrast* - Longer spans of text need medium contrast. Makes it easier on the eyes. You can reduce contrast by using dark gray text on a white background or off-white text on a black background.   

__*Opacity*__  
*specific to CSS3*  
Basically in rgba you can add a #.# value at the end which references how opaque you'd like something to be. 1.0 being solid and reducing in percentages of opacity from there. *ex. -* .5 is 50% (half opacity).    

__*HSL and HSLA*__  
*specific to CSS3*  
body {  
  background-color: #c8c8c8;  
  background-color: hsl(0,0%,78%);}  
p {  
  background-color: #fffff;  
  background-color: hsla(0,100%,100%,0.5);  
}  
HSL color property has been introduced into CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parenthesis for: Hue, saturation, and lightness.  
HSLA olor property allows you to specify color properties using hue, saturation, and lightness as above and adds a fourth value which represents transparency. The A stands for Alpha. This number is expressed between 0 and 1.0. .5 represents transparency, etc, etc. Is basically opacity.  

__*Seperation of concerns*__  
The idea that you should split HTML, JS, CSS files due to neatness. CSS, HTML and JS files can get very long and you would not want them to merge together. It makes it more editible as well.   

w3schools.com boz sizing border box  
clear: both; - helps with floats to line up pages  


__*Javascript*__    
Data Types-  
- Number - Numerical data - 3  
- String - Textual data - ' text '  
- Boolean - True or False  
- Null - Says this does not exist  
- Undefined - Delcared a variable with no value from that variable  
- Symbol  
- Valve  
- NaN - Not a number  

__Things you can put inside your app.js__  
console.log -  
<*script src="jslocation"></*script> - include this tag after the footer to prevent issues  


var is how you define things.  
var = variable  
We are learning vanilla javascript. We will learn ES6 (?)  
= is an assignment operator.  

prompt -  
alert -  
if -   
else -  


## Day4  
*Function*- Named piece of code  
*Declaration*-  
*Call*-  
*Parameter*-  
*Arguments*-  
*Return Value*-  
*Script*- Series of instructions given by the user.  
*Syntax*- Colons, semicolons, periods, etc. Things to end or include inside the script.  
*Expression*-  
*Operator*-  
*Refractoring*-  

  
function functionName(){  
    //code  
}  
___   
var nameOfThing = function {  
    //code  
}  
___  
function functionName (parameters){  
  //code  
}  

functionName(Argument);  
___  

