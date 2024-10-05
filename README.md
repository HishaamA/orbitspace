# OrbitSpace
Quakespace revolutionises the mapping of moonquakes with an immersive view of the map itself. From ring mapping to height maps, this project has it all.

## About
Originally created for the NASA Space Apps Hackathon held in 2024.

For more info, visit the team page:
https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/orbitspace/

Try out the orrery:
https://orbitspace.ampiere.co

## High-Level Summary
We developed an interactive orrery web app that visualizes celestial bodies, including planets, Near-Earth Objects, and Potentially Hazardous Asteroids. Our app provides real-time data on orbital characteristics, rise and set times, and visibility, adjusted for the user’s location. Users can explore the solar system at both exaggerated and true scales, with detailed information for each body, including links to educational resources. By combining accurate data with an intuitive interface, the app enhances public understanding of astronomy, making space exploration accessible and engaging for all.

## What exactly does it do?
Our interactive orrery web app provides a 3D model of the solar system, allowing users to explore celestial bodies like planets, Near-Earth Asteroids, Comets, and Potentially Hazardous Asteroids. It offers real-time data, including orbital characteristics, rise and set times, and horizon coordinates (altitude/azimuth), tailored to the user's location. The app also includes background stars and links to educational resources like Wikipedia for deeper learning.

## How does it work?
OrbitSpace operates by integrating several key components:

- Users can zoom in and out, switching between an exaggerated solar system view and a true-scale planetary system view.
- Celestial bodies larger than 1 km in radius are searchable and provide real-time data.
- The app retrieves live ephemerides and astronomical data through APIs, while users can adjust variables like location (latitude/longitude), time, and particle count for performance.

Overall, OrbitSpace combines the power of data, AI assistance, and immersive technologies to provide users with a rich and educational solar system exploration experience.

![orrery](https://assets.spaceappschallenge.org/media/images/Screenshot_2024-10-05_140537.width-1024.png)

## What benefits does it have?
OrrerySpace offers several benefits:

- Educational: The app offers detailed astronomical insights, making complex data easily understandable for students, educators, and enthusiasts.
- Interactive Exploration: Real-time tracking of celestial bodies and dynamic zoom features bring the solar system to life, enhancing engagement.
- Accessibility: The app provides both live data and links to external resources, merging interactive learning with research capabilities.

![image](https://github.com/user-attachments/assets/7fe46254-3217-46b6-9cb9-d9829a3a07ac)


## What do you hope to achieve?
We aim to create an accessible and educational tool that makes space exploration engaging for users of all backgrounds. By providing real-time data and interactive features, we hope to inspire curiosity about astronomy, raise awareness of potentially hazardous asteroids, and encourage learning about the solar system in a fun, dynamic way. Ultimately, we want to bridge the gap between complex astronomical data and user-friendly experiences, fostering a greater appreciation for space science.

## What tools, coding languages, hardware, or software did you use to develop your project?
We have used a variety of tools in order to cater up a highly-immersive experience. The list of programmes are as follows:

1. HTML:

HTML provides the foundational structure of OrbitSpace, organizing content and ensuring that all elements, such as headers, buttons, and data displays, are properly defined and accessible. This semantic structure enhances usability

2. CSS:

CSS is utilized to style the application, creating a visually appealing and responsive interface. It allows us to define layouts, color schemes, and typography, ensuring a seamless user experience across devices. CSS animations further enhance interactivity, making transitions smooth and engaging.

3. jQuery:

jQuery simplifies DOM manipulation and event handling, enabling us to create dynamic interactions without extensive coding. It allows for easy implementation of features like click events, animations, and AJAX calls, enhancing user engagement by providing real-time updates and smooth interactions.

4. JavaScript:

JavaScript serves as the backbone of OrbitSpace, powering all interactive features and app logic. It enables real-time data fetching from NASA APIs, manages user input, and controls the 3D rendering of celestial bodies. 

# Tools Used:
- GitHub
- Webstorm
- Visual Studio Code
- Microsoft Office
- Mozilla Developer Tools
- Adobe Illustrator
- Claude 3.5 Sonnet

# Use of Artificial Intelligence
- Visualization Optimization: AI is employed to optimize 3D visualizations, ensuring smooth rendering and efficient performance, even when displaying complex orbital mechanics.
- Creative Content with Claude 3.0: We utilized Claude 3.0 to enrich our app’s educational material and providing users with a unique artistic experience that complements their exploration of the cosmos.
- Code Assistance with GitHub Copilot: We utilized GitHub Copilot to streamline the development process, leveraging AI-powered code suggestions to enhance coding efficiency, reduce errors, and accelerate feature implementation in OrbitSpace.

# Space Agency Data
- https://ssd.jpl.nasa.gov/planets/approx_pos.html
- https://ssd.jpl.nasa.gov/tools/sbdb_query
- https://github.com/nasa/mission-viz
- https://nasa.github.io/mission-viz/RMarkdown/ontology_based_orrery_generated_from_R_code.html
- https://eyes.nasa.gov/apps/asteroids/#/home

# Reference
- https://api.jquery.com/
- https://science.nasa.gov/solar-system/
- https://www.javascript.com/
- https://web.dev/learn/css


