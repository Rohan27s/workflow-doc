---
sidebar_position: 1
---

# Services

**1. Enketo Core**

Enketo Core is a JavaScript library that enables the creation of interactive web forms that can be filled out by users. It provides a lightweight and flexible framework for rendering forms in web browsers. Enketo Core's capabilities include rendering complex form structures, handling form logic and calculations, managing data bindings, and supporting a wide range of form widgets.

#### Key Features:

Interactive Forms: Enketo Core empowers web developers to create interactive and dynamic forms that adapt to user inputs.
Cross-Platform: It is designed to work across various devices and browsers, ensuring a consistent form-filling experience.
Calculation Support: Enketo Core supports complex calculations and formula-based interactions within forms.
Offline Capabilities: Forms created with Enketo Core can be used offline, providing valuable functionality in areas with limited connectivity.

**2. Enketo Express**

Enketo Express is a server-side solution that integrates Enketo Core to facilitate form rendering, data collection, and submission processing. It provides endpoints for rendering forms, saving form submissions, and managing data storage. Enketo Express serves as a middleware between Enketo Core and your application's backend.

#### Key Features:


Form Rendering: Enketo Express generates HTML forms using Enketo Core, making it easy to render complex forms on the client side.
Submission Handling: It receives form submissions, validates data, and stores the data securely.
Security: Enketo Express ensures data security by handling user authentication and authorization for form submissions.
Customization: It offers configuration options to customize form rendering, submission handling, and other behaviors.

**3. Centro**

Centro is a web service that provides a central repository for managing forms and data collected through Enketo-based forms. It acts as a data hub, allowing you to collect, store, analyze, and visualize form data from different sources. Centro simplifies data management and analysis, enabling efficient decision-making based on the collected data.

#### Key Features:


Data Collection: Centro collects form submissions from various instances of Enketo-based forms, regardless of their location.
Central Repository: It stores form data securely in a central database, making it easy to manage and access.
Data Analysis: Centro provides tools for analyzing and visualizing collected data, helping users derive insights and trends.
Data Sharing: It allows sharing data with authorized users, enabling collaboration and knowledge sharing.

**4. Form Manager**

Form Manager is a component responsible for managing forms and their lifecycle in your workflow application. It interacts with Enketo Express and Centro to create, update, and retire forms. Form Manager streamlines the process of designing, deploying, and maintaining forms within your application.

##### Key Features:


Form Lifecycle: Form Manager handles form creation, modification, versioning, and retirement.
Integration with Enketo Express: It communicates with Enketo Express to configure form rendering and submission handling.
Data Management: Form Manager coordinates with Centro to manage form data collection, storage, and analysis.
User Permissions: It manages user access to forms, ensuring that only authorized users can create or modify forms.