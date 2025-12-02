# SyncPad - Real-time Collaborative Whiteboard

<div align="center">

![SyncPad Logo](https://img.shields.io/badge/SyncPad-Collaborative%20Whiteboard-fbbf24?style=for-the-badge&logo=draw.io&logoColor=white)

[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-4.x-010101?style=flat-square&logo=socket.io&logoColor=white)](https://socket.io/)
[![Supabase](https://img.shields.io/badge/Supabase-Auth-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)

**A powerful real-time collaborative whiteboard application enabling teams to draw, design, and brainstorm together seamlessly.**

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Tech Stack](#-tech-stack) • [Usage](#-usage) • [Contributing](#-contributing)

</div>

---

## Deployed Project Link - 

---

## 🌟 Overview

**SyncPad** is a feature-rich, real-time collaborative whiteboard application built with modern web technologies. It allows multiple users to draw, sketch, and collaborate on a shared canvas with instant synchronization and minimal latency.

### Why SyncPad?

- 🚀 **Real-time synchronization** with WebSocket technology
- 🎨 **Rich drawing tools** including pen, shapes, text, and more
- 👥 **Multi-user collaboration** with live cursor tracking
- 🔐 **Secure authentication** powered by Supabase
- 📱 **Responsive design** works on desktop and mobile
- ⚡ **Low latency** performance monitoring built-in

---

## ✨ Features

### 🎯 Core Features

#### ✅ Real-time Collaboration
- **WebSocket-powered** instant synchronization using Socket.io
- **Multi-user support** with real-time presence indicators
- **Live cursor tracking** - see where other users are drawing
- **User presence list** showing all online collaborators with colored indicators
- **Minimal latency** with performance monitoring (typically <100ms)

#### ✅ Rich Feature Set
- **Drawing Tools:**
  - ✏️ Free-hand pen with adjustable width
  - 🔴 Shapes: Circle, Rectangle, Ellipse, Polygon, Star
  - ➡️ Lines and Arrows
  - 🆎 Text tool with font customization
  - 🧽 Eraser with adjustable size
  
- **Shape Manipulation:**
  - Drag and drop shapes
  - Resize and rotate with transform handles
  - Double-click text to edit inline
  - Copy room ID with one click

#### ✅ User Experience
- **Clean, intuitive interface** with organized toolbar
- **Color customization** - 8 preset colors + custom color picker
- **Undo/Redo functionality** with full history tracking
- **Background color control** synced across all users
- **Download canvas** as PNG image
- **Auto-switch tools** for better workflow

#### ✅ State Management
- **Complete history tracking** for undo/redo operations
- **Real-time state synchronization** across all connected users
- **Canvas persistence** during active sessions
- **Shape metadata** tracking (creator, timestamps)

#### ✅ Room System
- **Multi-room support** with unique room IDs
- **Easy room sharing** with copy-to-clipboard functionality
- **Room isolation** - each room has independent canvas state
- **User management** per room with join/leave notifications

#### ✅ Authentication & Security
- **Supabase integration** for secure user authentication
- **Email/Password signup** with email verification
- **User profiles** with full name, email, and phone
- **Protected routes** with authentication guards

#### ✅ Performance Monitoring
- **Real-time latency tracking** displayed in UI
- **Performance metrics** for shape operations
- **Connection status** indicators
- **Console logging** for debugging and monitoring

---

## 🛠 Tech Stack

### Frontend
- **React 18.x** - UI framework
- **React Router v6** - Client-side routing
- **Konva.js & React-Konva** - Canvas rendering and manipulation
- **Socket.io Client** - WebSocket communication
- **Supabase Client** - Authentication
- **CSS3** - Styling with modern features

### Backend
- **Node.js 16.x** - Runtime environment
- **Express.js** - Web framework
- **Socket.io** - Real-time bidirectional communication
- **CORS** - Cross-origin resource sharing
- **HTTP** - Server creation

### Database & Auth
- **Supabase** - Authentication and user management

### Development Tools
- **npm** - Package management
- **Git** - Version control
- **ES6+** - Modern JavaScript

---
