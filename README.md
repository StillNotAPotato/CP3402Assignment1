# CP3402 Assignment 1
--------------------------------------------------------------------------------------------------------------------------------
# Assignment Description

This learning journal documents my learning journey in the exploration and usage of CMSs for assignment 1.
Due to marketing campaigns by popular website builders such as Wix and Squarespace, the idea of a CMS was not foreign to me. However, following the requirements of this assignment, site-building websites were not allowed to be used. In my interpretation, the purpose of this assignment was to build a website using two different CMSs. The website did not have to be vastly different from the startup business it was meant for.

# Business Description
The name of my startup business is HappyTails Grooming. We aim to be not just a place for grooming but _the_ place for pet wellness. Using only the finest pet-friendly products, our top priorities are the owners' well-being and happiness, as well as the safety and happiness of their pets. Our skilled and caring groomers will ensure that every tail wags with delight after a visit to HappyTails Grooming.

# Goals and Desired Outcome(s)
1. To learn and build a website that is SEO-friendly.
2. To develop a website that would be effective in increasing the conversion rate for the business (a higher conversion rate equals more clients).
3. To create the means of attaining the goal of having 500 client bookings for any of the services offered within 6 months.

To achieve these goals, the following methods were implemented in the design of the website:
* Award discount vouchers (5 to 20%) to encourage bookings and call-to-action.
* A service review feature for our clients to leave their feedback regarding our quality of service, quality of grooming, and ease of site navigation.

The two CMSs which I had decided to use were WordPress and Joomla. These would be hosted on AWS Lightsail.

# Insights Acquired/Reflection
Once I had crafted and reviewed my site's goal, I then came up with several tactics to work towards the goal. Since we wanted more client bookings, providing attractive vouchers and call-to-action was a tried and proven tactic. It would be interesting to leverage a pop-up extension to achieve this, and I wanted to find one that would allow auto-open on page load.
Before diving into the research, however, I also designed the sitemap and thought of the various pages that will be making up the site. The discount voucher popup would only appear when a user lands on the home page, and we can have a separate pop-up with alternate content running a different campaign on others, to be decided later. I set out to research available extensions on the web that could support my idea. After finding a suitable free extension, I reviewed the documentation and managed to set it up via zip package upload installation.

It was at this point that I realized that I had to learn more about Joomla modules, which eventually led me to read about Joomla templates as well. The newly installed extension, Pop Up JT, is a site module. The plugin could only be added as a site module, so this required some additional reading. The installation of a similar pop-up module (plugin) on WordPress was much simpler and easier to manage. While reading the following 'getting started' guide ([https://docs.joomla.org/J3.x:Getting_Started_with_Joomla]), I focused more on modules and templates. Joomla templates are similar to WordPress themes, although slightly more complicated in terms of usability. The template primarily takes care of the look and feel of the site while also defining the usage of modules. Time spent trying to configure Pop Up JT was futile, as it didn't seem to be working as expected anymore. The documentation was lacking, and the existing forum did not provide much usefulness.
I moved on to trying out the installation of a free template on Joomla. The size of the template was bigger than the 40 MB limit from the Joomla admin portal. I had to then learn how to use FileZilla (an FTP client software) and workaround the 40 MB limit by uploading files directly into the Lightsail server.

Another issue that I encountered was trying to obtain SSL certification for my websites. Using Lightsail's browser client to enable HTTPS on both of my instances (WordPress and Joomla) proved challenging as I continued to get an error message saying that the configuration tool could not resolve the domain I had entered. Eventually, upon referring to forums as well as double checking my domain setup, I realised that I had in fact, not set up my domain correctly. The fix for this issue was simple, which was to simply register and buy a domain on AWS Route 53. Upon validating my account and purchase, the domain was up and running and I was able to enable HTTPS on both instances.

Attached below are my references:

https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-enabling-https-on-wordpress#https-wordpress-enable
https://stackoverflow.com/questions/59745340/unable-to-create-certificate-for-my-aws-bitnami-wordpress-website
https://joshhall.co/how-to-make-a-non-clickable-menu-item-in-wordpress/
https://wordpress.org/documentation/article/styles-overview/
https://wordpress.org/documentation/article/manage-wordpress-widgets/

Attached below is a screenshot of the sitemap proposed during the ideation stage:

![image](https://github.com/StillNotAPotato/CP3402Assignment1/assets/108881455/7bd9ce52-7a68-47bb-8e37-1910c38dbd15)

# Career/Employability Insights
This assignment has shown me that creating a website for a business is not as easy as it seems. It involves a great deal of planning as well as resource allocation (money, in my case). Furthermore, since I used AWS Lightsail and Route 53 for this assignment, I have become more familiar with using AWS's services, which are also extensively used in the industry. This assignment has also shown me that studying and working at the same time is incredibly difficult, as it has been greatly challenging to allocate enough time to meet school obligations and work.

# Website Links
* Joomla: [jm.steamedpotato.com	](https://jm.steamedpotato.com/)
* WordPress: [wp.steamedpotato.com	](https://wp.steamedpotato.com/)https://wp.steamedpotato.com/



