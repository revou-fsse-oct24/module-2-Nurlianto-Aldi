# Module 2 Assignment

Name    : Nurlianto Aldi

Section : Paris

Team    : 3

## Checkpoint #1

### Task
1. Applying custom font using @font-face or embed &#x2714;
2. Applying text-shadow to text and list-style to the list &#x2714;
3. Applying 1 responsive background image, (using contain or cover, suit your needs) &#x2714;
4. Applying 1 responsive image with picture + source + srcset method &#x2714;
5. Creating one Asymmetrical Grid → layouting grid, both container and item (children)
6. Creating simple animation with two methods: animation and transition &#x2714;

### Applied

1. I added a custom font to the H1 of the Hero section in `index.html`.
2. I also added a text-shadow to the H1 of the Hero section in `index.html`.  

   <p align="center">
     <img src="assets/markdown/task-1.png" alt="the result of task one & task two" height="100">
   </p>

3. I applied a responsive background image in the Hero section of `index.html`.  

   <p align="center">
     <img src="assets/markdown/task-3.PNG" alt="the result of task three" height="100">
   </p>  

4. I implemented a responsive image using the `<picture>` element in the card section of `index.html`.
<br>
   <p align="center">
     <img src="assets/markdown/task-4-a.PNG" alt="the result of task four (global resolution)" height="100">  
    </p>
    <p align="center">
     <img src="assets/markdown/task-4-b.PNG" alt="the result of task four (768px resolution)" height="100">
   </p>  

5. For the asymmetrical grid, I added a "GALLERY" link in the navigation bar that links to a gallery page. This gallery uses `display: grid` with an asymmetrical layout styled with `:nth-child(3n - 2)`. I also added a zoom effect to the images when hovered, using CSS transitions.  

   <p align="center">
     <img src="assets/markdown/task-5.PNG" alt="the result of task five" width="200">
   </p>  

6. I added transitions to navigation links, buttons, and images in `gallery.html`. I initially considered adding animations using keyframes, such as a bouncing ball, but decided they didn't fit the website's style. However, the code for this animation is included as commented code.  
    <p align="center">
     <img src="assets/markdown/task-6-nav-link-a.PNG" alt="the result of task six (navigation link transition)" width="200">
    </p>  
    <p align="center">
     <img src="assets/markdown/task-6-button-a.PNG" alt="the result of task six (button transition)" width="200">
   </p>  

<br>
<br>

note: i can't show you the before and after of the transition because i'm using sniiping tools. Please, just try it by yourslef.  

another note : i update this assignment in Novemebr 11 2024 because i'm not confidence enough to show it to anyone. Since the final checkpoint need to deploy the website (means everyone can see it) then i fix my website and ready to deploy. Thanks for the understanding.

## Final Checkpoint

