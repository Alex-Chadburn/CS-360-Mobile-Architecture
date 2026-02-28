# CS‑360 Mobile Architecture Reflection

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The application was developed as a lightweight inventory management tool that enables users to add, update, and remove items while tracking their quantities. Its primary purpose was to give users a simple and reliable way to monitor items they have on hand. By focusing on essential CRUD functionality, the app addressed the need for an accessible and efficient system for organizing and maintaining personal or small‑scale inventory records.

## What screens and features were necessary to support user needs and produce a user‑centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app required only two main screens to meet user needs: a login screen for authentication and a primary interface for interacting with the inventory database. The user interface was intentionally minimalistic to promote clarity and reduce cognitive load. Each component was positioned and labeled to help users understand available actions without confusion. This straightforward design approach contributed to the overall usability and success of the interface.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My coding approach emphasized modularity and reuse. Although not strictly inheritance, I created shared helper functions and XML resources within the com.cs360project package to maintain consistency and reduce redundancy. This approach made the codebase easier to manage and update. Similar strategies can be applied in future projects to support scalability, improve readability, and make development more accessible across multiple components.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Testing was performed using the Android Studio emulator, which allowed me to simulate user interactions and identify issues throughout development. This iterative testing process was essential because it revealed several points where the app did not behave as expected. These findings reinforced the importance of continuous testing and validation, especially when ensuring that the implementation aligns with project requirements.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

Although the initial plan appeared straightforward, one unexpected challenge involved separating the user interface from the underlying functional elements. To address this, I created an additional XML layout containing the specific buttons and components needed for each data entry. This separation allowed the interface and logic to evolve independently, reducing the risk of unintended interactions and improving maintainability.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful in applying my understanding of Android hierarchy and resource management. I consistently used appropriate resource files, followed best practices such as using start and end instead of left and right, and made informed adjustments to ensure the app functioned correctly. This attention to detail demonstrated both technical competence and a strong understanding of platform guidelines.
