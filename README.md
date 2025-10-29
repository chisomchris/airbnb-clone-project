# AirBnB Clone Project

## Project Overview

The AirBnB Clone Project is a full-stack web application inspired by the popular accommodation booking platform Airbnb.
The goal of this project is to design and build a functional clone that allows users to browse available properties, view detailed information, and complete bookings through an intuitive and responsive interface.

### Project Goals

- Develop a scalable full-stack application using modern technologies.

- Build a responsive and user-friendly UI for both desktop and mobile.

- Implement secure user authentication and data management.

- Practice team collaboration using Git and GitHub.

- Gain experience with frontend, backend, and database integration.

### Tech Stack
| Layer |	Technologies|
| :-------- | :---------- |
| Frontend |	HTML, CSS, JavaScript, Nextjs|
| Backend |	Node.js / Express |
| Database | MySQL or PostgreSQL |
| Version Control |	Git & GitHub |
| Design Tool	| Figma |
| Deployment |	Netlify / Vercel |

### Getting Started

1. Clone the repository:

    ```bash
     git clone https://github.com/<your-username>/airbnb-clone-project.git
    ```

2. Navigate into the folder:

    ```bash
    cd airbnb-clone-project
    ```

3. Install dependencies (if applicable):

    ```bash
    npm install
    ```

4. Run the development server:

    ```bash
    npm start
    ```

### Author

Christian Ezeanyaeche

## UI/UX Design Planning

### Design Goals

The primary goal of the UI/UX design is to create an intuitive, consistent, and engaging experience for users browsing and booking properties. The design should reflect simplicity and elegance while maintaining Airbnb’s signature look and feel.

**Key goals include**:

- Ensuring seamless navigation across all pages

- Maintaining visual consistency (colors, typography, spacing)

- Optimizing for speed and accessibility

- Prioritizing mobile-first responsiveness

### Key Features

- **Property Search and Filtering** - Users can search for properties by location, price, and availability.

- **Detailed Property View** - Display images, amenities, reviews, and booking form.

- **User Authentication** - Allow users to register, log in, and manage their bookings.

- **Secure Checkout Process** - Simplified payment and confirmation workflow.

- **Favorites and Wishlists** - Enable users to save properties for later.

### Primary Pages
| Page	| Description |
| :-------- | :-------- |
| Home - Property Listing View | Displays available properties in a grid layout with filtering options. Enables users to search for properties and locations |
| Listing Detailed View | Shows detailed property information, images, amenities, and booking form. |
| Simple Checkout View | Streamlined booking and payment confirmation interface for selected property |

### Importance of User-Friendly Design

A user-friendly design is essential in a booking system because it directly impacts how efficiently and comfortably users can complete their booking journey. When users can easily search, compare, and book accommodations without confusion or frustration, they are more likely to trust the platform and return for future use.

A well-designed interface reduces friction by offering clear navigation, intuitive layouts, and consistent visual elements. Features such as prominent call-to-action buttons, organized property listings, and responsive mobile views help users accomplish tasks quickly and confidently. Additionally, incorporating accessibility principles ensures that users of all abilities can interact with the system effectively.

Ultimately, a user-friendly booking system enhances customer satisfaction, increases conversion rates, and builds brand loyalty. It transforms a complex process -like browsing, filtering, and confirming bookings- into a smooth and enjoyable experience, aligning both business goals and user needs.


### Figma Design Reference

