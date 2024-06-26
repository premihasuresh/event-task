# event-task
index.html:

This HTML document creates a web page layout for displaying a list of events. It begins with standard HTML5 structure and includes a reference to an external CSS file named event-home.css.

The first section is a search bar (<section class="search">) with an input field for users to search for specific events. The placeholder text "SEARCH EVENTS" guides users on how to use the search feature.

The second section (<section id="events">) contains a series of event cards, each representing a different event. Each event card consists of a title (<h2>), an image (<img>), and information about the event such as the date, available seats, and a button for booking or indicating if the event is sold out. The information is structured within <div> elements with appropriate classes for styling.

event.css

The #events selector sets a yellow background color for the section containing the events.

The .event class defines the appearance of each event card, including a black background with a red border, rounded corners, and spacing margins. Event images are styled to have a specific width, margin, and a black border for visual appeal. Buttons within the event cards have a wheat-colored background, red text, and a hover effect that changes their background and text color to red and wheat, respectively, on hover.

The .event-name class centers the event names and sets their color to wheat, enhancing readability. The .event-content class floats the content within event cards to the right, adds padding for spacing, and adjusts margins for a visually appealing layout.