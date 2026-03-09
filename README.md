# 🌿 Purely Plated Recipes — How to Update the Website

Hi! This website is just **one file**: `index.html`.  
No apps to install, no build process, no Netlify credits. Just edit the file and push!

---

## 🚀 First-time setup (GitHub Pages)

1. Go to your GitHub repo → **Settings** → **Pages**
2. Under "Branch", select **main** and **/ (root)**
3. Click **Save**
4. Your site will be live at `https://daphnepiteira.github.io/purely-plated-recipes/`

That's it. The site is live!

---

## ✏️ How to add a recipe

Open `index.html` and look for the `RECIPES` array near the top of the `<script>` section.

Each recipe looks like this — just copy one block and fill in your info:

```js
{
  title: "Golden Lentil & Coconut Soup",
  url: "https://www.bbcgoodfood.com/...",
  image: "https://images.unsplash.com/...",
  source: "BBC Good Food",
  tags: ["Vegan", "Gluten-Free", "Dairy-Free"]
},
```

### What each field means:

| Field | What to put |
|---|---|
| `title` | Name of the recipe |
| `url` | Link to the recipe on the web |
| `image` | A direct link to a photo (see below) |
| `source` | The website name (e.g. "BBC Good Food") |
| `tags` | One or more dietary labels (see list below) |

### How to get an image link:
1. Find the recipe on the web
2. Right-click the main photo → **"Copy image address"**
3. Paste that URL as the `image` value

### Available tags (use these exactly):
- `Vegan`
- `Vegetarian`
- `Dairy-Free`
- `Gluten-Free`
- `Nut-Free`
- `Halal`
- `Low-Carb`
- `Paleo`

💡 You can also invent your own! Any tag you add will automatically appear as a filter button on the website.

---

## 💾 How to publish your changes

1. Edit `index.html` in GitHub (click the pencil ✏️ icon)
2. Add your recipe block
3. Click **Commit changes**
4. Wait 30 seconds → your site updates automatically!

---

## ❓ Troubleshooting

**Site not showing?** → Check Settings → Pages is enabled.  
**Image not loading?** → Make sure the image URL ends in `.jpg`, `.png`, or `.webp`.  
**Tag not appearing?** → Check spelling matches exactly (capital first letter).
