# Live Dashboard - Server-Sent Events (SSE) Practice Project

A modern real-time notification dashboard built with **Node.js + Server-Sent Events (SSE)**. Demonstrates user-specific live updates using only vanilla JavaScript and Tailwind CSS (no heavy frameworks).

Perfect for learning and practicing production-grade SSE patterns.

## Features

- ✅ **User-specific notifications** – Each user gets their own live feed
- ✅ **Live notification badge** in navbar (real-time count)
- ✅ **Beautiful modal popup** for notifications (instead of tabs)
- ✅ Clean **sticky navbar** with Dashboard & Notifications
- ✅ Auto-connect & manual connect/disconnect
- ✅ Responsive and modern UI using Tailwind CSS
- ✅ Unread count tracking (resets when modal is opened)
- ✅ ESC key support to close modal
- ✅ Clean code with proper connection handling

## Tech Stack

- **Backend**: Node.js + Express
- **Real-time**: Server-Sent Events (SSE)
- **Frontend**: Vanilla JavaScript + Tailwind CSS (via CDN)
- **No React / No Build Tools** – Single HTML file

## How to Run

### 1. Clone / Setup

```bash
mkdir sse-notifications
cd sse-notifications


npm init -y
npm install express cors

node server.js

http://localhost:3000 - plain html version
http://localhost:3000/dashboard-react.html - react version demo



```
