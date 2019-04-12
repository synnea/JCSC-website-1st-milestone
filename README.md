# Japanese Culture Social Club

Milestone Project: User-Centric Frontend Development - Code Institute

Ever been interested in learning how to say more than "Konnichiwa"? Want to understand the philosophy behind tea ceremony? Do you think samurai swords look really cool?

If you answered yes to any of these questions, the JSCS Berlin is there to serve your interests. 

We organize Japanese cultural events throughout the city of Berlin. Membership is free, and we offer a monthly meetup where you can come talk to like-minded people for absolutely free as well.
Other club events, of which there are several each month, are charged individually. 

Sign-up is risk-free, and you only pay for the events you actually attend.

Through our cooperation with our many Japanese partners, among them companies and artists, we help diversify our city and bring to it rich cultural content.


## UX

The website's target audience is anyone interested in Japanese culture in Berlin. The goal of the website is to increase the number of its members, and thus in time increase the number of events offered.

Membership is free, but the club makes money with each individual paid event. 

### Strategy Plane

On the strategy plane of UX, the following goals are most important:

| Objective         | Viability          | Feasibility |
| ----------------- |:------------------:| -----------:|
| increase members  | 5                  | 5           |
| inform fans       | 5                  | 5           |
| attract sponsors  | 5                  | 2           |

As can be seen from the matrix, the goals to **increase the number of new members* and *inform fans* are both doable and valuable, and should thus be prioritized. In contrast, attracting sponsors would be valuable, but requires  content that is currently out of the scope for this website.

Since the core audience can be assumed to be rather young, cosmopolitan, and hip, we will also need a modern design that ties in with the topic of the website. Modern Japanese pop culture should be included just as much as more traditional topics such as tea ceremony and samurai ethics.

### Scope Plane

With the goals overarching strategy set, next I decided upon the features.

Since users need to be enticed to sign up, a prominent **Join Me** button needs to be displayed. It was thus decided to feature the option to join the club very prominently on the landing page. In the context of this club, "membership" means being signed up to their email list.

Furthermore, the users need to be informed of what it is they are joining. Hence, the rest of the website should be dedicated to fulfill that need, by giving the user easily accessible information on what it is the club does, what the benefits of joining are, and what they can expect to gain from membership.

Using these realizations as a springboard, the following user stories were created:

1. As a first-time user, I want to find out what this website is about.
2. As a fan of Japanese culture, I want to quickly join this club.
3. As a user interested in Japanese culture, but unsure about the merits of joining a club, I want to find out what this club offers me.
4. As a user interested in Japanese, but unwilling to spend any money, I want to stay informed on upcoming events.

### Structure Plane

Next, I decided on the color palette. The landing page background came to me pretty early on in the conception process of this website, and it was from there that I decided on the color palette of the website, which would focus on white, black, and red. These colors are elegant and timeless and lend themselves well to a simple yet visually appealing UI.

Taking the concept of *content hinting* into account, it was also decided here that the front page would show the top of the following section to entice curiosity and get the user to scroll down the page.

In order to best address the user stories above, it was quickly decided that the website needed an **About** section, as well as an **Upcoming Events** and **Contacts** page. A single-page, scrollable website was decided on, in order to relay the information in a linear, logical manner, from About --> Upcoming Events --> Past Events --> Contact.

In this stage, the Information Architecture was also decided upon, with the decision to use Bootstrap cards for upcoming events and to embed YouTube videos and Spotify songs for the Past Event section.

The footer was decided to contain the JSCS logo (*Note: it currently can't be called a logo, as I didn't take the time to design one due to scope restraints, but the JSCS elements in the navbar and footer effectively function as if they were representations of a logo*), another join invitation (*Note: which was later scrapped*), and the social media links.

### Skeleton Plane

At this stage, I created mockups via Balsamiq. The Balsamiq file as well as a .pdf file generated from it are included in the project and can be accessed via assets/wireframes.

The original mockup shows several important differences to the finished product. Here are some of the most important differences, and why the finished product varies from the mockup:

* The original desing did not contain a "Past Events" section. This was included later to serve the technical requirement of including iframes in the website. I also realized it fulfilled a user need to get a better idea of offerings, and capture the younger segment better by including some "hip" Japanese music.
* The monthly meetup was originally given a lot more page real estate with its own distinct section. In the finished product, it is represented in a card, similar to all the other events. This was chosen for visual symmetry. Instead, in order to visually emphasize its uniqueness, it was given a green button that spells 'Free!'
* The footer originally contained an address and phone number. This was later removed. The reason for that is that the idea to include a .pdf brochure of upcoming events came later in the development process. Additionally, since our target is young and cosmopolitan, a phone number is less essential. Also, since JCSC doesn't have a fixed office building, an address was likewise judged superfluous.


### Surface Plane

Since the finished project is now accessible, I will skip over this section.

## Features

The website features a fully responsive navbar that collapses into a dropdown menu for mobile users.

The website features an overview of upcoming events. It also showcases past events via a YouTube video and 2 Spotify songs.

The website also contains two modals: one triggered by the "Join Me" button prominently displayed on the jumbotron, and one triggered by the "Send" button following the form in the Contact section.

The website currently *does not* contain any embedded maps; instead, img pictures were used as placeholders in the cards.

A downloadable .pdf is included in the footer.

### Existing Features

The navbar collapses at the top for mobile devices, allowing the user to access all parts of the website.

The website includes a callout button that takes them to a pop-up modal. By filling in their name and email address, they can easily get in touch with the club. The button signs the user up to the email list.

At the bottom of a page, there's a contact form that allows the user to get in touch with the club and opt in to the email list. It triggers a modal that thanks the user for signing up and affirming the receipt of the contact request.

### Future Features

The cards in the "Upcoming Events" section currently feature a screenshot of a Google Maps location. In a future rework of this project, I would like to embed an interactive map.

The "logo" in the navbar and footer is at present only the 












https://stackoverflow.com/questions/39031224/how-to-center-cards-in-bootstrap-4

https://www.w3schools.com/howto/howto_css_image_center.asp

https://stackoverflow.com/questions/22433616/how-can-i-align-youtube-embedded-video-in-the-center-in-bootstrap

https://blog.theodo.fr/2018/01/responsive-iframes-css-trick/

https://stackoverflow.com/questions/2570972/css-font-border

https://css-tricks.com/fun-viewport-units/

https://stackoverflow.com/questions/13648979/bootstrap-modal-immediately-disappearing

https://stackoverflow.com/questions/17756649/disable-the-horizontal-scroll

caught the fact that I've been developing from a desktop-first approach. fixed it with the cards and the cat background.

standardized heading style by using vh top and bottom, except for on the last item 

HTML validator tells me not to use fixed height and width with the Spotify plugins, but the Fiona Apple website begs to differ.







to-do: put button instead of free for monthly meetup card

change hover class of bottom JSCS