# Participation: My First Webpage

## Goal

Apply some of the basic knowledge that we spoke of in class and make our first webpage.

## Instructions

Here we go. Time to make our first webpage! 

Now that we did our readings and have talked about some of the basics, it is time to practice and write our first webpage. We will keep it very simple. We just want to get something going and get our hands dirty, so to speak. 

Here is an example of what we will have by the end of this practice exercise.

![screen shot](screenshot.png)

First thing that we will need to do is open up our code editor of choice. For this course, I'll probably mostly be using either [VS Code](https://code.visualstudio.com/) or notepadd++. If you are following along with me for this exercise, then open up VS Code now.

When you open up VS code you should see this screen: 

![screen shot](screenshot.png)

Then right away you should save your file. I'm going to save mine as `my_first_webpage.html` 

![screen shot](screenshot.png)

You might notice the file extension. savedd as html. similar to your other programming courses. your file extension tells you the type of file. a lot of the work we will do will be html files. so we give it the .html extension. 

html stands for hyper text markup language. and basically what we will be doing here in this file is "marking up" the page. When we mark up and lable the page correctly, our web broswer can identify certain elements and display them correctly. 

Before we get started creating the content for our webpage. We need to add the most basic elements of the webpage. This is mostly some meta data that tells the browser about our webpage.

And after setting this up, we will put most of our code inside the `body` element. 

Here are the most basic elements. You should always have this on every html file you make.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

You can either copy paste the code above into your code editor, or if you have a fancy code editor like VS Code, then you can use a nice utility called Emmet. To learn more about Emmet, you can read up on it's [wikipedia page](https://en.wikipedia.org/wiki/Emmet_(software)).

As a quick start, you can use Emmet. 

To Emmet, you can type `!` then tap `tab`.

At this point, let's save. Let's look at our web page in a web browser. I'm going to pull up the page in chrome.

Now, since we don't have any content yet, I don't expect it to display anything. And that is indeed what we see.

![screen shot](screenshot.png)

Ok, so now would be a good time to add some content to our webpage.

Inside the `body` tag, we are going to add two more tags, a header 1 and a paragraph.

It should now look like this:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>This is a title header!</h1>
    <p>Welcome to my first webpage. This is a paragraph. In fact, it's the best paragraph in the history of forever.</p>
</body>
</html>
```

At this point, let's save again.

Now that we have made some basic changes to the content of the page and saved our work. Now is a good time to look at the updates in our web browser. 

![screen shot](screenshot.png)

Wow, amazing. Feel the power! 

That's great. You made your first webpage. Congrats!

But the file is still on your local computer. Another big component of web dev is uploading our files to a server. 

So in part two, let's upload this file to a server.

For this class, we will be hosting files on rit's banjo server, located at `banjo.rit.edu`. Because we are students, RIT has reserved some space on this computer for us to use.

We will need a way to copy paste or transfer the files from our local computer to the banjo server. 

I'll be using Filezilla for this. But you can use and FTP software you like. 

![screen shot](screenshot.png)

Let's connect to the server.

Do this by:

![screen shot](screenshot.png)

Then transfer over your file. 

Now that the file is on the server and in the right folder, we should be able to view it from the magical world of the internet and from any computer or mobile device.

We can test that right now.

Open up your web browser and type in: `website.com` That's my page. but if you swap out `nabigm` for your rit such as `abc1234` you should see your personal space. 

and with that you have successfully uploaded your first webpage to a server!

Congrats!

dancing happy gif

![screen shot](screenshot.png)

## Submitting

Don't forget to submit
