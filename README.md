# HTML Email Hybrid - Fluid Approach Responsive Design


## HTML Email Boilerplate Document Type and Meta Tags



## 600px Breakpoint



## Why we use HTML Table Element in HTML Email Development 




### This maso can cause line height problem

mso-line-height-rule: exactly !important;
         mso-table-lspace: 0 !important;
         mso-table-rspace: 0 !important;


 ## Dark Mode Styling in Email Client Support    

 ### CSS Property Dark Mode using the root element

 -color-scheme: light dark;
 - supported-color-scheme: light dark;


 Preference is always in using root    


 ## ogsc and ogsb

 [data-ogsc] h1 {
          color: #3d3d3d !important;
        }

        [data-ogsb] h1 {
          background-color: #e13939 !important;
        }


padding = 0 added to the data tag removes the cell padding.

border-collapse : collapse; removes all cell spacing

border-spacing : 0 ; removes ...

        <table width="100%" style="border-spacing: 0;"  role="presentation"


 <table align="center" style="border-spacing: 0; border-collapse: collapse; color:#242424; font-family:Arial, Helvetica, sans-serif;
               font-size: 16px; margin: 0 auto; max-width: 600px; width: 100%; background-color:#fafdfe " role="presentation"
         >
            
               <tr>
                  <!-- remove padding from the table data role -->
                  <td style="padding: 0;">
                     <table width="100%" style="border-spacing: 0;"  role="presentation">

                     </table>
                  </td>
               </tr>

</table>


- removing border. 0 doesnt change anything
## Best Practices

## IMAGE LINK

wrap images in links
Add font-size inline because not all Email client

<!-- Image Links:
https://i.ibb.co/1fN4jNV/w3newbie.png
https://mcusercontent.com/474f5b70c3b324277323d4c42/images/8c6d35c2-2b66-5af9-d40f-1eec9d2dcaf3.png
https://raw.githubusercontent.com/w3newbie/html-email-mastery-images/main/basic-template/w3newbie.png

https://i.ibb.co/djwMPKK/lock-banner.jpg
https://mcusercontent.com/474f5b70c3b324277323d4c42/images/80657041-e007-7e23-37ed-2e10ac4f5cac.jpg
https://raw.githubusercontent.com/w3newbie/html-email-mastery-images/main/basic-template/lock-banner.jpg

https://i.ibb.co/84RF9Vc/button.png
https://mcusercontent.com/474f5b70c3b324277323d4c42/images/0f63e7e6-d834-2e03-a0f8-17b043f7763e.png
https://raw.githubusercontent.com/w3newbie/html-email-mastery-images/main/basic-template/button.png
-->

<!-- Icon: <a href="https://www.flaticon.com/free-icons/password" title="password icons">Password icons created by Freepik - Flaticon</a> -->



## GRADIENT BACKGROUND

Ways to add gradient background on HTML EMAIL

## Height

Three ways to add height

Padding method is preferably for both height and width
Margin doesnt have good support in HTML email


-- We style inside table data element with padding


-- Fluid-Hybrid 100% width Responsive Column
-- Media Query styling at 600, 500 and 400px widths
-- Dark Mode styling and CSS Blend Mode
-- Background Images with VML for Outlook
-- Button and Images in VML with radius for Outlook



## STRIPE COPYWRITE

build great payments experiences with stripe, improve performance, expand into new markets, and engage customers with subscriptions and marketplaces.

Simplified Cross border payment with Strip

Power your e-commerce payment with Stripe



Stripe is Built for growth
Take your startup farther, faster

Startups build on Stripe to launch faster, adapt as they grow, and automate workflows to do more with less. Build your own API-based integration or use our low- to no-code solutions, which are simple enough for easy implementation and powerful enough to scale as fast and as far as you need.


Millions
BMW owners using ConnectedDrive Store
350+
US dealerships
Products used
Payments
Connect
5+
Amazon businesses on Stripe including Prime, Audible, and Amazon Pay.

50+
Payment methods available on Stripe


Connect
130
Countries in logistics network
$10+

+5.5%
Uplift from Stripe's Global Payments Infrastructure



 <tr>
                    <td style="padding: 20px 40px;">
                        <div style="text-align: center; margin-bottom: 20px;">
                            <img src="https://i.ibb.co/7zvZ3J2/summer-mountain-climbing.jpg" alt="Summer Mountain Climbing" style="width: 100%; max-width: 600px; height: auto;">
                        </div>
                        <h1 style="font-size: 24px; font-weight: 700; margin: 0 0 20px;">Summer Mountain Climbing</h1>
                        <p style="margin: 0 0 20px;">Summer is the perfect time to go mountain climbing. The weather is warm, the days are long, and the mountains are calling. Whether you're an experienced climber or a beginner, there's a mountain out there for you. From the towering peaks of the Himalayas to the rugged terrain of the Rockies, there's no shortage of places to explore. So pack your bags, lace up your boots, and get ready for the adventure of a lifetime.</p>
                        <p style="margin: 0 0 20px;">Here are some of the best mountains to climb this summer:</p>
                        <ul style="margin: 0 0 20px; padding-left: 20px;">
                            <li>Mount Everest, Nepal - <strong> $5000 </strong> </li>
                            <li>Mount Kilimanjaro, Tanzania - $3000</li>
                            <li>Mount Rainier, Washington - $2000</li>
                            <li>Mount Elbrus, Russia - $4000</li>
                            <li>Mount Fuji, Japan - $2500</li>
                        </ul>
                        <p style="margin: 0 0 20px;">No matter where you go, be sure to pack plenty of water, food, and warm clothing. And always remember to respect the mountain and the environment. Happy climbing!</p>
                    </td>
                </tr>


                <div style="text-align: center; margin-bottom: 20px;">
                    <a href="https://www.example.com" style="display: inline-block; padding: 10px 20px; background-color: #FFA500; color: #ffffff; text-decoration: none; font-size: 16px; font-weight: 700; border-radius: 5px;">Make a Booking</a>
                </div>
