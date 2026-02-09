# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

Zeyue Xu(zx1612): https://github.com/zeyuexu123

Samay Dhawan: https://github.com/samaythe1

Zhihui Chen(zc3716): https://github.com/Zhi-Hui-C

Aryaman Nagpal (an3782): https://github.com/aryamann04

## Stakeholders

### End-User (NYU Student)
The end-user is a college student and local resident. The user occasionally brings friends and family that do not reside in New York City to Washington Square. They value convenience, speed, and affordability, and often make food decisions spontaneously between classes or work sessions. Because food trucks are mobile by nature, the user struggles to reliably find accurate and up-to-date information about what options are nearby and available at any given moment, especially later at night. 

#### Goals and Needs
- **Quickly discover nearby food options.** The user wants a fast, location-based way to see which food trucks are currently operating and serving near them without needing to walk around or search multiple different platforms. This is especially important when they have limited time between classes and/or events. 
- **Make informed decisions before committing time or money.** The user needs access to menus and prices (and ideally photos and reviews) so that they can judge whether a food truck is worth visiting quickly. 
- **Avoid unnecessary delays.** The user needs accurate information about opening hours, current status, and busy times (e.g. line length or wait time) so that they do not arrive at a closed truck or face unexpectedly long lines. 
- **Personalized food discovery.** The user wants to be able to filter by cuisine type, dietary preferences, ratings, or favorites so that the app surfaces food options that match their tastes rather than overwhelming them with arbitrary choices. 

#### Problems and Frustrations
- **Unreliable and outdated information.** The user notes that food trucks frequently move or change hours, so existing platforms often list incorrect locations or schedules, leading to wasted time and frustration. 
- **Fragmented sources of information.** The user indicates that a lot of the time, reviews may be on one platform while the menu and prices are on another, forcing the user to search several different platforms just to decide where to go. 
- **Uncertainty about food quality.** Without consistent reviews or photos, the user feels like choosing a food truck is a gamble, which discourages them from trying new food trucks. 
- **Lack of situational awareness when choosing a truck.** Even when the user knows the location and menu of a food truck, they are unaware of the current wait times and popularity. This leads to frustration when they arrive to find long lines or overcrowding especially when in between classes. 

### Food-Truck Vendor 
This stakeholder is a vendor of a food truck that operates near Washington Square and relies on foot traffic from students, locals, and tourists. They manage many responsibilities simultaneously (e.g. food preparation, taking orders, logistics, etc.) which leaves little time for maintaining a strong online presence. Because locations and hours can change very frequently, the vendor feels that it is difficult to communicate accurate information to their potential customers. Their primary needs are visibility, efficiency, and control over how their business is represented to the public. 

#### Goals and Needs 
- **Increase visibility to nearby customers.** The vendor wants customers in the immediate area to easily find their truck when it is open without relying solely on social media or word of mouth. 
- **Simple and fast information updates.** The vendor needs an easy way to update location, hours, menu items, and prices on the fly. These updates ideally should require minimal effort. 
- **Attract and retain new customers.** The vendor wants to showcase photos, post daily specials/deals, and highlight positive reviews in order to draw in traffic. 
- **Manage reputation and customer feedback.** The vendor needs the ability to view and respond to reviews so that they can address concerns and provide strong customer service. 

#### Problems and Frustrations
- **Customers arriving based on outdated information.** The vendor is frustrated when customers complain or leave negative reviews because the truck moved locations or closed earlier than expected. 
- **Fragmented online platforms.** Maintaining accurate information on multiple platforms (e.g. Instagram, Yelp, Google Maps etc.) is time consuming and inevitably leads to inaccurate/inconsistent information across platforms. 
- **Limited control over public perception.** The vendor feels discouraged when outdated or unfair reviews continue to affect their reputation without a clear way to respond or correct information. 
- **Time constraints during operating hours.** The vendor has very little time to manage complex digital tools while actively taking and serving orders, which makes overly complicated and unintuitive platforms highly impractical. 

## Product Vision Statement

Our app aims to help students, locals, and visitors easily discover, track, and evaluate food trucks around Washington Square by providing accurate locations, photos, menus and community-driven ratings in one centralized platform.

## User Requirements

### 1. End-Users (Students, Locals, Visitors)
- As an end-user, I want to see nearby food trucks on a map so that I can quickly find food near me.
- As an end-user, I want to search for food trucks by name so that I can find my favorite vendors.
- As an end-user, I want to filter trucks by cuisine so that I can find food I like.
- As an end-user, I want to view menus and prices so that I can decide what to order.
- As an end-user, I want to see ratings and reviews so that I can choose high-quality food.
- As an end-user, I want to leave a rating after visiting a truck so that I can share my experience.
- As an end-user, I want to write reviews so that I can help other users.
- As an end-user, I want to upload photos of my food so that others can see what it looks like.
- As an end-user, I want to save favorite food trucks so that I can find them easily later.
- As an end-user, I want to see opening hours so that I know when a truck is available.
- As an end-user, I want to view busy times so that I can avoid long lines.
- As an end-user, I want to report incorrect information so that the app stays accurate.
- As an end-user, I want to sort trucks by rating so that I can find the best ones.
- As an end-user, I want to create an account so that my reviews are saved.
- As an end-user, I want to edit or delete my reviews so that I can fix mistakes.

### 2. Vendor Users (Food Truck Owners)

- As a vendor, I want to create a business profile so that customers can find my truck.
- As a vendor, I want to update my location in real time so that users know where I am.
- As a vendor, I want to upload my menu so that customers can see my food.
- As a vendor, I want to update prices so that my information is accurate.
- As a vendor, I want to post daily specials so that I can attract more customers.
- As a vendor, I want to upload photos of my food so that my truck looks appealing.
- As a vendor, I want to set my operating hours so that users know when I’m open.
- As a vendor, I want to mark my truck as opening/closed so that users are not misled.
- As a vendor, I want to respond to reviews so that I can communicate with customers.
- As a vendor, I want to view my ratings so that I can improve my service.

### 3. Administrators (App owner, development team)

- As an administrator, I want to manage user accounts so that the system stays secure.
- As an administrator, I want to approve new vendor registrations so that only valid trucks join.
- As an administrator, I want to remove fraudulent vendors so that users are protected.
- As an administrator, I want to configure app-wide settings so that the platform runs smoothly.
- As an administrator, I want to assign moderator roles so that content is managed properly.
- As an administrator, I want to monitor system performance so that downtime is minimized.
- As an administrator, I want to back up data so that information is not lost.
- As an administrator, I want to view usage statistics so that I can improve the app.
- As an administrator, I want to enforce community guidelines so that standards are maintained.
- As an administrator, I want to review system logs so that technical issues can be diagnosed.
- As an administrator, I want to investigate and resolve usability issues so that users can use the app smoothly.


## Activity Diagrams

![<# alt text #>](../Container-5.png "Container-5.png")
![<# alt text #>](../Container-4.png "Container-4.png")
![<# alt text #>](../Container-3.png "Container-3.png")
![<# alt text #>](../Container-2.png "Container-2.png")
![<# alt text #>](../Container-1.png "Container-1.png")
![<# alt text #>](../Container.png "Container.png")


## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.
