# Smart India Hackathon Workshop

# Date : 15/05/2024

## Register Number : 212223220046

## Name : KEERTHIVASAN S

## Problem Title
E-Waste Facility Locator

## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.

## Problem Creater's Organization
Ministry of Environment

## Idea

The proposed solution is a comprehensive web platform named "GreenRecycle" that helps users locate the nearest e-waste collection and recycling facilities. The platform aims to educate users about the environmental and health impacts of improper e-waste disposal and incentivize proper disposal through a points-based reward system.

## Key Features

**Locator Service:**

1. Interactive Map: Users can input their location to find the nearest e-waste collection and recycling facilities.
2. Filter Options: Filters based on types of devices accepted, operating hours, and additional services (e.g., pick-up services).
3. Facility Information: Detailed information about each facility, including contact details, accepted e-waste types, and user reviews.

**Educational Pop-Ups:**

1. Component Information: Pop-ups providing detailed information on harmful components found in e-waste, such as lead, mercury, and cadmium.
2. Environmental Impact: Information on how these components affect the environment if not disposed of properly.
3. Health Impact: Information on the health risks associated with improper e-waste disposal.

**Incentive System:**

1. Device Input and Assessment: Users can input the model of their old device to receive an estimated value based on the precious metals and recyclable components.
2. Credit Points: Users earn points relative to the estimated value of the metals recovered from their device when they dispose of it at a registered facility.
3. Rewards: Points can be redeemed for rewards such as discounts on new electronics, donations to environmental charities, or cash-back options.

## Proposed Solution / Architecture Diagram

**1. Interactive Map and Facility Locator** : The core feature of GreenRecycle is an interactive map that allows users to find e-waste collection points based on their location. This feature will include

1. Geolocation Services: Automatically detect user location to show nearby facilities.
2. Search and Filters: Users can search by zip code or city and filter results by criteria such as device type, facility services, and operational hours.
3. Facility Profiles: Each facility will have a profile page with detailed information, including accepted items, operational guidelines, user reviews, and contact information.

**2. Educational Pop-Ups** : Education is key to changing behavior. GreenRecycle will use engaging pop-ups to inform users

1. Contextual Information: When a user inputs a device, pop-ups will provide relevant information about the hazardous components in that specific device.
2. Interactive Content: Infographics, videos, and articles about the environmental and health impacts of improper e-waste disposal.
3. Quiz and Certification: Users can take quizzes after reading the educational material to earn additional points and badges.

**3. Incentive System** : To motivate users to dispose of e-waste correctly, GreenRecycle will implement a robust incentive system

1. Device Model Input: Users can input their device model to get an estimated value of recoverable materials.
2. Credit Point System: Points are awarded based on the estimated value and actual recycling of the device. Points can be tracked in the user’s account.
3. Redeemable Rewards: Points can be redeemed for various rewards, including discounts on new electronics, donations to environmental causes, or even small monetary incentives.

**Technical Implementation**

1. Frontend Development: Using React for a dynamic and responsive user interface.
2. Backend Development: Node.js with Express for server-side operations, MongoDB for data storage, and APIs for geolocation and facility data integration.
3. Third-party Integrations: Integration with Google Maps API for the locator service and educational content providers for environmental and health information.

**User Experience Flow**

1. Accessing the Site: Users visit GreenRecycle and can immediately see an interactive map with their current location.
2. Finding a Facility: Users enter their device type and location, and the map updates with nearby facilities.
3. Learning: As users search, educational pop-ups provide information about the environmental impact of their specific e-waste.
4. Inputting Device Model: Users input their device model to see potential recoverable materials and earn points.
5. Earning and Redeeming Points: Users drop off their e-waste at a facility and earn points, which they can track and redeem on the platform.  

## Flowchart

![flowchart](https://github.com/ikeerthivasanswaminathan/SIHPS/assets/148937372/a6fa578e-6c1b-43ee-8b32-8a4d2c70e400)

## Use Cases

![usecaseflowchart](https://github.com/ikeerthivasanswaminathan/SIHPS/assets/148937372/c483ddee-7c66-45c2-b7e8-1ff8af8909dc)

## Technology Stack

**Frontend**

1. HTML: For structuring the web pages and content.
2. CSS: For styling the web pages with modern design principles.
3. JavaScript (Vanilla JS): For client-side scripting to handle dynamic content and user interactions.
4. Bootstrap: For responsive design and pre-built components to speed up UI development.
5. Fetch API: For making HTTP requests to interact with the backend services and APIs.

**Backend**

1. Python: A versatile and widely-used programming language.
2. Django: A high-level Python web framework that encourages rapid development and clean, pragmatic design.

**APIs and Third-party Services**

1. Google Maps API: For the locator service, providing map functionalities, geocoding, and place searches.
2. Geolocation API: To detect and use user location data for showing nearby e-waste facilities.
3. Educational Content API: Integration with educational content providers to fetch relevant articles, infographics, and videos about e-waste components and impacts.

## Dependencies

HTML, CSS, JavaScript, Bootstrap, Fetch API, Python, Django, Google Maps, Geolocation API, Cloud Platform, Mapping Services, Data Collection, Development Cost.
