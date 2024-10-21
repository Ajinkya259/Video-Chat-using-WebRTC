## Omegle clone using WebRTC (p2p)


# Omegle Clone Using WebRTC

This project is an Omegle-like clone that enables anonymous real-time video and audio communication between users through WebRTC. It uses WebSockets for signaling and connection establishment, allowing users to connect seamlessly without the need for an external server for media streaming.

## Features
- **Real-time communication:** Video and audio chat between peers using WebRTC.
- **Peer-to-peer connection:** No media server required as WebRTC directly connects the users.
- **Anonymous chat:** Users are randomly matched with others for a spontaneous chat.
- **Signaling server:** Utilizes WebSockets for exchanging connection information and setting up WebRTC sessions.

## Technologies Used
- **WebRTC**: For peer-to-peer video and audio communication.
- **WebSockets**: For signaling between clients to establish the WebRTC connection.
- **Node.js & Express**: Backend server for handling WebSocket connections.
- **HTML, CSS, JavaScript**: Frontend technologies for building the user interface.
  


## Installation

### Prerequisites
- Ensure you have **Node.js** and **npm** installed on your machine.

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/omegle-clone-webrtc.git
2. **Navigate to the project directory:**
    ```bash
    cd omegle-clone-webrtc
3. **Install the required dependencies:**
    ```bash
    npm install
4. **Start the server:**
    ```bash
    cd backend/npm start
    cd frontend/npm run dev
5. **Open your browser and navigate to:**
    http://localhost:3000
    You should now be able to access the application and initiate anonymous video/audio chats.

## How It Works

1. **Signaling via WebSockets**: 
   - When two users join, WebSockets are used to exchange Session Description Protocol (SDP) and Interactive Connectivity Establishment (ICE) candidates. These are essential for establishing the WebRTC connection between peers.

2. **WebRTC Connection**:
   - Once the signaling process is completed, WebRTC takes over and handles the video/audio streaming directly between the connected peers, allowing seamless peer-to-peer communication.

3. **Anonymous Chat**:

    - "To be added" Users are randomly paired without any prior identification, enabling them to start chatting instantly once connected to another user.
