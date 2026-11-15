Cloud hosted website (by Render) can be found here: https://infr3120u-assignment-ii.onrender.com/ 
Link to GitHub: https://github.com/alvin-li2/INFR3120U-Assignment-II

Public folder contains CSS in content subfolder, javascript in script subfolder, and images and videos under assets. Under assets, there are two different subfolders, for images and videos respectively.

Bootstrap was utilized for the navigation bar. 
Font Awesome is used in the navigation bar as well. Specifically, it is used for the emojis in front of all four navigation buttons (Home, About me, Projects, and Contact me.)

There are four routes used in index.js, which can be found under the "routes" folder.
First route is '/', this route acts as the home / landing page of the website.
Second route is '/aboutme', this leads to the about me section.
Third route is '/projects', which leads to my past projects 
Fourth route is '/contact', this leads to a form that can be filled out to contact me via email. 

While all four pages are separated using if statements, all four share a universal header and footer. The header is: <h1>Welcome to My <%= title %> Page</h1>, and the footer is <h1>My Github!: https://github.com/alvin-li2</h1> <h2>My LinkedIn: https://www.linkedin.com/in/alvin-li-6270b6384/</h2>. No matter what page is selected, both the header and footer will show.