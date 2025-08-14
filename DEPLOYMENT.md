# 🚀 Deployment Guide for 12 Coins Logic Puzzle

## Quick Deploy to Netlify

### Method 1: GitHub Integration (Recommended)
1. Go to [Netlify Dashboard](https://app.netlify.com/)
2. Click **"New site from Git"**
3. Choose **"GitHub"** as your Git provider
4. Select repository: **`sabbah13/12coins`**
5. Configure build settings:
   - **Build command**: Leave empty (no build needed)
   - **Publish directory**: `.` (root directory)
   - **Site name**: `12coins`
6. Click **"Deploy site"**

### Method 2: Manual Drag & Drop
1. Go to [Netlify Dashboard](https://app.netlify.com/)
2. Drag and drop the entire project folder
3. Once deployed, go to **Site settings** → **Change site name** → `12coins`

## Site Configuration

### Custom Domain
- **Netlify URL**: `https://12coins.netlify.app`
- **Repository**: `https://github.com/sabbah13/12coins`

### Build Settings
The `netlify.toml` file includes:
- Publish directory: `.` (root)
- Security headers
- Cache optimization
- Performance settings

### Environment
- **Node Version**: 18 (specified in netlify.toml)
- **No build process**: Direct HTML deployment

## Files Ready for Deployment
- ✅ `index.html` - Main application
- ✅ `README.md` - Documentation  
- ✅ `package.json` - Project metadata
- ✅ `netlify.toml` - Deployment configuration
- ✅ `.gitignore` - Git ignore patterns

## Post-Deployment
1. Test the live site at `https://12coins.netlify.app`
2. Verify responsive design on mobile/tablet
3. Check game functionality and physics simulation
4. Update README.md with live demo link if needed

## Troubleshooting
- **Site not found**: Ensure site name is `12coins`
- **Build failed**: Check netlify.toml configuration
- **Assets not loading**: Verify publish directory is `.`

---
**Ready to deploy!** 🚀