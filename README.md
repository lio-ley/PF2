README:
    This is a responsive web page with the following features:

    1. Profile Information: Displays personal and course profile information at the top of the page, including the user's name, sex, address, course, school, semester, subject, and instructor details.
    
    2. **Responsive Background Color: 
       - On mobile devices (screen width < 600px), the background color is blue.
       - On tablets (screen width between 600px and 991px), the background color is green.
       - On desktop devices (screen width ≥ 992px), the background color is orange.
       The background color updates dynamically based on the screen size and is also responsive to window resizing events.
       
    3. Sidebar Navigation: Includes links to different sections (Home, Settings). The sidebar is sticky and remains visible on the page as the user scrolls.
    
    4. Page Information and Controls (in Settings):
       - Displays the current URL, hostname, and page title.
       - Includes a button that prompts the user to input a new title for the page and updates the `<title>` dynamically.
    
    5. Browser Navigation Controls: 
       - Buttons are included to reload the page, navigate back, navigate forward, and redirect the user to a new URL using the `location` and `history` objects.

    6. JavaScript Features: 
       - Event listeners on page load and window resize to adjust the background color dynamically.
       - Functions for page navigation and content updates.
