# Fika Coffee Shop

One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch.

---

# UX

## STRATEGY

### Focus
The site owner has a newly built Coffee Shop based in the local village of ferns he is currently using Facebook, 
Instagram and twitter but wishes to take the final step in creating an online presence by creating a website where customers 
can easily contact the Coffee shop and review there constantly updating Menu.

### Definition
The Site owner requires a brand new website to accompany his brand new coffee shop allow customers to easily and clearly 
find what they are looking for.

### Value
Building this site gives the owner the full online presence he is looking for along with make customers aware of the 
coffee shops locations and what is available via the menu.

## SCOPE

### External user’s goal:
* The site's users are potential customer, who want to know more about what’s on the menu.
* Customers can easily locate the Coffee shop given its based inside a village.
* Everything is easy to find on site appealing to customers to come back to the site.

### Site owner's goal:
* FIKA Coffee Shop is interested in attracting and retaining customers.
* Display there menu.
* Online Presence.
* Insure customers are aware of there opening hours.

### Potential features to include:
* Coffee Shop Menu
* About the Coffee shop
* Home page
* Whats new
* Gallery
* Contact/Location

## STRUCTURE

### Interaction Design
We want to entice customers visiting the website to show an interest in our menu of what is available to drink and eat 
and from there using our google maps location, easily find the place.

### Requirements
* Displaying new products that become available
* Display Company's opening hours
* Viewing the Menu
* The location will be available.
* Information on the company and the Coffee beans used.
* Display Active Social media icons

### Information Architecture
1. We want the menu navigation to go like Home, About, Our Menu and Contact / Location,  
This is the most effective way of displaying it as we are telling a story as we go along from right to left in the menu.

2. We want the Menu to be displayed completely on the site to make it easier for customers, 
also will be displayed is all new Coffees at the very top.

3. We want Contact details, and location displayed on the same page, insuring customers don’t 
have to click around the site searching for information.

4. The preference for the home page is attracting customers to view the menu 
whilst also displaying any new coffee that has become available.

5. Display Opening Hours.

6. Give customers a back story on the brand new Coffee Shop and where our fresh Coffee beans come from.

## SKELETON

### Wireframes - Desktop / Tablet / Mobile
* [Home](assets/images/wireframes/Fika-Home-Page.pdf)
* [About](assets/images/wireframes/Fika-About-Page.pdf)
* [Our Menu](assets/images/wireframes/Fika-Our-menu.pdf)
* [Contact](assets/images/wireframes/Fika-Contact-page.pdf)

## SURFACE

[Home Page Mockup](assets/images/readme-images/Desktop-Home-Fika-Coffee-shop.pdf)

### Fonts
* Crimson Text - 700 Bold

* Montserrat - 400 Regular

### Colours
![Colour Orange](assets/images/readme-images/Orange-EE8726.png) | ![Colour Black](assets/images/readme-images/Black.png) | ![Colour Grey](assets/images/readme-images/Grey.png) | ![Colour Off White](assets/images/readme-images/Off-white.png)
--- | --- | --- | ---
#EE8726 | #000000 | #535353 | #F6F3F2 

# Features


## Technologies Used

* HTML - For Structuring the site.
* CSS - For Styling the Site.
* Bootstrap - For Grid Layout & Components.
* Font Awesome - icons.
* Google Font - For two selected fonts.
* JQuery - For working with Burger menu in mobile view. 


## Testing


### Bugs Discovered

* Problem1 - I was unable to add a background video with a text overlay.
```
Banner with Video wasnt working
<div class=" section">
    <div class="video-container">
        <video autoplay muted>
            <source src="videos/coffee_bean6.mp4" type="video/mp4">
        </video> Help From W3school on video

        <div class="header-text">
            <section class="text-center header-text">
                <h1 class="title">FALL IN LOVE</h1>
                <h2 class="second-text">WITH THE TASTE OF OUR FRESH ROASTED COFFEE</h2>
                <button type="button" class="btn btn-outline-primary">VIEW FULL MENU</button>
            </section>
        </div>
    </div>
</div>
```
* Problem1 SOLVED - I eventaully came to the idea of converting the video into a lower res and cropped gif where I used it as a background image which worked out better as it lowered the size of the file.
```
    <div class="container-fluid img-container bg-opacity">
        <div class="row">
            <div class="col-12">
                <section class="text-center header-text">
                    <h1 class="title">FALL IN LOVE</h1>
                    <h2 class="second-text">WITH THE TASTE OF OUR FRESH ROASTED COFFEE</h2>
                    <a class="btn btn-outline-primary" href="ourmenu.html" role="button">VIEW FULL MENU</a>
                    
                </section>
            </div>
        </div>
    </div>

    .img-container {
        height: 100vh;
        background: url('../images/coffee-beans-BG.gif') rgba(0, 0, 0, .65)no-repeat bottom right fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
        background-blend-mode: multiply; /* Code From overflow*/
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
}
```

## Deployment




## CREDITS

### Content

https://www.codegrepper.com/code-examples/delphi/bootstrap+4+navbar+logo+left+menu+right

https://www.w3schools.com/howto/howto_css_fullscreen_video.asp

https://stackoverflow.com/questions/39819510/remove-an-object-when-on-mobile

### Media

https://pixabay.com/photos/various-nuts-almond-walnut-1766/

https://www.cleanpng.com/png-hazelnut-food-common-hazel-nutella-walnut-cream-281137/

https://www.cleanpng.com/png-red-velvet-cake-cheesecake-fudge-cake-dessert-choc-918683/

https://www.cleanpng.com/png-honey-bee-honeycomb-comb-honey-honey-141425/

https://www.pexels.com/photo/photo-of-spilled-coffee-beans-977878/

https://www.freepik.com/free-psd/coffee-cup-store-low-angle_11631353.htm#page=1&query=coffee%20logo%20mockup&position=1

https://www.pexels.com/photo/art-blur-cappuccino-close-up-302899/

https://www.pexels.com/photo/coffee-contact-email-hands-4831/

https://pixabay.com/photos/sandwich-appetizer-food-snack-dish-1238615/

https://www.freepik.com/free-psd/coffee-shop-premium-quality-board-mockup_3574877.htm

https://pixabay.com/photos/coffee-coffee-grinds-cafe-206142/