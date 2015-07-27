# PBT-Propeller
PSD to Web Conversion by Stephen Collins

http://beesmart.github.io/PBT-Propeller/

##Framework
The website uses some Sass styles & code from a lightweight template called "Bones"  - http://themble.com/bones/
I've used this template for a while now and I like to use it as a boilerplate for Sass, I simply extracted what I needed and left the rest. I understand the request not to use a 'framework', I agree that Bootstrap can often be too heavy and loaded, whereas Bones, as the author states: 

"Bones is not a Framework
Frameworks are great, but sometimes they make things more complicated than they need to be. Bones is as bare and minimalistic as possible. It's meant to be used on a per-project basis."

##Responsive
The site, as above uses Sass and a lot of the responsive styles are bing brought in through seperate scss templates. I refinied responsiveness through Chromes emulator.

##Jquery, interactions & extras
The site uses SlickNav for the mobile menu, cycle2 slider, Font awesome for icons. I'm also loading in the twitter widget. There are a number of minor css animations for hover effects but I kept it all pretty light.

http://slicknav.com/
http://jquery.malsup.com/cycle2/
http://fortawesome.github.io/Font-Awesome/

##Build
I used yeoman/grunt (http://yeoman.io/) to scaffold the app and grunt build tools to deploy. So the app folder has the relevant scss files while the dist folder, everything's minified. 

##Things to imporve
I'd like to do some work with the instagram API, add some functionality to the sign up form and I'd also like to improve the look of the footer contact details and how they react on mobile screens.

###SEO 
I haven't looked at image ALT tags or other SEO optimisations.

