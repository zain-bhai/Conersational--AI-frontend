# Frontend Setup Guide

This is the frontend interface for our project. It connects to the backend API (FastAPI / Flask / Node, etc.) to handle requests /Chat.

Follow the steps below to set it up locally or deploy it on your own server.

## Quick Start
## 1. Clone the Repository
git clone https://github.com/zain-bhai/Conersational--AI-frontend.git

cd Conersational--AI-frontend

## 2. Install Dependencies
Make sure you have Node.js and npm installed.
Then run:
npm install

## 3. Configure the API URL

Open the file:

index.html

## Go to line 149
Replace the existing API URL with your own deployed backend URL followed by the /chat endpoint.

Example:

// Before:const API_URL = "https://conversational-ai-hv4u.onrender.com/chat";

// After:
const API_URL = "https://your-deployed-api-url.com/chat";


you are good to go just integrate this index file to your system.
