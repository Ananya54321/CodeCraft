
# Code Craft

**Code Craft** is a real-time collaborative code editor designed for seamless teamwork and efficient coding. Created for the BitnBuild Hackathon on February 10, 2024, by GDSC CVR.

**Team Name:** 404Found  
**Team Members:**
- [Rishi Kumar Gade](https://github.com/RishiKumarGade)
- [Ananya Pappula](https://github.com/Ananya54321)
- [Sneha Muthyala](https://github.com/SnehaMuthyala)
- [Dhruv S Shah](https://github.com/TheSpecsGuy17)

## Tech Stack

- **Frontend:** HTML, CSS, Tailwind CSS, React
- **Backend:** Next.js, Socket.io, Node.js, TypeScript
- **Database:** MongoDB

## Installation

1. **Clone the Repository** 📥

    ```bash
    git clone https://github.com/RishiKumarGade/CodeCraft.git
    ```

2. **Install Dependencies** 🛠️

    - For the client:
      ```bash
      cd codeeditor
      npm install
      ```

    - For the server:
      ```bash
      cd server
      npm install
      ```

3. **Run the Application** 🚀

    - For the client:
      ```bash
      npm run dev
      ```
    - For the server:
      ```bash
      npm start
      ```

## Features

**Home Page**:
- Central hub for navigation and overview of the features 🏠

**Login and Authentication**:
- Custom authentication with secure password hashing 🔐
- Single user sign-in functionality ✅

**Offline Code Editor**:
- Edit code even when offline 📝

**Custom Avatars**:
- Choose your avatar to represent your activity in the room 🌟

**Room Page**:
- **Room Creation**: Generate a unique room code to share with friends 🔑
- **Room Joining**: Enter a valid room code to access the room 🚪
- **Your Rooms**: Log of created rooms with stored session data 📚

**Toast Messages**:
- Indicate success & failure for account creation, login, logout, room creation, and room exiting 👏

**Collaborative Code Editor**:
- **Code Editor**:
  - Real-time code updates ⚡
  - Syntax highlighting based on file extension 🌈
  - Avatar indicators for user activity 🚶‍♂️🚶‍♀️
  - Locking protocol to prevent conflicts during simultaneous editing 🔒
- **File System**:
  - Real-time creation and deletion of files 📂
  - Detect file type based on extension 📄
- **Chat Section**:
  - Display online users with avatars 🗨️
  - Real-time chatting within the room 💬
- **Session Management**:
  - Automatically redirect users back to their previous room if they leave abruptly due to network issues or closing the tab 🔗

**Contact Us Page**:
- Submit queries directly to us through the Contact Us page 📬

**About Us Page**:
- Short description of the project and our objectives 📖

## Screenshots

![Home Page](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/66ba081c-443d-4726-b0a6-87f9f347ad28)
![Room Page](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/5fe9b9c5-b348-4a89-8ea6-7e37e788d021)
![Code Editor](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/e93263e9-9c91-43d2-a34c-9f6dfb110d02)
![File System](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/7555c70c-7baf-454a-97f4-51e48fe6bed2)
![Chat Section](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/e1db2075-06dd-4f1e-b352-b9b5543edaa1)
![About Us](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/d8eab00c-d5f9-4f39-86e5-79d27c4c7eb4)
![Contact Us](https://github.com/RishiKumarGade/CodeCraft/assets/116152722/ce4ea639-d044-4f3a-8c22-705d7fe404e8)

## Credits

If you find this project useful and incorporate it into your own work, please provide proper attribution. Acknowledge the effort and contributions of the developers by linking back to the original repository.

**How to Give Credits:**

Include a visible and clear credit to the original project with a link to [Code Craft on GitHub](https://github.com/RishiKumarGade/CodeCraft).
