# youtube

https://tanishka-khamesara.github.io/youtube/youtube.html



![Screenshot (53)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/52a0fc53-83b9-4b00-b9ba-15a2bd438fbb)
![Screenshot (54)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/5b53593e-466b-4089-83cc-49920e77b7c9)
![Screenshot (55)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/8e1eaba2-e3aa-4eca-8c70-c42b13cb3bc5)
![Screenshot (56)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/69842e31-f263-4e82-af16-00cda6a115c8)
![Screenshot (57)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/09f58cb5-4dad-4212-9e1b-d0608b546384)
![Screenshot (58)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/ef8ebca4-10d5-46b1-93ef-96cdf6fc7804)
![Screenshot (59)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/bc0cd8f4-69a8-484d-afcd-f51543ac1c72)
![Screenshot (60)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/d78113cb-0a40-4f45-89f7-a41f1f68bb34)
![Screenshot (61)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/9ac59a98-1645-4a93-83e4-5f106c73693a)
![Screenshot (62)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/ee1ea552-c32f-4ca9-97f7-eff41d95711f)
![Screenshot (63)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/613ddec1-3539-4ca6-b1ed-75c549b2720e)
![Screenshot (64)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/ae043f2c-fa75-40f9-b1ac-70dbbd1c190e)
![Screenshot (65)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/27fbc61c-f85c-4f0a-b05d-f3fad4b81238)

html explaination->
1.<!DOCTYPE html>: This declaration defines the document type and version of HTML being used. In this case, it's HTML5.

2.<html lang="en">: This is the opening tag for the HTML document. The lang="en" attribute specifies that the content is in the English language.

3.<head>: This section contains meta-information about the web page, such as character encoding, viewport settings, and the page title.

4.<meta charset="UTF-8">: This meta tag specifies that the character encoding for the page is UTF-8, which supports a wide range of characters and symbols.

5.<meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag sets the viewport properties to ensure that the web page is displayed properly on various devices. It makes the page responsive.

6.<title>Document</title>: This sets the title of the web page, which appears in the browser's title bar or tab.

7.<link href="./style.css" rel="stylesheet">: This line includes an external CSS file named "style.css" to apply styling to the HTML elements.

8.<body>: This is the main content of the web page.

9.<header class="header">: This section represents the header of the page, which typically contains a navigation menu and a logo.

10.<div class="youtube">: This is a container for the YouTube-like logo and menu icon.

11.<div class="search">: This container holds a search input field and a search button.

12.<div class="links">: This container contains icons representing various navigation links, such as search, video camera, apps, notifications, and user account.

13.<div class="container">: This container wraps the main content of the page, including the sidebar and video recommendations.

14.<aside class="aside">: This represents the sidebar section.

15.<div class="categories">: This section contains categories for navigation.

16.<div class="category">: Each category is represented by a container that includes an icon and a label. Categories include Home, Trending, Subscriptions, Library, History, Your Videos, Watch Later, and Liked Videos.
17.<hr />: This horizontal line is used to separate the categories.

18.<main class="main">: This represents the main content area of the page.

19.<h1>Recommended</h1>: This is a heading indicating that the following content consists of recommended videos.

20.<div class="videos">: This section contains a list of video thumbnails and details. Each video is represented by a container that includes a thumbnail image, uploader's icon, video title, uploader's name, and view count.

21.The code includes placeholder images (<img>) for the video thumbnails and uploader icons. These should be replaced with actual URLs to images.

22.The code uses Material Icons for various icons throughout the page, which are represented by <span> elements with the class material-icons.

23.The code includes some placeholder text for video titles, uploader names, and view counts. These should also be replaced with actual data when implementing the website.

24.In summary, this code provides the structure for a web page that resembles a video-sharing platform like YouTube. It includes placeholders for content and styling, which can be customized and filled with real data to create a functional website.


CSS -->
![Screenshot (66)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/6b40c364-4e35-4bb8-9d3e-e2c61f8e8763)
![Screenshot (67)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/928a6917-19ad-4a57-90a6-8b7fd6c5db2f)
![Screenshot (68)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/2ee421ab-6a0f-475b-b7e3-cb72826cb80f)
![Screenshot (69)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/64a689d8-5ecd-40da-851d-8a652890ba18)
![Screenshot (70)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/09bd95a1-b331-4674-8252-02e3c67ffefd)
![Screenshot (71)](https://github.com/Tanishka-khamesara/youtube/assets/127411985/1e3b9001-bdc4-4e02-ba81-51d4f187d532)
css Explaination->
1.@import './header.css';, @import './aside.css';, @import './main.css';: These lines import three external CSS files named "header.css," "aside.css," and "main.css." These files likely contain additional styles for specific sections of the web page, such as the header, sidebar (aside), and main content.

2.*: This selector applies the following styles to all elements on the page.

3.margin: 0;: Sets the margin of all elements to 0.
4.padding: 0;: Sets the padding of all elements to 0.
5.box-sizing: border-box;: Makes sure that the width and height of an element include its padding and border, not just its content.
6.@font-face: This block defines a custom font named 'Material Icons' for displaying icon fonts. It specifies the font's source URL and various font properties.

7..material-icons: This selector applies styles to elements with the class "material-icons," which is used for displaying icon fonts. It sets the font family, size, line height, and other font-related properties to render the icons correctly.

8..icons: This selector applies styles to elements with the class "icons," which are likely used for icons in the header and sidebar. It sets the color for these icons to #606060 (a shade of gray).

9..container: Styles the container for the main content. It makes it a flex container, sets its height to fill the viewport minus 70px (likely to accommodate the header), and hides overflow content.

10..header: Styles the header section, which contains the logo, search bar, and navigation icons. It sets its height, padding, and aligns its content horizontally.

11..youtube: Styles the container for the YouTube logo and menu icon.
12..search: Styles the search bar, making it a flex container and setting its border.
13..search input: Styles the search input field, including its width, padding, and border.
14..search button: Styles the search button.
15..aside: Styles the sidebar section on the left side of the page. It sets its background color, width, and enables scrolling if its content exceeds the height of the sidebar.

16..categories: Styles the container for the navigation categories within the sidebar.
17..category: Styles each category within the sidebar, including padding and alignment.
18..category span:not(.icons): Styles the text within each category.
19..aside::-webkit-scrollbar: Styles the scrollbar within the sidebar. In this case, it is set to display: none, which hides the scrollbar in WebKit browsers (like Chrome and Safari).

20.hr: Styles horizontal lines (likely used to separate categories), setting their height and background color.

21.h1: Styles the heading "Recommended" in the main content area. It sets the font size, margin, and text color.

22..main: Styles the main content area to have a background color, padding, and a border at the top. It also enables scrolling if the content exceeds the height of the container.

23..videos: Styles the container for video recommendations. It arranges the videos in a flexible layout with spacing.
24..video: Styles individual video containers within the recommendations. It sets their width and margin.

25..thumb: Styles the video thumbnails to cover the entire container.

26..uploader: Styles uploader icons with width, height, object-fit, border radius, and margin.

27..details: Styles the container for video details, arranging them in a flex layout.

28..text: Styles the text details of each video, arranging them in a column layout.

29..text h3: Styles the video title with font size, line height, and margin.

30..text a, span: Styles links and spans within the text with text decoration, font size, and color.

In summary, this CSS code provides styling for various components of a web page that simulates a video-sharing platform like YouTube. It defines fonts, colors, layouts, and other visual aspects to create the desired appearance for the page. Additional styles might be included in the imported CSS files for specific sections of the page, as indicated by the import statements at the beginning of the code.
