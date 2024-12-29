# pechacks2024

# Accessible Job Portal for Disabled Individuals

## Overview
This project is an accessible job portal tailored for disabled individuals. It offers an inclusive platform where job seekers and companies can connect efficiently. The portal integrates various accessibility features to ensure a seamless experience for users with disabilities.

---

## Features

### General Features
- **Login and Registration**:
  - Separate login and registration options for job seekers and companies.
- **Job Management**:
  - Companies can post job listings.
  - Job seekers can browse and apply for jobs.

### Accessibility Features
- **Google Translate**:
  - Multi-language support for better usability across diverse linguistic backgrounds.
- **Screen Reader**:
  - Reads out text on the screen to assist visually impaired users.
- **High Contrast and Saturation**:
  - Enhances visual clarity for users with low vision.
- **Cursor Resizing**:
  - Allows users to enlarge the cursor for better visibility.
- **Text Spacing**:
  - Adjustable spacing to improve readability for users with cognitive disabilities.

### Backend
- **Firebase Integration**:
  - Secure and scalable backend for storing user profiles, job postings, and application data.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-portal-disabled.git
   ```
2. Navigate to the project directory:
   ```bash
   cd job-portal-disabled
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up Firebase:
   - Create a Firebase project and configure the credentials.
   - Update the `firebaseConfig` in the project.
5. Start the development server:
   ```bash
   npm start
   ```

---

## Usage

1. **For Job Seekers**:
   - Register and log in.
   - Browse available job listings.
   - Apply for desired jobs.
2. **For Companies**:
   - Register and log in.
   - Post job opportunities.
   - Review applications from job seekers.
3. **Accessibility Options**:
   - Use the toolbar to enable/disable features like high contrast, cursor resizing, and text spacing.
   - Select preferred language from the Google Translate dropdown.

---

## Technologies Used

- **Frontend**: React.js
- **Backend**: Firebase
- **Accessibility Libraries**: ARIA roles, screen reader integrations
- **Additional Tools**: Google Translate API

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

- Accessibility inspiration from WCAG guidelines.
- Firebase for seamless backend integration.
- Google for Translate API support.

---

## Contact

For inquiries or support, please email [support@jobportal.com](mailto:support@jobportal.com).
