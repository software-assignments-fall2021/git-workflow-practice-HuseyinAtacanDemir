# Dependency Confusion
## Or How Some PenTester Hacked Into some of the Biggest Companies in the WORLD

![dependency confusion](https://www.zdnet.com/a/img/resize/10ad3492e018e8d44192244a632a9f8758e504f2/2021/02/09/a9a2f23d-b603-45ef-b69d-7e98593f11e6/dependency-confusion.png?fit=bounds&auto=webp)

### The Story

We have all used numerous package managers, such as npm, pip, homebrew, apt, etc.
But have we ever considered who is maintaining all the thousands of dependencies that our projects link to? Or have we taken for granted the fact that we are all sitting on a ticking bomb of countless dependencies where through an exploit in just one dependency, our whole project may become vulnerable?

<br/>
What about public dependencies and private dependencies? What would happen if someone figured out the names of private dependencies that your team has created for your project, and created a public npm package under those names? Well, <a href="https://twitter.com/alxbrsn">Alex Birsan</a> answers that question in his <a href="https://medium.com/@alex.birsan/dependency-confusion-4a5d60fec610">article</a>.

<br/>
<br/>

_Here is a video on the topic by one of my favorite youtubers Hussein Nasser_

[![_Here is a video on the topic by one of my favorite youtubers Hussein Nasser_](https://img.youtube.com/vi/43g3PF-e4ik/0.jpg)](https://www.youtube.com/watch?v=43g3PF-e4ik "Dependency Confusion")


## Student Comments

### Julie Pirro - jap871
I was actually wondering about this topic earlier last week! How can commands like "pip install X" run directly on my laptop without having to actually download something from the internet? Isn't this a big security risk? I thought the explanation behind the hacking was very interesting in this article. I also loved how this article went into how big companies offer a "bug bounty" for essentially hacking into their systems. 


<br/>

<p>Edit by Christian Weinschenk:</p>

</br>

<p> This is really cool and its unfortunate to see that package managers like NPM can be absued to hack into even larger corporations. Package managers are very ubiqitous and this seems very wildly applicable and could do a lot of damage. It reminds me a lot of an <a href="https://www.w3schools.com/sql/sql_injection.asp">SQL Injection</a> attack and I would hope that this is patched out.</p>

