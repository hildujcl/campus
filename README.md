CampusConnect 🎓

CampusConnect is a student community web application built with Next.js. It helps students discover campus events, explore learning resources, read announcements, and create events of their own.

The project focuses on creating a simple, responsive, and user-friendly experience for connecting students with campus activities.

✨ Features

Student Authentication: Sign-up and sign-in pages for the student experience.

Dashboard: A central place for students to access campus activities and resources.

Student Profile: A page for student profile information.

Campus Events: Browse events, view event details, and access event-related information.

Create Events: A page for creating campus events.

Announcements: View important campus updates.

Learning Resources: Browse educational materials and submit resource access requests.

Resource Request Management: Admins can review student requests and approve or reject them.

Student Report: Students can request a report generated as a PDF from CSV data after approval.

Admin Dashboard: A separate area for managing resource requests.

Announcement Management: An admin page for managing campus announcements.

API Routes: Includes event-related API functionality and a health-check endpoint.

🛠️ Technologies Used

- Next.js with the App Router
- React
- JavaScript (JSX)
- Tailwind CSS
- Browser Local Storage
- Git and GitHub
- Vercel for deployment

🚀 Getting Started

Prerequisites

- Node.js
- npm
- Git

Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hildujcl/campus.git
   ```


2. Open the project folder:

   ```bash
   cd campusconnect
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build the Project

To check whether the application builds successfully, run:

bash
npm run build


 💾 Data Storage

CampusConnect currently uses browser Local Storage for demo account information, session data, and newly created events. Sample events, resources, and announcements are also provided by the project.

Because Local Storage is browser-specific, the data is not shared across users or devices. Clearing browser storage may remove saved demo data.

🔐 Authentication and Security

The current sign-up and sign-in functionality is intended for demonstration and coursework purposes. Account information is stored in Local Storage, so this implementation is **not secure production authentication**.

A future version could use a secure authentication provider, server-side authorization, and a database.

 ⚠️ Current Limitations

- No backend database is connected.
- Demo account and event data are stored locally in the browser.
- Users do not share newly created events across different devices.
- Authentication is not suitable for real user accounts.
- Some displayed content is based on sample data.

🔮 Future Improvements

- Integrate a database for persistent, shared data.
- Implement secure authentication and authorization.
- Add event registration and attendance tracking.
- Allow students to edit and delete their own events.
- Add event search, filtering, and categories.
- Improve accessibility and automated testing.

 🌐 Links

- **GitHub Repository:** https://github.com/hildujcl/campus
- **Live Application:** Add your deployed Vercel URL here after deployment.

👩‍💻 Author

**Hildana Asfaw**
Full Stack Developer

 📄 License

This project was developed for educational and portfolio purposes.