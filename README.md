# BarbaraPDF Backend

Backend server for AI Tutor functionality using OpenAI API.

## Deploy to Render

1. Go to https://render.com
2. Sign up with GitHub
3. Click "New +" → "Web Service"
4. Connect your GitHub repo
5. Settings:
   - Name: `barbarapdf-backend`
   - Build Command: `npm install`
   - Start Command: `npm start`
6. Add Environment Variables:
   - `OPENAI_API_KEY`: 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
   - `ALLOWED_ORIGINS`: `https://barbarapdfeditor.net,https://vitesite-4.sg-host.com`
7. Click "Create Web Service"

Render will give you a URL like: `https://barbarapdf-backend.onrender.com`

## API Endpoints

### Health Check