All wireframes and prototypes are designed in Figma.
You can view the design file here:
[View Project Airbnb Design on Figma](https://www.figma.com/design/E2BRqdPcKkrnX6hLGPto8Z/Project-Airbnb?node-id=1-4&p=f)

This design file includes both low-fidelity wireframes (for structure and layout) and high-fidelity prototypes (for visuals and interactivity).

#### Color Styles

| Purpose | Hex Code |
| :----- | :-------: |
| Primary	| #FF5A5F |
| Secondary	| #008489 |
| Background | #FFFFFF |
| Text	| #222222 |
| Secondary Text | #717171 |

#### Typography

| Type	| Font | Weight	| Size |
| :----- | :-----: | :----: | :------ |
| Primary Font | Circular | Medium (500) | 16px |
| Heading 1 | Circular |	Bold (700) | 32px |
| Heading 2 | Circular |	Bold (700) | 24px |
| Secondary Text	| Circular | Book (400)	| 14px |

### Importance of Identifying Design Properties

Understanding and documenting design properties - such as colors, typography, spacing, and components - is essential in maintaining a consistent and user-friendly interface.

**Here’s why it matters:**

- **Consistency**: Ensures all pages and components look cohesive and follow the same visual rules.

- **Efficiency**: Helps designers and developers collaborate effectively by using a shared design language.

- **Scalability**: Makes it easier to extend the design system for future updates or new features.

- **User Experience**: A consistent and visually balanced interface improves usability and trust.

By clearly identifying these design properties in the mockup, the development team can accurately translate the Figma design into code while preserving the intended aesthetic and functionality.

## Project Roles and Responsibilities

A successful project depends on well-defined roles and clear communication between team members.

Each role below contributes uniquely to the success of the AirBnB Clone project, ensuring smooth collaboration across design, development, testing, and deployment phases.

| Role | Responsibilities | Contribution to Success |
| :----- | :----- | :------ |
| Project Manager |	Oversees the project timeline, resource allocation, and communication between team members. | Ensures all milestones are met and risks are managed.	Keeps the team aligned with project goals and deadlines, ensuring smooth coordination. |
| Frontend Developers | Build the user interface using React (or similar framework), implement responsive layouts, and connect frontend components to backend APIs. |	Deliver an engaging, fast, and user-friendly interface for end-users. |
| Backend Developers | Develop RESTful APIs, manage the database schema, and ensure secure data flow between the server and client. Handle business logic and authentication. |	Provide a reliable and scalable foundation that powers the core application functions. |
| Designers (UI/UX) | Create wireframes, prototypes, and visual designs in Figma. Maintain color schemes, typography, and component consistency.| Ensure a visually appealing and intuitive experience for users. |
| QA/Testers | Develop test cases, perform manual and automated testing, and verify that all features meet requirements before deployment. | Guarantee quality by identifying and resolving bugs early in the development process. |
| DevOps Engineers | Manage the deployment process, configure CI/CD pipelines, and maintain server infrastructure and version control workflows. | Ensure continuous integration, smooth deployments, and stable system performance. |
|Product Owner | Define product requirements, prioritize features, and act as the liaison between stakeholders and the development team. | Aligns the project outcomes with business goals and user needs. |
| Scrum Master | Facilitate Agile processes, conduct sprint meetings, track progress, and remove blockers for the team.	| Keeps the development process efficient, organized, and transparent. |

### Summary

Clearly defining roles and responsibilities ensures accountability, efficiency, and collaboration.
Each role contributes to building a robust, user-friendly, and maintainable application - from conceptual design to final deployment.

## UI Component Patterns

UI components form the core building blocks of the AirBnB Clone interface.
Each component is modular, reusable, and responsive, ensuring consistency and efficiency across all pages of the application.

Below is a breakdown of the planned UI components, their purpose, and design considerations.

1. **Navbar** (NavigationBar)

    Purpose: Provides consistent navigation across all pages.
    Elements: Logo, Search Bar, Navigation Links, and User Profile Menu.
    Design Goal: Maintain a clean, intuitive layout that adapts to mobile and desktop screens.
    Example Use: Displayed at the top of every page for quick access to Home, Listings, and Profile.

2. **Footer** (SiteFooter)
    
    Purpose: Displays secondary navigation and company information.
    Elements: About, Help, Terms, Social Media Links, and Copyright Info.
    Design Goal: Keep the layout minimal and accessible while maintaining visual harmony with the rest of the site.
    Example Use: Appears on all pages to provide users with additional navigation and credibility.

3. **PropertyCard**
    
    Purpose: Showcases individual property listings detail in a card.
    Elements: Image, Property Name, Location, Price per Night, Rating, and Favorite Button.
    Design Goal: Create an engaging, compact card that clearly communicates key details.
    Example Use: Used in the Property Listing page to display multiple listings.

4. **Testimonial**
    
    Purpose: Highlights user reviews and feedback to build trust.
    Elements: User Avatar, Name, Rating, Review Text, and Decorative Elements.
    Design Goal: Encourage credibility and social proof through clean, readable layouts.
    Example Use: Featured on the property detail page to display guest testimonials.

5. **PillWrapper**

    Purpose: A non-semantic pill-shaped container used for grouping small UI elements or tags.
    Elements: Customizable text or icons within rounded borders.
    Design Goal: Add subtle emphasis or categorization (e.g., “Verified Host”, “Top Rated”).
    Example Use: Used inside Property Cards or filter chips.

6. **Button**

    Purpose: A generic button used for primary or secondary actions, has multiple variants that define its appearence.
    Elements: Text Label, Optional Icon.
    Design Goal: Maintain visual consistency with all buttons on the page.
    Example Use: Commonly used for filters (e.g., “Entire Place”, “Pet Friendly”) or calls-to-action.

7. **NavIconButton**

    Purpose: A navigation button with an icon and label, displayed vertically.
    Elements: Icon, Text (below icon).
    Design Goal: Provide simple, touch-friendly navigation.
    Example Use: Used in mobile bottom navigation or quick-access sections.

8. **CheckoutForm**
    
    Purpose: Handles booking confirmation, payment details, and order summary.
    Elements: Input Fields, Summary Section, Confirmation Button.
    Design Goal: Ensure a seamless and secure checkout flow with clear validation messages.
    Example Use: Used on the Checkout Page to finalize reservations.

9. **HomeBanner**

    Purpose: Hero section that introduces the platform and encourages exploration.
    Elements: Headline, Background Image.
    Design Goal: Capture user attention immediately with vibrant visuals and concise messaging.
    Example Use: Placed at the top of the homepage to attract and guide visitors.
