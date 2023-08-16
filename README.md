# GeekGather - Dev Community Web Application

GeekGather is a dynamic and engaging developer community web application built with Next.js, Clerk for authentication, MongoDB for database management, and Tailwind CSS for stylish and responsive user interfaces. This README provides comprehensive information on how to set up, configure, and contribute to the GeekGather project.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

GeekGather aims to provide developers with a platform to connect, collaborate, and learn from each other. The application fosters a vibrant community where members can share their knowledge, discuss trending technologies, and participate in coding challenges. With a focus on user-friendly design and seamless authentication, GeekGather offers a superior experience for both beginners and experienced developers.

## Features

- User authentication powered by Clerk
- Seamless integration with MongoDB for efficient data management
- Interactive user interface using Tailwind CSS
- Engaging community forums for discussions
- Upvoting and commenting on posts
- Code snippet sharing
- User profiles with activity tracking
- Real-time notifications
- Moderation tools for administrators

## Getting Started

Follow these steps to set up the GeekGather project on your local machine.

### Prerequisites

- Node.js (version >= 14)
- MongoDB installed and running
- Clerk account for authentication setup

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/krishcodz/geekgather.git
   cd geekgather
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Configuration

1. Create a `.env.local` file in the root directory and add the following environment variables:

   ```plaintext
   NEXT_PUBLIC_CLERK_FRONTEND_API_KEY=your-clerk-frontend-api-key
   NEXT_PUBLIC_MONGODB_URI=your-mongodb-uri
   NEXT_PUBLIC_MONGODB_DB=your-mongodb-database-name
   ```

2. Customize other configuration settings in `config.js` as needed.

## Usage

1. Start the development server:

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000` to access GeekGather.

## Contributing

We welcome contributions from the community to enhance GeekGather. To contribute, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your commit message here"
   ```

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request on the main repository.

## License

GeekGather is released under the [MIT License](LICENSE).

---

Feel free to explore, contribute, and make GeekGather your own! If you encounter any issues or have questions, please reach out to us via the Issues section or contact the project maintainers.
