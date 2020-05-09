# To Do List Webpage
## Made by Jessie Murphey
 ![ToDo Image](http://ec2-3-83-96-252.compute-1.amazonaws.com/Jcmq6bWebPage/to_do_pic.png)
### [Link to website](http://ec2-3-83-96-252.compute-1.amazonaws.com/Jcmq6bWebPage/Jcmq6bToDoListS20.html)

 
- The purpose of this application is to help keep track of projects, homework, or other assignments that you need to get done.
- I created this using HTML5, CSS, and Javascript (and Jquery).
- Below is a jquery function I wrote to change the page theme between light and dark mode.
```javascript
//Function to change color mode
                let mode = "light";
                $("#modeButton").click(function(){
                    console.log(mode)
                    if(mode=="light"){
                         $('link[href="lightmode.css"]').attr('href', 'darkmode.css');
                        $("#modeButton").text("Dark Mode");
                        mode = "dark";
                    }else{
                        $('link[href="darkmode.css"]').attr('href', 'lightmode.css');
                        $("#modeButton").text("Light Mode");
                        mode = "light";
                    }
             '''
