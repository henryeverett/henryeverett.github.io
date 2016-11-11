---
published: true
---

I started at Happiour nearly two years ago. I picked up the responsibility for design and development of the iOS app from a 3rd party agency. After spending time with the app and learning its goals and its priorities, I set about deciding how it should evolve as a product. Most of my decisions around the product were focussed on crystallising the core user journey through the app.  In this post I'll examine the major steps we took and the thought that went into them.

### Version 1.x
![happiour_1_shots.png]({{site.baseurl}}/happiour_1_shots.png)
The first version implemented the initial vision of the product. The List View (left) focussed heavily on the brand logos of our partners, with 5 tabs in the Tab Bar representing Schedule, Map, Search, Messages and Profile. The Offer View (right) featured the details of the offer, followed by a map, with the redemption button sticking to the base of the screen. Tapping the button would reveal a barcode inline with the rest of the content.

### Version 2.0
![happiour_2_0_shots.png]({{site.baseurl}}/happiour_2_0_shots.png)
Version 2 saw the app built from the ground up in Swift, featuring bigger bolder elements and fonts with more emphasis on the important information. The tab bar was reduced from five tabs down to three: Search, Schedule and Profile. The other two tabs were consolidated into other parts of the app. The map was combined with the Search View and messages were moved to the Offer View.

Location and time-based information was segregated in the Offer View and the barcode was presented on a modal 'Coupon' view to give the affordance of a real coupon. Terms and conditions were hidden to free up space and new sharing features were added which were better suited to the type of communication channels our users preferred.

### Version 2.1
![happiour_2_1_shots.png]({{site.baseurl}}/happiour_2_1_shots.png)
Version 2.1 featured a redesign of the Offer View, keeping the parts that worked best from versions 1 and 2.0 and presenting the information in a clearer hierarchy. Favouriting and sharing took stronger positions, photos were expanded and logos minimised to put the offer iself front-and-centre. The redemption button was stickied to the bottom of the screen and the coupon was expanded to include new sharing options and the offer details.

![happiour_2_1_shots_search.png]({{site.baseurl}}/happiour_2_1_shots_search.png)

This version also added advanced search controls as our users were asking for a way to find offers that were starting on a certain day or at a certain place.

### Version 2.2
![happiour_2_2_shots.png]({{site.baseurl}}/happiour_2_2_shots.png)
Launched recently, version 2.2 focussed on the discovery aspect of the app. I realised that the advanced search feature that was launched in version 2.1 wasn't working. Users weren't able to find the controls and they were too complex for the context in which they would be used. We had come up with a technical-focussed solution based on our previous experience with advanced search rather than a user-focussed one. That was a mistake.

Version 2.2 fixed that by breaking the advanced search into two simple buttons on the list view. One to set the date and one to set the location. Now users could quickly filter the results in a couple of taps without having to do any searching through the app. The controls were much more intuitive and accessible.

The offer cells got a make over too, becoming photo-centric and removing uneccesary brand logos. The new style promotes the content of the offer rather than the brand itself to help users discover the best deal and drive them to try new places.

This was a process of streamlining the user experience by placing the core journey front-and-centre. To come to these decisions you have to take a step back from the details of the app and think hard about that journey. It's hard but putting yourself in the user's shoes and asking 'What do I want to do when I open this app?'. From there you can tailor the features to make that goal as simple as possible. If you find yourself wanting to add tooltips or a tutorial, you've already failed. The interface should be intuitive enough that the user doesn't need instruction.
