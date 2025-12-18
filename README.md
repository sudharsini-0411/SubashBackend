# Recharge Hub Backend

Backend API for the Recharge Hub application.

## Environment Variables

Set these in Render:
- `MONGODB_URI`: Your MongoDB connection string
- `JWT_SECRET`: Secret key for JWT tokens
- `PORT`: Will be set automatically by Render

## Deployment

This backend is configured to run on Render with:
- Start command: `npm start`
- Node.js runtime
- Auto-deploy from GitHub