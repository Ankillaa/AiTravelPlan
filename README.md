# AI Budget Travel Planner 🌍✈️

An AI-powered travel planning application that helps you create budget-friendly travel itineraries using Google's Gemini AI.

## Features
- AI-generated travel plans
- Budget-conscious recommendations
- Simple and intuitive interface
- Powered by Google Gemini API

## Local Setup

1. Install dependencies:
```bash
npm install
```

2. Create a `.env` file with your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

3. Run the server:
```bash
npm start
```

4. Open http://localhost:3000 in your browser

## Deploy to Render (Free)

### Step 1: Push to GitHub
```bash
git add .
git commit -m "Ready for deployment"
git push origin main
```

### Step 2: Deploy on Render
1. Go to [render.com](https://render.com) and sign up
2. Click "New +" → "Web Service"
3. Connect your GitHub repository
4. Configure:
   - **Name**: ai-budget-travel-planner
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
5. Add Environment Variable:
   - **Key**: `GOOGLE_API_KEY`
   - **Value**: Your Google API key
6. Click "Create Web Service"

Your app will be live in 2-3 minutes! 🎉

## Deploy to Railway (Free)

1. Go to [railway.app](https://railway.app)
2. Sign up with GitHub
3. Click "New Project" → "Deploy from GitHub repo"
4. Select your repository
5. Add environment variable `GOOGLE_API_KEY`
6. Deploy!

## Deploy to Vercel (Free)

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

3. Add environment variable in Vercel dashboard:
   - `GOOGLE_API_KEY`

## Getting a Google API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Click "Create API Key"
4. Copy the key and add it to your `.env` file

## Tech Stack
- **Backend**: Node.js, Express
- **AI**: Google Gemini API
- **Frontend**: Vanilla JavaScript, HTML, CSS

## License
MIT
