# 🧑‍🎓 Dynamic Student Community

Dynamic Student Community is a secure and collaborative platform designed to connect students within a college or university. It enables users to share announcements, participate in polls, raise complaints, and contribute study materials — all through a centralized system. With an intuitive interface and robust backend, it supports seamless interaction and admin-level moderation.

## 🚀 Features

- 📝 **User Signup & Login**: Students can register and securely log in to access the community.
- 📢 **Announcements & Discussions**: Share news, updates, and open discussions with peers.
- 📊 **Poll Creation & Voting**: Users can create polls and vote on various academic and social topics.
- 📚 **Study Material Sharing**: Upload and access helpful study resources.
- 🙋‍♂️ **Complaint Submission**: Raise concerns and suggestions for better campus life.
- 🔐 **HOTP-based Secure Authentication**: One-Time Password via email ensures safe login.
- 🧑‍💼 **Admin Dashboard**: Admins can manage users, posts, and platform activities.
- 📱 **Responsive UI**: Built with React and Bootstrap for a smooth experience across devices.


## 🛠️ Tech Stack

- **Frontend**: React, Bootstrap, JavaScript
- **Backend**: Java (Jakarta EE Servlets)
- **Database**: MySQL / PostgreSQL
- **Authentication**: Email-based HOTP, Secure Sessions
- **Tools**: Eclipse IDE, HTML, CSS

## 📝 How It Works

1. Students register and log in using their email and a secure HOTP.
2. After login, users can create different types of posts: announcements, polls, complaints, or study material links.
3. Admins have additional access to manage user accounts and moderate content.
4. All posts are visible in the main feed, categorized for easy access.
5. Polls support real-time voting and results.


### 📌 Backend Setup

```bash
# Clone the repository
git clone https://github.com/AkshithaArtham/Dynamic_student_community.git

# Import into Eclipse IDE as a Java EE project
# Set up your MySQL/PostgreSQL DB and configure DBUtil.java with your credentials

# Deploy to Tomcat/Glassfish server and run

### 📌 Frontend Setup

# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Run the development server
npm start

