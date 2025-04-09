# OmegleClone - Open Source Random Video Chat App

OmegleMeet is a real-time video chat app inspired by Omegle. It allows users to connect with strangers for live video calls and text chats.

🔴 **[Live Demo (currently broke)](http://omeglemeet.devrohit.tech/)** - Or checkout demo video below
[![OmegleMeet Demo](https://img.youtube.com/vi/YTGfyUdhu-U/0.jpg)](https://www.youtube.com/watch?v=YTGfyUdhu-U)

## Features
- Random stranger matching
- Real-time video calling with WebRTC
- Text chat alongside video calls
- Camera device switching
- Mobile responsive design

## Tech Stack
**Frontend**
- React.js
- Socket.IO Client
- WebRTC

**Backend**
- Express.js
- Socket.IO
- Redis

## Deployment
Deployed on AWS with Nginx serving both frontend and backend.

## How It Works
1. Enter a username to join
2. Get paired with random users
3. Start video call via WebRTC
4. Chat and switch cameras during calls
5. Disconnect and find new partners

## Project Setup
```bash
# Clone repository
git clone [repo-url]

# Setup before running
mv client/env client/.env && mv server/env server/.env && cd client && npm install && cd ../server && npm install

# Start Client
cd client && npm run dev

# Start Server
cd server 

## Docker server start 
docker-compose up -d (docker setup)

## Manual server start (update .env file redis config)
npm run dev
```

## More Complex Version

Looking for a more advanced version of this app?
Check out SquadX — a much more feature-rich video chat experience:
[https://github.com/rohitsx/SquadX](https://github.com/rohitsx/SquadX)

## Custom Features or Help?
Need something custom-built or want to collaborate?
Feel free to reach out to me at  rohitbindw@gmail.com

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact
Rohit Bind - [rohitbindw@gmail.com](mailto:rohitbindw@gmail.com)

---
Keywords: omegle clone github, random video chat app, omegle alternative, open source video chat, webrtc video chat, omegle like, omegle clone, random video chat, omegle alternative, open source omegle, video chat app, random chat application, webrtc video chat, react video chat, omegle like app github, video chat github, omegle clone github, random video chat open source
