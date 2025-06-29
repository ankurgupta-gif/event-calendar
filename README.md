# Dynamic Event Calendar App

## Features

- **Calendar View**: Displays a grid for the current month with aligned days. Navigate between months using "Previous" and "Next" buttons.
- **View Modes**: Switch between month, week, and day views to manage events.
- **Event Management**: Add, edit, and delete events with specific details (name, time, description, and type).
- **Event Type Color Coding**: Events are color-coded based on type (Work, Personal, Others).
- **Event List**: Lists all events for the selected day in a modal or side panel.
- **Persistent Storage**: Events are saved in localStorage to persist even after refreshing the page.
- **Responsive UI**: The app is responsive and works well on different screen sizes.
- **UI Design**: Developed using **shadcn** components for a clean and modern look. Highlights the current day and the selected day.
- **Complex Logic**:
  - Handles month transitions (e.g., from January to February).
  - Prevents overlapping events by validating time slots.

## Installation

To run the app locally:

1. Clone the repository to your local machine:  
   `git clone <repository-url>`  

2. Navigate to the project directory:  
   `cd <project-directory>`  

3. Install the required dependencies:  
   `npm install`  

4. Start the development server:  
   `npm start`  

5. Open your browser and go to `http://localhost:3000` to view the application.



## Code Highlights

- Built using React functional components and hooks like `useState` and `useEffect`.
- Implements calendar logic manually without relying on external libraries.
- Features a modular, clean, and maintainable code structure.




