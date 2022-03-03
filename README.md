# coffeeprofessor
A simple static website created during the Bootstrap module of my 5-month certified web developer bootcamp. 
The instructor gave us the copy/text and this image https://bit.ly/3IIwl8O and we were told to reproduce it from scratch as a static website (i.e., no code provided). 
It's just basic HTML and CSS, but I really wanted to get the colors right as well as positioning of the elements. I modified how the hours are displayed, and
added a hover property for the navbar buttons just for fun (as you can see they don't link to anything).
Since this is a static website and Heroku doesn't host static websites, just apps, a little workaround was employed to deploy the project to Heroku: before logging into Heroku,
I added an index.php file and a single line of code in the project files in order to redirect the static index.html file, which fooled Heroku into thinking it was a PHP app. 
Here's the final product: https://coffeeprofessor.herokuapp.com/index.html
