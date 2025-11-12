# Vincikaram Redirect Page

A simple HTML redirect page deployed on Vercel.

## Deployment Instructions

### Option 1: Deploy via Vercel CLI (Recommended)

1. Install Vercel CLI globally:
   ```bash
   npm install -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy the project:
   ```bash
   vercel
   ```

4. For production deployment:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up or log in
3. Click "Add New Project"
4. Import your Git repository (GitHub, GitLab, or Bitbucket)
5. Vercel will automatically detect the configuration and deploy

### Option 3: Deploy via Git Integration

1. Push this code to a GitHub/GitLab/Bitbucket repository
2. Connect your repository to Vercel
3. Vercel will automatically deploy on every push

## Local Testing

To test locally:
```bash
npm start
```

Then open http://localhost:8000 in your browser.
