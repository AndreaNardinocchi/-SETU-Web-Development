# -SETU-Web-Development
This is a website created to be submitted as a first Web Development assignment for SETU, Waterford, Ireland.
# CN Cinzia Nardinocchi | Psychology & Counseling
This website is about a Family Counselor based in Italy.
# What this project does 
Its purpose is simply to provide information about the family counselor profession in terms of its history and evolution in Italy, what a counselor practically does, the type of therapies that Cinzia relies upon. Additionally, it includes a blog, a short biography and also some contacts to get in touch with the counselor.
# Why the project is useful
The project is useful for those users that would like to drill down a bit on the family counselor profession, as they can read up on it in the 'Home' page as well as on the 'Therapies' page. Additionally, this project might be useful for users that think they might need to avail of the family counselor's help and schedule some counseling sessions with Cinzia.
The ultimate ideas here would be to deliver a fully functional website to Cinzia, who currently does not have one, so that she can use it herself for her profession, and to enable her to establish a meaningful and important presence online aimed also at helping her business footprint growth.
# How users can get started with the project
<h2>Home</h2>

As a user opens up the CN Cinzia Nardinocchi | Psychology & Counseling Home page, they will see a sticky nav bar on the top for an easy navigation through the website.

<h3>Navigation bar</h3>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/a719d421-ca8b-4b6e-a732-a9262c8e590d"><br><br>

The code for the Flexbox navigation nav menu can be found in the 'nav.njk' and in the 'nav-foot.css' files:
<h4>Source attribution</h4>
// 
The knowledge source for this nav has been taken from "Beginner's Step by Step Coding Course-Learn Computer Programming the easy way", DK author, published in 2020, page 222-223 and:<br><br>

   
<ul>
     <li>https://freshman.tech/flexbox-navbar/ for Flexbox navigation </li>
     <li> https://developer.mozilla.org/en-US/docs/Web/CSS/overflow for overflow: hidden; (when content does not fit in the box, it will be hidden thanks to the value of this property) </li>
     <li>https://stackoverflow.com/questions/61545007/dropdown-menu-is-hidden-behind-my-hero-image  z-index: 1; (This property and its value enable the navigation bar to stick above any other elements in the website, which is helpful as the ultimate effect is to have a sticky one)</li>
     <li>https://css-tricks.com/almanac/properties/b/box-sizing/ box-sizing </li>
   </ul
  >//<br><br>



<h3>Hero banner</h3>

Right below the sticky nav bar, the user will se the Hero banner. 
Every page has a different hero image with a h1 header, whose code can be seen in the 'header' tag of each page and on the 'banners.css' file:

<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/965551a3-949a-4291-b2a3-7ecae45ea36e"><br>
index.njk

<img width="482" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/35e5f9ca-6c6e-4b47-b555-5c225239938b"><br>

<img width="439" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/0fac692a-448f-452a-9fea-b108641a030a">
<br>
banners.css
<br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/c1472f9e-2304-463e-8cbc-a77cf9b75353"><br>
<h4>Source attribution</h4>
// Part of the #banner id properties have been taken from "Beginner's Step by Step Coding Course-Learn Computer Programming the easy way", DK author, published 
   in 2020, page 314-315.//<br><br>

<h3>Main content section | Two column section</h3>
As the user scrolls down, there will be some informative sections regarding Cinzia Nardinocchi and the family counselor profession overall, such as what a counselor is and why a user might want to avail of their services, as well as on mental health.
A CTA to know more about Cinzia is embedded in the article, which will land the user to the 'About me' page.
The 2 column layout is achieved by means of a 2 column grid template (grid.css) in the #maincontent id resting, in turn, upon an underling 4 column grid template created in the .container class:<br><br>

<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/f1113148-cc03-4973-b78f-9f86b9f3506f">

.container class/rule <br><br>
<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/df3fb664-9ac9-4314-a304-78c24410f056"><br><br>
#maincontent id/rule and its children ids <br><br>
<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/10ada1d1-f7f2-420a-af22-1abea6a702e0"><br>



<h3>Three column section</h3>

Towards the bottom of the homepage, a user will come across a three column section where there is some short info about person, couples and family counseling with CTAs, which will take the user to the Therapies page where they can delve more into the topics:<br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/628a246c-c59f-4761-9341-c2209d711fad"><br>
#three-column-box id in the 'grid.css' file <br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/489b0aaa-b501-411b-8f1f-d4e4d10aaabd">

<h3>Horizontal-banner section</h3>

Right below the three column layout, there is an horizontal banner with an image in the background, an overlay content on the right and a CTA, which will take the user to the 'Contact & Fees' page. 
The code can be found in 'horizontal-banner.njk' and in 'banners.css': 

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/e6cc069e-c1bc-4925-a301-43627b2d571f">

