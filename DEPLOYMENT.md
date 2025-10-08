# Deployment Guide for Snake Game

## Quick Deploy to Render

### Method 1: GitHub Repository (Recommended)

1. **Prepare your repository:**
   ```bash
   git add .
   git commit -m "Prepare for Render deployment"
   git push origin main
   ```

2. **Deploy on Render:**
   - Go to [render.com](https://render.com) and sign up/log in
   - Click "New +" → "Web Service"
   - Connect your GitHub repository
   - Configure:
     - **Name**: `snake-game` (or preferred name)
     - **Environment**: `Node`
     - **Build Command**: `npm install`
     - **Start Command**: `npm start`
     - **Plan**: Free tier is sufficient

3. **Your game will be live at**: `https://[service-name].onrender.com`

### Method 2: Manual Deploy

If you don't want to use GitHub:

1. **Create a new web service on Render**
2. **Upload your files directly** or connect via Git
3. **Use these settings:**
   - Build Command: `npm install`
   - Start Command: `npm start`
   - Port: 3000 (auto-detected)

## Environment Variables (Optional)

You can set these in Render's dashboard:

- `NODE_ENV=production`
- `PORT` (automatically set by Render)

## Performance Optimizations Included

✅ **Compression**: Gzip compression for faster loading
✅ **Caching**: Static assets cached for 24 hours
✅ **Security Headers**: XSS protection, frame denial, content type protection
✅ **Health Check**: `/health` endpoint for monitoring
✅ **Error Handling**: Graceful error handling and logging

## Monitoring Your Deployment

- **Health Check URL**: `https://[your-app].onrender.com/health`
- **Logs**: Available in Render dashboard
- **Performance**: Monitor in Render's metrics section

## Troubleshooting

### Common Issues:

1. **Build fails**: Check that `package.json` is correct
2. **App won't start**: Verify `server.js` file exists
3. **404 errors**: All routes redirect to main game

### Local Testing:

```bash
# Install dependencies
npm install

# Test locally
npm start

# Visit http://localhost:3000
```

## Custom Domain (Optional)

To use your own domain:
1. Go to your Render service settings
2. Add custom domain
3. Update your DNS records as instructed

## Free Tier Limitations

Render's free tier includes:
- 750 hours/month
- Automatic sleep after 15 min of inactivity
- Cold start delay (~30 seconds)
- Shared resources

For production use, consider upgrading to a paid plan.

## Support

If you encounter issues:
1. Check Render's status page
2. Review deployment logs
3. Test locally first
4. Check GitHub Issues

---

**Your snake game should now be live and ready to play! 🐍🎮**