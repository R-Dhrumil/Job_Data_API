# Job Tunnel Backend API

This is the backend API powering [Job Tunnel](https://vercel.com/r-dhrumils-projects/job-tunnel), a platform for discovering job opportunities across India. Built with Node.js and Express, this API serves demo job data and is ready for deployment on Vercel.

## Features

- RESTful API to fetch job listings
- CORS enabled for frontend integration
- Easily extensible for real-world data and more endpoints

## Live API

You can access the deployed API here:  
👉 **[https://vercel.com/r-dhrumils-projects/job-tunnel](https://vercel.com/r-dhrumils-projects/job-tunnel)**

## Endpoints

- `GET /`  
  Returns a welcome message.

- `GET /api/jobs`  
  Returns a JSON array of job postings with details like employer, city, description, and apply link.

## Getting Started

### Prerequisites

- Node.js (v16 or above)
- npm

### Installation

1. Clone this repository or download the source code.
2. Install dependencies:
   ```sh
   npm install
