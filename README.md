# Milestone-1 Project / Forever Fit Gym /

![page mockup](/assets/images/mockup-ffgym.png)

View the live project [here](https://syler11.github.io/ms1-gym/).

Local gym in the City of Stirling with growing client base.  
The gym offers extensive variety of classes and gym space for all age group, gender.   
The gym is easily accessible and located in the City Centre. 
The website offers several functionalities to retain existing client and gain new ones.

### **Project Goals:** 
The project helps me to showcase my knowledge of HTML and CSS and Bootstrap. 

### **User Goals:** 
To find relevant information after arriving from a search or referral link to this website. 

### **User Stories:**
**First Time Visitor Goals**  
* As a First Time Visitor, I want to easily understand the ethos of the gym and what they offer me as client.
* As a First Time Visitor, I want to be able to easily navigate throughout the site to find content relevant to me.
* As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted.
* As a First Time Visitor, I want to find information about different membership and pricing. 
* As a First Time Visitor, I want to find out what is demographics of the gym goers. 

  ![pricing](/assets/images/pricing.png) 

**Returning Visitor Goals**  
* As a Returning Visitor, I want to find the best way to get in contact with the gym.
* As a Returning Visitor, I want to find information where to park if arriving by car.
* As a Returning Visitor, I want to find the best membership option meet my requirements.  

![info](/assets/images/info.png)

**Frequent User Goals**  
* As a Returning Visitor, I want book my classes using via the website.
![book a class](/assets/images/book-a-class.png)



### **Site Owner Goals:**
The site owner would like to get more business by exposing the users to this content.   
Also this surface is retaining existing client providing information and facilities to them. 

### **User Requirements and Expectations:**
Users have a set standard what they expect to find when they arrive to a website e.g. navigation, contact page with contact details and so on.   
These needs and requirements were met throughout the website design. 

### **Design Choices:**
Design choices were made to have high usability of website.  
Classes were structured in table form as usually expected for such information. 
Membership choices were categorized to address all age groups.

### **Colors:**
**Background colours**
* #e35b17 RGB(200, 80, 20)
* ##7d7d7d RGB(117, 117, 117)  

**Font colours**  
* #fff as the default text color 


### **Fonts:**
My font family choice is “Montserrat” with Sans Serif as a fall back what was taken from [Google Font](https://fonts.google.com/specimen/Montserrat?query=mon&preview.text_type=custom).

### **Structure:**
The website consists of 5 separated pages namely index.html, about.html, membership.html, classes.html and contact.html.


### **Wireframes:**
 Wireframing helped me to put together the project without coding a single line.   
 Once the finished wireframes were printed the coding process was very smooth and straightforward.   
 Wireframes are available in [bmpr](https://syler11.github.io/ms1-gym/assets/wireframes/MS1-Gym.bmpr) and [pdf](https://syler11.github.io/ms1-gym/assets/wireframes/MS1-Gym.pdf) format. 

### **Features:**
**Index**  
The user by clicking on the Sign Up button is able to fill up a from and send it to the gym.  
With the sent information the gym would be able to reply and discuss a free introductory session with the new potential client.  
The first section will give a short insight what the gym can offer.  
User testimonials to help first visitor to build trust.  
Map and transport to help the users to make their first virtual visit. 
The local bus times are also linked for better user experience. 

**About Us**  
Short description of the gym and its ethos with a video tour.   
(video is not realted to this business and was taken from Youtube see Credits below)   
Progress bar to showcase of the gym's demographics.  
Cards to emphasize the different features of the gym.  

**Membership**  
Pricing description as passes and monthly plans with pictures.
By hovering over the price tags the box shadow would increase. 

**Classes**  
Throughout description of the classes, their intensity and schedule.  
By hovering over the class description the box shadow would increase.   
Book a class modal to make an online booking and downloadable pdf format is also available.

**Contact**  
Contact form to send direct message from the website.  
General contact information and opening times.  
Map and transport option repeated for a second virtual journey.  
The local bus times are also linked for better user experience. 



### **Technologies used:**
The following languages and framework were used to create this project.  
* HTML5 – provided the main structure of the website.
* CSS3 – provided the styling of the website and the overall content.
* Bootstrap 4.6.1 – provided the responsive structure and some other component such as jumbotron, modal, navbar. 
* Balsamiq - development tool was used to create the wireframe for the website. 
* Git - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
* GitHub - GitHub is used to store the projects code after being pushed from Git.


### **Testing:**
The main testing took place in Google Chrome and its Developer tool using the Network and Lighhouse options to  
identify any errors or opportunities to improve performance.    
After the deployment the website was tested on different screen sizes and in different OS systems.  
I have asked my wife and few of my friends to test the website and their feedback was taken on board.  

### **Validation:**  
Html pages were validated by [W3C Markup Validation Service](https://validator.w3.org/)  
1. Index.html  
![result](/assets/images/validation/html-validation-index.html.png)
2. Aboutus.html  
![result](/assets/images/validation/html-validation-aboutus.html.png)
3. Membership.html  
![result](/assets/images/validation/html-validation-membership.html.png)
4. Classes.html  
![result](/assets/images/validation/html-validation-classes.html.png)
5. Contact.html  
![result](/assets/images/validation/html-validation-contact.html.png)

Css code was validate by [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)  

Style.css  
![result](/assets/images/CSSvalidation.png)

The website accessibility was checked with [Wave Web Accessibility Evaluation Tool](https://wave.webaim.org/).

As a result I had to changed the font and background colors to achieve higher contrast to eliminate contast errors.   
The original orange color (#357464) was changed to (#c85410), grey color (#7d7d7d) was changed to (#757575) and   
the font color (#fafafa) was changed to (#fff) for better contrast ratio.
![result](/assets/images/validation/Wave-report.png)

Conclusion: In the future the colors will be checked before the coding would even start. 

**Chrome Lighthouse Test**

1. Opened up my deplpyed webpage in a new incognito tab in Google Chrome.  
2. I used CTRL+SHIFT+I key command to prompt the Developer Tool.
3. I navigated to the Lighthouse menu option (usually the option is not visible but clicking on the  >> sign will reveal it)
4. I select all 5 categories and selected desktop option and repeated steps for all 5 pages

![result](/assets/images/validation/chrome-lighthousetest-desktop-index.html.png)
![result](/assets/images/validation/chrome-lighthousetest-desktop-aboutus.html.png)
![result](/assets/images/validation/chrome-lighthousetest-desktop-membership.html.png)
![result](/assets/images/validation/chrome-lighthousetest-desktop-classes.html.png)
![result](/assets/images/validation/chrome-lighthousetest-desktop-contact.html.png)


5. I select all 5 categories and selected mobile option and repeated steps for all 5 pages

![result](/assets/images/validation/chrome-lighthousetest-mobile-index.html.png)
![result](/assets/images/validation/chrome-lighthousetest-mobile-aboutus.html.png)
![result](/assets/images/validation/chrome-lighthousetest-mobile-membership.html.png)
![result](/assets/images/validation/chrome-lighthousetest-mobile-classes.html.png)
![result](/assets/images/validation/chrome-lighthousetest-mobile-contact.html.png)



### **Deployment:**
**GitHub Pages**  
The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the GitHub Repository  
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.  
3. Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
4. Scroll down the Settings page until you locate the "GitHub Pages" Section.
5. Under "Source", click the dropdown called "None" and select "Master Branch".
The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

**Clone a Repository**  
1. On GitHub, navigate to the main page of the repository.
2. Above the list of files, click  Code.
3. To clone the repository using HTTPS, under "Clone with HTTPS", click . To clone the repository using an SSH key,   
including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click.   
To clone a repository using GitHub CLI, click Use GitHub CLI, then click.
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory.  
6. Type git clone, and then paste the URL you copied earlier.  
7. Press Enter to create your local clone.

**Browser Preview**
Browser preview was used between commits using the following steps...

1. Open terminal in GitPod. 
2. With Ctrl+C the cursor was prompt.
3. python3 -m http.server command line was used to open up a private port.
4. Once the port 8000 was serving the page was opened by clicking on the Open Browser tab.

### **Bugs:**
The menu toggler was one area where I spent lot of time to try to find a solution.     
My primary goal was to give a custom color scheme to the menu items and to the toggler too.   
After my second session with Mo (mentor). I decided to do this icon from scratch rather using the Bootstrap predefined icon.  
With that being done I was able to fully customize all the elements I wanted. 

Embedding images in div container and make them responsive was very time consuming in the beginning  of the task.  
I researched the topic and read many topics and watched a few Youtube tutorials and I was able to resolve the issue fully. 

### **Credits:**
Content
* Logo Linear gradient feature - [Source](https://cssgradient.io/blog/css-gradient-text/)
* The photos used in this site were obtained from Pexels.com, Rawpixel.com and Pixabay.com. 
* Icons were obtained from FontAwesome.com 

Acknowledgements  
* Photo by Cleyder Duque from Pexels quotes-guy.jpg  
* Photo by Cliff Booth from Pexels quotes-lady.jpg  
* Photo by Elly Fairytale from Pexels - fitness-class.jpg  
* Image by rawpixel.com - personal-training.jpg  
* Image by pixabay.com - weights.jpg    
* Photo by William Choquette from Pexels - treadmill.jpg  
* Photo by F-Jord from Pexels - lockerroom.jpg  
* Photo by Polina Tankilevitch from Pexels - nutribar.jpg  
* Image by rawpixel.com - contact.jpg  
* Image by rawpixel.com - about.jpg  
* Photo by Tim Samuel from Pexels - solo1.jpg  
* Photo by Mister Mister from Pexels - solo2.jpg  
* Photo by Timothy from Pexels - student1.jpg  
* Photo by Andrea Piacquadio from Pexels - student2.jpg
* Photo by rawpixel.com - couple1.jpg
* Photo by Bruno Bueno from Pexels - couple2.jpg  
* Photo by Yan Krukov from Pexels - oap1.jpg  
* Photo by Karolina Grabowska from Pexels - junior1.jpg
* Video by Fountain Valley LA Fitness [Youtube.com](https://www.youtube.com/watch?v=Gdf-dxNKKOU)

I received inspiration for this project from my mentor Mo who didn't let me to go   
the easy way and as a result I feel lot more confident in the end by solving these problems along the way.   
Thanks Mo