<h3>Subscribe Newsletter section</h3>

The user will then hit a 'widget' to sign up for the newsletter with name and email fields and CTA to 'Subscribe', whose code is in 'horizontal-banner.njk' and 'form.css'.
<h4>Source attribution</h4>
// The idea of a subscribe widget has been taken from this website https://marisasitaliankitchen.com/, and the form code knowledge has been acquired here https://www.w3schools.com/howto/howto_css_contact_form.asp and https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form //<br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/9edd58c0-e79c-4170-aa52-085343fd5b66">

<h3> Footer </h3>

Finally, a footer with contact details and a logo, and an underfooter with a copyright mark and the developer's acknowledgement end the page flow.
The code for both can be seen in 'footer.njk' and 'nav-foot.css' where I used a 4 column grid template in the #footer id:<br>

<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/635fcd66-3561-4a85-8e0a-2615428ab1a4"><br>
nav-foot.css <br><br>


<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/8bfd6375-1e19-493b-a29a-fa4a9578462b"><br><br>

Navigation, newsletter subscriptions, footer and underfooter are experience fragments/blocks re-used across all pages.

<h2>Therapies</h2>

This page is an informative one providing insights on the history and evolution of the profession, its mission and, above all, the type of therapies:

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/72928e0c-d144-472a-822e-4026c9ed39ce"><br><br>
I wanted to create a re-usable block for the below section that I called 'underneath-banner' since it is consumed in 3 pages ('Home', 'Therapies', 'About me'), but its h2 header is different in each page and, therefore, I decided to leave it off as coded into the pages themselves:<br>


<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/e31227f3-ff5e-4644-9f51-192058e27271">


No CTAs on this page.

<h2>Blog</h2>

This page is a blog embedded into the website and users can see 4 articles at present on a 'two column' layout on the left and an 'aside' layout on the right column where the 'Latest Articles' should be rendered (only Lorem Ipsum content has been used in there as a sample).

By clicking on the first two article boxes on the top, the user will open up 2 articles, whilst the 2 at the bottom do not have content, at present (they just redirect to the Home page):

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/69d6f126-33f3-460e-b05c-196aebebf943">

<h3>Blog articles</h3>
<ul>
  <li><b>The Eternal Child</b></li>
  <li><b>Carl Rogers' Person-Centered Approach</b></li>
</ul>

The 2 articles preserve the structure of the parent 'Blog' page, although they do not show a hero image and the article layout is a one column only. The 'aside' layout 'Latest articles' is still present on the right end of the page.

Ex. 'Carl Rogers' Person-Centered Approach' article <br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/a0cab880-33bc-4fce-a7f7-87a3d5e735ee"><br><br>

This article also features a YouTube video of Carl Rogers.

Code can be observed in the 'blog.njk', 'sidebar.njk' and 'grid.css' file :<br><br>
<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/2a8b8e81-c11f-4dba-ad40-145575bb3125">
<br>
<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/539cac35-96a6-44bd-bbc9-f44595538a15">





<h2>About me</h2>

This page hosts a biography of the family counselor Cinzia Nardinocchi on the top with a link to a blog article on Carl Rodgers. It also has a section on her counseling guiding principles and a section at the very bottom inviting the user to schedule an appointment with Cinzia through a CTA button:<br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/97185f6c-1d80-405e-a22d-abf27dc959dc"><br><br>


<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/11ebb583-1ea6-4c0d-aa64-d3cda9bf77b7">

Noteworthy here is the white unorder list in the right column of the blue box :<br><br>

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/76c913cb-8ca9-4af9-bb80-ea17e78dbfc9">
<br><br>
Its css code is in the 'grid.css' file:<br><br>
<img width="300" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/78022530-f947-450f-b750-e92e54fc159a"><br><br>

<h4>Source attribution</h4>
// The white list has been created by observing what was done in this link https://sharkcoder.com/blocks/list Example #2* //<br><br>



<h2>Contact & Fees</h2>

This page provides the user with info regarding the counselor's location, a map, a picture of the counseling room and a form to fill out to get in touch with the counselor:

<img width="500" alt="image" src="https://github.com/AndreaNardinocchi/-SETU-Web-Development/assets/51911079/e29f90b0-a30c-4fdf-b7fc-11197bb6cd9d"><br><br>

The form code can be found in the block 'contact-form.njk' and 'form.css'.

<h4>Source attribution</h4>
// The form code knowledge has been acquired here https://www.w3schools.com/howto/howto_css_contact_form.asp and https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form //<br><br>


# Where users can get help with your project

As shown above, aside from information regarding the counselor profession and counseling overall throughout the pages, the 'Home', 'Blog', 'About me' and 'Contact & Fees' pages show CTAs for users to take action and get in touch with the family counselor.

# Who maintains and contributes to the project

This project will be maintained by myself only.



