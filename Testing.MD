# The Monkees - Testing Document

##   [W3C Validation](https://validator.w3.org/#validate_by_input)

## Testing Pages

The Monkees and the Home page hold the same info as I didn't want the title to be a non existent part of the design and so adding the
link for the home page gives it functionality. These pages offer an insight into the band and so having them both working was important
as they're the starting guide for the user. I created a testing.html page so I could break as I added info before running changes in the main
pages of the website.

## Testing Navigation

The Pages are all designed with the customer in mind. I designed this as I'd want to use it and I asked my daughter to navigate around the 
website to make sure she could find information. I asked her to spend 10 minutes using the site and then asked her what she thought.
"This is a cool website Dad. I can find what I need on each page. Are they all meant to look the same though?" I smiled "Yes, that way you can
find your way around and it's not overwhelming"

So, this gave me an indication about the site having consistency and an easy to use formula. This is how I want all fans to see the site and
so a 10 year old finding their way was and good start.

Asking my wife to test it, not a fan of the band. She liked the layout, watched the music video and spent the day singing the song "Daydream
Believer". She even got a little upset after finding out one of the band members had passed away recently whilst I was putting the website 
together. She was able to find this information from the social medial links which are found on each page and each one opens up a fresh tab 
for the bands site so you can close and return to my website. A poignant moment but again, my site offered the starting portal for a user to 
go from and find their way to what the band is about and their story on a much bigger scale.

These tests showed my site was functional, offered up some information about The Monkees so you could find out names and a piece of their back
story. You could if it was fully functional contact the band and book them for a venue but if you simply wanted to start somewhere and go beyond,
my website offers that and is exactly how I wanted my website to work.

I tested the site personally on multiple devices to make sure it displayed correctly. It wasn't always the case and I'd have to go back and rewrite
some of the code but I got to a point where the site works fluidly on small devices such as mobiles, mid screen sized tablets to larger full screen
monitors.

## Personal logical testing for functionality

### Home Page:

When I first started the site, my original design was done in Bootstrap 3 but after a review by my newest Mentor, he advised to update to Bootstrap
4CDN and I had so much more scope on what I was able to achieve.

  * The Navigation Bar
   I added a Navigation Bar which I originally took from the BootstrapCDN website. I then re-designed the entire layout. It was white with blue writing
   with elements which weren't at all needed. There was also subject options and I changed it to Black, white writing and added links to each option.
   Once designed, I made the Navigational bar static so the user could always find their way around the site. Each change made needed a test to be 
   carried out. As I was doing this, I renamed the web pages to a different format so they were all lower case. These changes also needed to be tested 
   as the back end as well as the front end was changing.Adding Font Awesome icons to the navigation bar also changed as I was using newer icons to work
   with the new Bootstrap 4CDN layout so these all needed to be changed so there were mutliple elements to test as I worked on the navigation bar alone.

 * The main Hero Image. As I wanted this to technically be a static image, it took some figuring out within the CSS to have it as a non movng image but
   the rest of the page moves around it. As I worked on this, it wasn't always the case and also, with the Navigation bad, I should have mentioned that 
   these didn't always sit right togehter. There was padding and so a white gap between the Navigation bad and image so I had to correct this for it to 
   display correctly across the entire website.

 * Spacing for the paragraphs and Modal buttons. Well, on this case there were some major changes made. I was developing my site with Bootstrap 3, old
   design tags such as <br> and <center> to put it together. When my newest Mentor spent time and reviewed the code, he spotted all these "flaws" instantly
   and advised me of the changed I needed to make. So, with some time, I learnt how to use the grid layout for Bootstrap 4CDN which as I found was the 
   industry standard and provided me with much more functionality. I was able to design easier using layouts and so this proved indespensable in my learning
   and testing of the website. Before I had made the change to the grid system, I was already using Modals in my site as this was an extremley well laid out 
   format of bringing up extra information and adding interactivity to the site. Once I had the grid system worked out and in place, I could then integrate 
   the Modal layout to add extra funtionality to the website. 

  * Putting these together took a great deal of figuring out. The concept of the "holding" par of the Modal connecting to the "display" was difficult because 
   of the layout of the structure. The 4 paragraphs with their Name related buttons all sat together in a groupd of 4. Thr "display" design code all sat 
   below this so it wasn't 1 to 2, 3 to 4, 5 to 6, 7 to 8. It was 1 to 5, 2 to 6, 3 to 7 and 4 to 8 otherwise they didn't sit right on the page. Using this 
   grid and modal system, I was able to replicate onto the other pages after testing. I did initally have some inline styles adding padding around the Modal 
   images but I since changed it to add padding around the whole card. I also changed the colour of the buttons and each one was colour coordinated from the 
   click button, to the layout colour of the Modal and the close button on the Modal card itself.
   
  * The music video again, this seemed like an easy thing to add intially and sat "center" on the page but I found this weas incorrect and so putting 
    together another grid layout lined up the video to display in the middle of the page. 

*  The footers. I orginally had a different standard design for the footer social media links but after researching more, I was able to add the newer
   designed looking icons from Font Awesome and they displayed better. I then added the relevant URL to the social media code and tesred offering fully
   functional pages which open on new tabs so leaving the site doesn't happen.

### Our Merchandise

 * The Navigation Bar. The same testing was carried out as the homr page through out the site. Tested and working.

 * The main Hero Image was again, consitently tested throughout the site. Tested and working.

 * The Merchandise. I again used the grid layout with spacing in 2 rows of information. These rows then had Modals integrated into them, again the design
   had to be done 1 to 5 etc but there were 8 to add altogether which took some work and testing. I then added again, the same colour design so the 
   design of the Modal colour applied all the way through.

 * The footers were the same as the Home page for consistency. Tested and working.

### Get in Touch

 * The Navigation Bar. The same testing was carried out as the homr page through out the site. Tested and working.

 * The main Hero Image was again, consitently tested throughout the site. Tested and working.

 * Another grid system but with more complicated code which I took from W3C and edited so it laid out as I wanted it too. Both the Booking and Get In 
   Touch forms started off exactly the same but one is more developed than the other. I had to strip the Get In Touch down so it was a simple text box.
   There were easier ways to do it but the Form function concept was perfect for what I wanted and so making changes and testing took time as I removed
   a lot of information. Then, to make things more complicated, I wanted to add colour coding and a frame around the pop up Modals so they looked the 
   same as the rest of the site. Using CSS to my advantage and some none inline styles advised by my Mentor, I found the perfect combination but each
   stage was difficult and so thorough testing was carried out. The main booking Form took time as I had to edit the wording and add to it so there were
   more options such as times for the band to play etc but it gave me a fully working form which was good.

 * The footers were the same as the Home page for consistency. Tested and working.

### Touring

 * The Navigation Bar. The same testing was carried out as the homr page through out the site. Tested and working.

 * The main Hero Image was again, consitently tested throughout the site. Tested and working.

 * Adding thr touring buttons and testing was a much simpler process than the booking forms but still required a grid system and Modals. These again
   had to be added in the correct manner so the page laid out correctly and even though I said it was simpler, there were still moments when I was
   scratching my head. Once the layout was working correctly and there was a functional Modal, I then designed it the same as the other with CSS.

 * The footers were the same as the Home page for consistency. Tested and working.


### The website was tested on various devicdes as explained above and found to be working on all formats.