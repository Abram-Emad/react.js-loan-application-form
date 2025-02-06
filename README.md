# React.js Loan Application Form

A modern, responsive, and user-friendly loan application form built with React.js. This project simplifies the loan application process by breaking it down into manageable steps with real-time validation and a smooth user experience.

## Features

- **Multi-Step Form Navigation**  
  Break down the loan application into logical steps (Personal Details, Employment, Loan Details, Confirmation) for a guided user experience.

- **Real-Time Form Validation**  
  Instant validation with clear error messages for required fields, email formats, phone numbers, and numeric inputs.

- **Progress Indicator**  
  Visual progress bar showing the current step and overall completion status.

- **Responsive Design**  
  Mobile-first approach ensures seamless usage across devices (desktops, tablets, phones).

- **Data Review & Submission**  
  Final confirmation page to review entered data before submission, with a mock API call simulation.

- **State Management**  
  Efficient handling of form data and navigation state using React Hooks (`useState`, `useContext`).

## Technologies Used

- **React.js** - Core library for building the UI components.
- **React Router** - Navigation between form steps.
- **CSS Modules** - Scoped styling for components.
- **JavaScript (ES6+)** - Modern syntax and features.
- **HTML5** - Semantic markup structure.

## Installation

1. **Clone the Repository**
   bash
   git clone https://github.com/Abram-Emad/react.js-loan-application-form.git
   cd react.js-loan-application-form
   

2. **Install Dependencies**
   bash
   npm install
   

3. **Run the Development Server**
   bash
   npm start
   
   The app will open at `http://localhost:3000`.

## Usage

1. **Start the Application**  
   Fill out the form step-by-step after launching the development server.

2. **Navigate Through Steps**  
   Use "Next" and "Back" buttons to move between sections. The progress bar updates dynamically.

3. **Input Validation**  
   Required fields are marked with an asterisk (*). Errors display instantly if validation fails.

4. **Submit the Form**  
   Review all entered data on the confirmation page. Click "Submit" to simulate an API request.

## Project Structure

- plaintext
- src/
- ├── components/          # Reusable components (FormStep, InputField, ProgressBar)
- ├── contexts/            # React context for state management
- ├── pages/               # Form step components (Personal, Employment, Loan, Confirmation)
- ├── App.js               # Main component with routing
- ├── index.js             # Entry point
- └── styles/              # CSS modules for each component


## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a Pull Request.


## Contact

Abram Emad  
- GitHub: [@Abram-Emad](https://github.com/Abram-Emad)  

## Acknowledgments

- Inspired by modern web form best practices.
- Built with guidance from React.js documentation.
 
