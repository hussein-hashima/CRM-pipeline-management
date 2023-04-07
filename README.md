# CRM-pipeline-management
A CRM pipeline is a visual representation of the sales process, divided into multiple stages. Each stage represents a particular step in the process, such as Lead, Contacted, Qualified, Proposal, Closed Won, and Closed Lost. A CRM pipeline allows sales teams to track and manage their leads and opportunities more efficiently.
CRM Pipeline Management Application
This is a pipeline management application for managing deals in a CRM system. The application is built using Angular and is a single-page application (SPA). It allows users to manage deals in multiple pipeline stages and provides a visual representation of the sales process.

## Getting Started
To get started with the application, follow these steps:

1- Clone the repository to your local machine.  
2- Run `npm install` to install the required dependencies.  
3- Run `ng serve` to start the development server.  
4- Navigate to `http://localhost:4200/ `to view the application in your browser.  
Features  
## The application has the following features:

-Fetching Deals Data: The application fetches deals data from a public CRM Contacts API endpoint. The API endpoint used for this project is:
`https://my-json-server.typicode.com/mabukoush1/contacts/db`.      
-Displaying Deals Data: The deals data is displayed in a visual pipeline divided into the following stages: Potential Value, Focus, Contact Made, Offer Sent, and Getting Ready. Each deal is displayed as a card with its respective fields:   
`id, first_name, last_name, email, phone, company, status, date, probability_status, and state`.   
-Drag and Drop Functionality: Users can drag and drop deals between the different stages of the pipeline. This allows for easy management of deals and helps track their progress through the sales process.   
-Updating Deal Status: The application updates the deal status when it is moved to a different stage in the pipeline. This allows for easy tracking of deals and ensures that the sales team is always up-to-date on their progress.   
-Search Functionality: The application provides a search functionality to search for contacts based on first name, last name, or email. This allows users to quickly find the deals they are looking for without having to scroll through the entire pipeline.    
-Responsive Design: The application is responsive and works on both desktop and mobile devices. This ensures that users can access the application from anywhere and on any device.    
## Conclusion
This CRM Pipeline Management Application provides an easy and intuitive way to manage deals in a CRM system. With its drag and drop functionality, visual pipeline, and search functionality, it helps sales teams track their leads and opportunities more efficiently.
## Contributing
If you would like to contribute to this project, please follow these steps:

1- Fork the repository and create a new branch for your changes.   
2- Make your changes and commit them with clear, concise commit messages.   
3- Push your changes to your forked repository and submit a pull request to the original repository.   
4- Wait for a maintainer to review your changes and merge them into the main branch.   
## License
 This project is licensed under the MIT License. See the [LICENSE](docs/3rdpartylicenses.txt) file for details.
