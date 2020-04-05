## Assignment 1: Heuristic Evaluation

## Exploring Stories of Asian America

Chu Yin Wen | DH-150 | Spring 2020


### Severity Ratings in Heuristic Evaluation - [Nielson Norman Group](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)  
1 = Cosmetic problem only: need not be fixed unless extra time is available on project  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, so should be given high priority

## Website 1: [Virtual Asian American Art Museum](https://vaaam.tome.press/)

Motivation:

This was one of the few websites which shared my vision of giving voice to Asian American stories through a virtual museum. 
In particular, it provides rich context for each piece and focuses on the Asian American artist as an individual rather than just focusing on their art as pieces in a digital archive. 
It will serve as a reference for my final project, and I hope to use it as material for usability testing. 

Overall evaluation:

In general, the website offers a creative and modern take on an online museum. 
It is innovative in its aspirations, although its execution could be improved. 
This museum appears to be targeted to academic consumers, given the many citations and intellectual discussion of the theory and politics behind the art. 
Some basic usability heuristics were not considered, resulting in an aesthetically modern, yet confusing experience.

#### 1. Visibility of System Status 
* Immediately on landing on the home page, there is no text or content on the screen, but just a fullscreen image of a painting and a hamburger menu icon in the top left. Though it makes for a unique and creative opening for a digital museum, it is a little disorienting and could make the user wonder if the page has fully loaded. The user has to hover over the hamburger menu before seeing the title and description of the website. 
 **(3)**    
 
 ![homepage](/images/vaaam_homepage.png)
 
*Recommendation: Do not show the forwards and backwards buttons when the user hovers over the side menu to eliminate confusion. This way, users know that they cannot interact with the buttons while hovering over the side menu.*
  
* A forward and backwards navigation button both appear onscreen when the user hovers over the side menu. This suggests that the user can interact with these buttons while hovering over the menu. However, when the user tries to click them from here, the buttons disappear and the user is unable to navigate forwards/backwards. In order to advance or go back, the user must directly hover over the left or right arrows themselves (not while side menu is open).
**(3)**    
  
  ![navigation](/images/vaaam_menuLinks.png)
  
*Recommendation: Do not show the forwards and backwards buttons when the user hovers over the side menu to eliminate confusion. This way, users know that they cannot interact with the buttons while hovering over the side menu.*
  
#### 2. Match between system and the real world
* To navigate backwards and forwards, websites usually allow users to click a forwards/backwards button. However, on this site, users can navigate through the entire site by scrolling up and down or by clicking the forwards and backwards arrows. This does not match the user's initial spatial conception of the site map, as it is unintuitive to think that navigating backwards/forwards on the horizontal axis is equivalent to navigating up/down on the site's vertical axis.
**(3)**  

*You can scroll down or click the next arrow to get to the About page*
![scrolling navigation system](/images/vaaam_scrollingNav.png)
  
 *Recommendation: Either remove the forwards/backwards arrows that allow the user to move left and right, or remove the ability to scroll up and down to access the previous and next pages.*

* On the side menu, there are links labeled with names "Michiko Itatani" and "James Numata." Unless the user has already visited the site or knew of them beforehand, they would not know that these are the artists featured in the museum. The links are ambiguous and do not clearly communicate their purpose to the user.*
**(3)**  
  
  ![menu links](/images/vaaam_menuLinks.png)
  
 *Recommendation: Add a header in the menu that reads "Artist Collections" and include the links under this header.*
 
 #### 3. User control and freedom
 
 * There is no way to skip to a specific piece of art in the exhibit. The user must step through each screen. This is very cumbersome and drastically reduces the amount of user control and freedom.
 **(3)**
 
 *Recommendation: Add a menu that allows users to select which piece of art to view next.*
 
 * Because this site is focused around the narrative of an artist and the story behind the process of creating a piece, there are lengthy passages. Many photographs and related art pieces are buried among these passages, and there is no way to navigate directly to the visual content.
 **(3)**
 
 *Recommendation: Include an outline of the page at the top, which will allow users to get an overview of what the page contains.*
 
 #### 4. Consistency and standards
 * To open the side menu, the user must hover over the left side of the screen. They cannot open it by clicking the hamburger menu icon. To close it, the user can either stop hovering over it or click the hamburger menu icon to close it. This shows a lack of consistency in the way the user can interact with the same icon.
 **(2)**
 
 *Recommendation: Allow the user to click on the menu icon to open the menu. A click will result in the menu staying on screen regardless of where the user's cursor is, while just hovering over the menu will make the menu's visibility contingent on the position of the cursor.*
 
 * Some images on the site are embedded in the page alongside text, while others are hidden behind captions that toggle open. This does not appear to be systematically done, with no clear differences between the former and latter types of images.
 **(2)**
 
