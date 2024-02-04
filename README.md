# Online Coding Web Application

Welcome to our Online Coding Web Application, where mentors and students can collaborate in real-time on JavaScript code. This project is designed to facilitate remote coding sessions, allowing mentors like Tom to share code blocks and guide their mentees, like Josh.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ShovalElhaiany/online-coding-app.git
   ```

2. Navigate to the server directory:

   ```bash
   cd online-coding-app/server/
   ```

3. Run the server:

   ```bash
   ./run.ps1
   ```

4. Move back to the parent directory:

   ```bash
   cd ../
   ```

5. Navigate to the client directory:

   ```bash
   cd online-coding-app/client/
   ```

6. Install client dependencies:

   ```bash
   npm install
   ```

7. Run the client:

   ```bash
   ./run.ps1
   ```

## Usage

### Lobby Page

1. Open your web browser and go to [http://localhost:3000](http://localhost:3000).
2. Click on any code block to view its details and start a coding session.

### Code Block Page

1. The first user to open the code block page is considered the mentor.
2. The mentor will see the selected code block in read-only mode.
3. Students will see the code block with the ability to make real-time changes.
5. Code changes are displayed instantly using Socket communication.