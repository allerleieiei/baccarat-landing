# Baccarat Landing (DE / EN / DE-CH)

## Deploy without terminal
### Option 1: GitHub → Vercel (recommended)
1. Create a GitHub account and a new **public** repository.
2. Click **Add file → Upload files**, then **drag the whole folder** here (unzipped). Commit.
3. Go to **vercel.com**, import the repository, click **Deploy**. Done.
4. Add your custom domain in Vercel.

### Option 2: GitHub → Netlify
1. On Netlify choose **Import from Git** and connect your GitHub repo.
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Deploy.

## Local development (optional)
- Install Node.js 18+
- `npm i`
- `npm run dev` → http://localhost:5173/#/
