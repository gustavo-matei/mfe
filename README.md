# Microfrontends Project with Module Federation - README

This is a guide to understand the technologies and approaches used in the Microfrontends project, which employs the concept of **Module Federation**. The project has been divided into different packages for Authentication (Auth), Container, Dashboard, and Marketing functionalities. ReactJS was chosen to implement the Container, Auth, and Marketing, while the Dashboard was built with Vue.js. Additionally, route management was performed using both `browserhistory` and `memoryhistory`, ensuring a smooth navigation experience.

## Key Technologies

1. **ReactJS**: ReactJS was used to build the Authentication, Container, and Marketing modules. It allows creating reactive and dynamic user interfaces, essential for providing a high-quality user experience.

2. **Vue.js**: Vue.js was chosen to develop the Dashboard module. Its component-based approach and gentle learning curve make it an excellent choice for creating interactive and efficient interfaces.

3. **Module Federation**: The concept of Module Federation was employed to create a highly modular Microfrontends architecture. This allows each package to be developed independently while still being able to share resources and components among themselves.

## Routing and Navigation

Route management was handled carefully, employing both `browserhistory`  for user-friendly URLs and `memoryhistory` for internal communication between modules. This resulted in a cohesive and efficient navigation experience.

## Deployment and Continuous Integration

The project was deployed using GitHub Actions, leveraging AWS services such as CloudFront and S3 to host the modules. This allows potential users to access the modules quickly and reliably, ensuring continuous and effective delivery.

## Independent and Decoupled Packages

Each module (Auth, Container, Dashboard, and Marketing) was developed as an independent package, with its own dependencies and clear responsibilities. This results in a highly decoupled system, enabling efficient development, maintenance, and scalability of each module.

## How to Run the Project

1. Clone this repository to your local machine
2. Navigate to the project directory, and for each package (Auth, Container, Dashboard, and Marketing), run `npm install` or `yarn` to install the dependencies.
3. To start each module, use commands like `npm run start` or `yarn start`.
4. Open your browser and access the URLs corresponding to the different modules to see them in action.

## Customization and Expansion

Feel free to explore, customize, and expand this project according to your specific needs. The Microfrontends architecture offers flexibility and scalability, and the ongoing pursuit of best development practices will be crucial for the continuous success of this project.
