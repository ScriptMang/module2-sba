# Reflection Questions

## What accessibility challenges did you face, and how did you address them?

One of the challenges I faced was making sure the headings were in sequential order for better navigation. Even though it's easy to do, it's something you can forget while building a site. The issue with sequential headings is it ties into each section. For example, I had a set of h4 tags in a section that I needed to change to h2s. Another is I had to make sure to use aria-labeledby instead of aria-label. The reason being that aria-labeldby overrides the other aria-label attribute. 

## How did you ensure that your design was responsive and accessible to all users?

The way I made sure the design was responsive was the use of the meda query label for stacking the flexboxes at a small enough width. As for the accessibility, I used aria-labeledby attributes for describing buttons. I also made sure to use native semantic html where needed instead of over using div. 


## What tools or resources did you find most helpful during this project?

 I found the chrome web tools, lighthouse extension, and the mdn docs very helpful. However, I found the chrome web tools the most helpful. It is just a big box of different tools I can use without opening another app. I used the page inspector to hover over elements and see their contrast score. Whenever my styles wouldn't apply, I would click on the style tab  to locate any weird css applied before it. When I ran into trouble with a flexbox or gridbox clicking the button to show the container's outlines helped diagnose the issue.  Another tool I used was 
 Lighthouse. I would  have it inspect the page for any missing accessibility attributes. As for the mdn docs, I found it the most helpful for checking which aria attributes to use. 
