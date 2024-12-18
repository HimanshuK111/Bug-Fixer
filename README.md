# Bug Fixer Application

## Overview
The **Bug Fixer** application is a ticket management system built with React. It allows users to create, edit, and sort tickets based on their priority. This tool leverages the `useReducer` hook for state management and provides modular components for efficient ticket handling.

## Features
- **Create New Tickets**: Add a ticket with details such as title, description, and priority.  
- **Edit Tickets**: Modify existing ticket information directly in the app.  
- **Sort by Priority**: Arrange tickets in High to Low or Low to High priority for better organization.  

## Technologies Used
- **Frontend**: React.js, JavaScript  
- **Styling**: CSS  

## File Structure
- `App.js`: The main application component that manages state and renders the TicketForm and TicketList components.  
- `components/TicketForm.js`: A component for creating and editing tickets.  
- `components/TicketList.js`: A component that displays the list of tickets.  
- `reducers/ticketReducer.js`: A reducer function that handles state changes for tickets.  
- `utilities/sortingUtilities.js`: A utility function for sorting tickets based on user preferences.  
- `App.css` and `styles.css`: CSS files for styling the application.  

## Prerequisites
- **Node.js** (v14 or later)  
- **npm** (v6 or later)

## How to Run the Application

1. **Clone the Repository**:  
    ```bash
   git clone <repository-url>
   cd bug-fixer

2. **Install Dependencies and Start the Application**:  
    ```bash
   npm install && npm start

3. **View the Application**:  
    ```bash
   Open your browser and navigate to http://localhost:3000.

## Usage


- Use the form to add new tickets by providing the required details.
- Select a sorting preference (High to Low or Low to High) from the dropdown to organize the tickets.
- View all tickets in the list below the form.


## Screenshots


"Below is a screenshot showcasing the application's user interface with the ticket form and ticket list displayed."


![Screenshot 2024-12-18 012240](https://github.com/user-attachments/assets/04612b15-1567-42d6-9d00-585f2f10751b)


![Screenshot 2024-12-18 125639](https://github.com/user-attachments/assets/485f8337-01d1-447b-b5f3-b62abde44e9e)

## Contributing

 We welcome contributions! Here’s how you can help:  
  1. Fork the repository.  
  2. Create a new branch for your feature or bug fix.  
  3. Commit your changes and push them to your fork.  
  4. Submit a pull request for review.

## License

This project is open-source and available under the MIT License. See the  [LICENSE](https://choosealicense.com/licenses/mit/) file for details.
