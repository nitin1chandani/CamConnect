# CamConnect

## A free, p2p, group video call app for the web. No signups. No downloads. Works in all major browsers.

CamConnect is built using WebRTC, so all your video, audio & text chat is peer-to-peer. Group video call is achieved using WebRTC mesh. So the quality of the call is inversely proportional to the number of people on the call. The sweet number is somewhere around 6 to 8 people in an average high-speed connection.

---

### Prerequisites:

- Node.js 8.x or above
- NPM

### How to Build this app locally

[Fork this repo](https://github.com/vasanthv/CamConnect/fork) and then clone it:

```bash
git clone https://github.com/<your_name>/CamConnect.git
```

`cd CamConnect` and then install dependencies

```bash
npm install
```

Run the app

```bash
npm start
```

to start the CamConnect server on port 3000. Your CamConnect instance will be running on http://localhost:3000. Alternatively you can run the application using docker with `docker-compose up`.

### LICENSE

<a href="https://github.com/vasanthv/CamConnect/blob/master/LICENSE">MIT License</a>