### Task
Deploy a website about things that you built and deployed on Netlify. The deployment must be auto deploy from your project’s main branch using GitHub Action. Your portfolio website can be accessed by custom domain (example domain : http://budoacademy.rf.gd/ ) and documented on a readme with screenshots. Readme must explain about:  

1. Netlify Sign up process & connect Netlify to your Github project  
2. Auto Deployment on Github with Netlify  
3. How to connect your custom domain and DNS  

### Applied

## Web Description
This is a company that providing maintenance for The Jaeger (a robot for figth the Kaiju; don't heve a clue? Just watch Pacific Rim movie). This website serve as a place for the Jaeger's pilot to gain information about the service the company provide.

Step by step about deploying and Applying custom domain to the website:

1. Deploy it on Netlify  
    a. First, we need to go to netlify.com  
        <p align="center">
          <img src="assets/markdown/Deploy-1.PNG" height="100">
        </p>  
    b. Second, we need to log in with GitHub Account (You can login with another method if you are not using GitHub)  
        <p align="center">  
          <img src="assets/markdown/Deploy-2.PNG" height="100">
        </p>  
    c. Third, when you already on the dashboard, click on the "Add New Site" button and select "Import an existing project"  
        <p align="center">  
          <img src="assets/markdown/Deploy-3.PNG" height="100">
        </p>  
    d. After that, choose from where you want to import the project (i choose GitHub beacuse my project is on GitHub)  
        <p align="center">  
          <img src="assets/markdown/Deploy-4.PNG" height="100">
        </p>  
    e. Then, you can choose in which organization your project is (Mine is not on my account, but in oragnization)  
        <p align="center">  
          <img src="assets/markdown/Deploy-5.PNG" height="100">
        </p>  
    f. After that, select your desired repo to deploy  
        <p align="center">  
          <img src="assets/markdown/Deploy-6.PNG" height="100">
        </p>  
    g. Then, you can fill all the information needed and click on the "Deploy (yoursitename)" button (but actually, you just need to fill the "Site name" and left the rest)  
        <p align="center">  
          <img src="assets/markdown/Deploy-7a.PNG" height="100">
        </p>  
        <p align="center">
          <img src="assets/markdown/Deploy-7b.PNG" height="100">
        </p>  
    h. After that, wait for netlify to build your site (it could take a couple minute to an hour).
        <p align="center">  
          <img src="assets/markdown/Deploy-8.PNG" height="100">
        </p>  
    i. Then, tada! Your site already deployed.
        <p align="center">  
          <img src="assets/markdown/Deploy-9.PNG" height="100">
        </p> 
2. Buy your custom domain  

    You already deploy your site to the internet, now everyone can acces your site throught its domain. Congratulations! But as you can see, even though your second-level domain has a name that you already wanted, but the top-level domain is still not quite you wanted (it has netlify.app). So you need to buy a custom domain first.

    a. First, go to your desired domain registrar (i'm prefered niagahoster.co.id because Kak Mahi told me to do so)  
        <p align="center">
          <img src="assets/markdown/buyDomain-1.PNG" height="100">
        </p> 
    b. Second, log in with your google account (you can log in with another method)  
        <p align="center">  
          <img src="assets/markdown/buyDomain-2.PNG" height="100">
        </p> 
    c. Third, on the dashboard, got to "Domains" tab and click "Get a New Domain"
        <p align="center">  
          <img src="assets/markdown/buyDomain-3.PNG" height="100">
        </p> 
    d. After that, you can type your desired custom domain on the search bar. You can also choose the top-level domain based on your desire (or your budget). Scroll down to see its availibility.  
        <p align="center">  
          <img src="assets/markdown/buyDomain-4.PNG" height="100">
        </p> 
    e. Then, continue with the payment  
        <p align="center">  
          <img src="assets/markdown/buyDomain-5.PNG" height="100">
        </p> 
        <p align="center">
          <img src="assets/markdown/buyDomain-5b.PNG" height="100">
        </p> 
    f. You can see your purchased domain at the "Domain Portofolio" tab section. Congratulations, you are already purchased a custom domain based on you desire (or budget)  
        <p align="center">  
          <img src="assets/markdown/buyDomain-6.PNG" height="100">
        </p> 
3. Applying custom domain to your site on Netlify  

    Yes, you already your custom domain, but that doesn't mean its already applied to your site. You need to connect it between your site and your custom domain.

    a. First, go back to your domain registrar and on the "Domain" tab section, click on the "Domain protofolio" and choose your already purchased custom domain then click "Manage"
        <p align="center">  
          <img src="assets/markdown/buyDomain-6.PNG" height="100">
        </p>  
    b. Then, click on the "DNS / Nameservers" tab section and look for the "Nameservers" and remember that 4 Nameservers (Just kidding, you don't need to remember it, you can just copy-paste it)  
        <p align="center">
          <img src="assets/markdown/connectDomain-1.PNG" height="100">
        </p> 
    c. After that, go back to netlify.com and choose your deployed site
        <p align="center">  
          <img src="assets/markdown/connectDomain-2.PNG" height="100">
        </p> 
    d. Then, on the site overview, look for "Set up your site" section, and click on the "Set up a custom domain ->"
        <p align="center">  
          <img src="assets/markdown/connectDomain-3.PNG" height="100">
        </p> 
    e. After that, fill the input text with the custom domain you already bought and click verify. If its available, then you can click on "Add domain"
        <p align="center">  
          <img src="assets/markdown/connectDomain-4.PNG" height="100">
        </p> 
        <p align="center">  
          <img src="assets/markdown/connectDomain-5.PNG" height="100">
        </p> 
    f. Then, in your dployed site, go to "Domains" tab section and look for "Name servers" section. Copy all 4 of the Name Servers (that looks like dns.p09.nsone.net)
        <p align="center">  
          <img src="assets/markdown/connectDomain-6.PNG" height="100">
        </p> 
    g. Last, go back to your domain registrar. click on the "Change Nameservers" and paste it the Name Servers from the netlify. Don't forget to click "Save" button. 
        <p align="center">  
          <img src="assets/markdown/connectDomain-7.PNG" height="100">
        </p> 
    h. Finally, your website already deployed and has it custom domain. (You can check your site on netlify.com and need to wait a couple minute to an hours for the servers to be connected)
        <p align="center">  
          <img src="assets/markdown/connectDomain-8.PNG" height="100">
        </p> 
    You can see the result of my deployed website with custom domain at https://jaegerpremiumcare.site/
        <p align="center">  
          <img src="assets/markdown/connectDomain-9.PNG" height="100">
        </p> 