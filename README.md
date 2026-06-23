# 🍽️ MaruMeals — Food Delivery Website

Zomato jaisi food delivery website made for Rajasthan!

## Features
- 🔍 Live search (restaurants + dishes)
- 📍 Location selector (Jaipur, Jodhpur, Udaipur, etc.)
- 🛒 Add to cart with quantity controls
- 🏷️ Category filters (Rajasthani, Pizza, Biryani, etc.)
- ⭐ Rating, delivery time display
- 🎉 Promo code banner
- 📱 Fully responsive (mobile + desktop)
- 🌙 Smooth animations & toast notifications
- 💾 Cart persists using localStorage

## Deploy on GitHub + Netlify

### Step 1: GitHub pe upload karo
1. [github.com](https://github.com) pe new repository banao — name: `marumeals`
2. `index.html`, `netlify.toml`, `README.md` teen files upload karo
3. Commit karo

### Step 2: Netlify pe deploy karo
1. [netlify.com](https://netlify.com) pe login karo
2. **"Add new site" → "Import an existing project"** click karo
3. GitHub select karo → `marumeals` repo choose karo
4. Build settings:
   - **Publish directory:** `.` (just a dot)
5. **"Deploy site"** click karo — 2 minute mein live!

### Custom Domain (Optional)
- Netlify pe free `.netlify.app` domain milega jaise `marumeals.netlify.app`
- Ya apna domain Netlify DNS settings mein add karo

## Customize karna ho toh
- `restaurants` array mein apna data change karo
- Logo text `MaruMeals` hai — change karna ho toh `logo` class search karo
- Colors change karne ke liye `:root` mein `--orange: #FF5200` edit karo
