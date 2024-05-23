# Full Stack Job Portal

Full Stack Job Portal is a comprehensive web application designed to connect job seekers with employers. Built using modern web technologies, it provides a platform for users to search for jobs, apply online, and manage applications, while employers can post job listings and manage applicants.

## Table of Contents 📚

- [Introduction](#introduction)
- [Features](#features)
- [Screenshot](#screenshot)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction🚀

Full Stack Job Portal is a dynamic and responsive job portal application that allows users to search for jobs and apply online. Employers can post job listings, view applications, and manage their listings effectively.

## Features🛠️

- **User Authentication**: Secure user registration and login for job seekers and employers.
- **Job Search**: Advanced search functionality to find jobs based on various criteria.
- **Job Applications**: Apply for jobs online and track application status.
- **Job Listings Management**: Employers can post, edit, and delete job listings.
- **Applicant Tracking**: Employers can view and manage applications.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## Screenshot📷

![Full Stack Job Portal](https://github.com/BoddepallyVenkatesh06/Full-Stack-Job-Portal/blob/main/Screenshot.png)

## Technologies Used🖥️

- **Frontend**: React.js, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Docker, Kubernetes

## Getting Started🎯

### Prerequisites📋

Before you begin, ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- MongoDB
- Docker (optional, for containerization)
- Kubernetes (optional, for orchestration)

### Installation⚙️

1. Clone the repository:

```bash
git clone https://github.com/BoddepallyVenkatesh06/Full-Stack-Job-Portal.git
cd full-stack-job-portal
```

2. Install frontend dependencies:

```bash
cd client
npm install
```

3. Install backend dependencies:

```bash
cd ../server
npm install
```

## Usage📈

### Running the Application

1. Start the MongoDB server (if not using Docker):

```bash
mongod
```

2. Start the backend server:

```bash
cd server
npm start
```

3. Start the frontend development server:

```bash
cd ../client
npm start
```

### Building for Production

1. Build the frontend for production:

```bash
cd client
npm run build
```

2. Start the backend server in production mode:

```bash
cd ../server
NODE_ENV=production npm start
```

### Docker Deployment

1. Build and run the Docker containers:

```bash
docker-compose up --build
```

## Contributing❤️

Contributions are welcome! If you'd like to contribute to Full Stack Job Portal, please follow these steps:

1. Fork the project.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License📝

```
MIT License

© 2024 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