*Before toggle* ![toggled before](/images/vaam_beforeToggle.png) *After toggle* ![toggled after](/images/vaam_afterToggle.png) 
 
 *Recommendation: Keep consistency by embedding all of the images directly on the page and removing the need to toggle to view them.*
 
 #### 5. Error prevention
 
 * There is little user text input on this site, so there is not too much risk of the user making an error in submitting something. However, because of the confusing navigation layout, there is a possibility that users will accidentally scroll down and end up on the next page when their intention was to stay on the same page.
 **(2)**
 
 *Recommendation: Add in floating text that notifies you when scrolling down will take you to the next page.*
 
 #### 6. Recognition rather than recall
 
 * The side navigation menu disappears every time the user moves their mouse off of it. This menu is the only way to navigate the site, and having it continually appear and disappear can be jarring. The user cannot reference it without hovering over it. 
 **(2)**
 
 *Recommendation: Do not make the menu automatically disappear when the user hovers off of it. Instead, add in an exit button to allow users to click out of it manually.*
 
 * Similarly, there is a button labeled with the next page's title and an arrow indicating that the user should click on it to advance. When the user does not hover over it, the title disappears. This requires the user to recall the title of the next page to decide whether or not to advance.
 **(2)**
 
 *Recommendation: Keep the title visible in small text above the arrow, and do not make its visibility contingent on the user's hover.*
 
 #### 7. Flexibility and efficiency of use
 
 * There is no way for more experienced visitors of the site to filter art pieces by specific category, artist, or collection. All users can only step through page by page.
 **(3)**
 
 *Recommendation: Add a search feature or a menu that allows users to find a piece quickly by author, genre, or collection.*
 
 #### 8. Aesthetic and minimalist design
 * At first glance, the site is very aesthetically minimal and sophisticated. However, once the user hovers over the side menu, nearly all of the screen gets covered with navigation buttons and labels that have generous padding and a black background. 
 **(1)**
 
 *Recommendation: Do not make the labels of all navigations appear on hover. Instead, just make them either perpetually visible and non-obtrusive by removing the black background.*
 
 #### 9. Help users recognize, diagnose, and recover from errors
 
 * Under the "Selected Map of Exhibitions and Publications," there is an error loading the Google Map content. There is no explanation of why this error occurred nor how to address it. Additionally, the map is overlaid with text that says "For development purposes only." This is vague and out of context for users. There is no clear purpose for the map. The map is not a main feature of the site, but it is still distracting and takes up a large portion of the page. 
 **(2)**
 
 ![map error](/images/vaaam_mapError.png)
 
 *Recommendation: Remove the map completely, or replace it with a list of locations where the artist has exhibitions and publications.*
 
 * There are pages that are password protected. Given that the site is supposed to mimic a public museum, it seems odd to have any password protected exhibits. Even more so, there is no explanation as to why it is password protected. This may be off-putting to users.
 **(3)**
 
 ![password protected](/images/vaaam_password.png)
 
 *Recommendation: Hide password protected pages entirely, or add a description as to why these pages have been password protected.*
 
 #### 10. Help and documentation
 
 * Despite the rather unique layout and purpose of the site, there is no guide/onboarding process to help users become familiar with the site. As this is supposed to be a fully digital museum experience, it is important to guide the users through the process in a clear and well-documented way. The site does a poor job of this.
 **(3)**
 
 *Recommendation: Incorporate a walkthrough or onboarding screens to help the user understand the features of the site.*
 
