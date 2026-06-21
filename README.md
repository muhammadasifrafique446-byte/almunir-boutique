# Al-Munir Boutique Website 🌹

A beautiful, responsive website for Al-Munir Boutique featuring a premium unstitched dress collection.

## 📁 Folder Structure

```
almunir-designs-repo/
├── index.html              (Main website)
├── README.md              (This file)
├── images/                (Design images folder)
│   ├── design1.jpg
│   ├── design2.jpg
│   ├── design3.jpg
│   ├── design4.jpg
│   ├── design5.jpg
│   ├── design6.jpg
│   ├── design7.jpg
│   ├── design8.jpg
│   ├── design9.jpg
│   └── design10.jpg
└── css/                   (Optional - for future styling)
```

## 🎯 Design Names & Prices

| # | Design Name | Category | Price | WhatsApp |
|---|---|---|---|---|
| 1 | Summer Rose | Summer | Rs. 2,500 | ✅ |
| 2 | Pink Dreams | Casual | Rs. 2,300 | ✅ |
| 3 | Teal Elegance | Formal | Rs. 2,800 | ✅ |
| 4 | Golden Hour | Party | Rs. 3,200 | ✅ |
| 5 | Crimson Grace | Classic | Rs. 2,600 | ✅ |
| 6 | Rose Gold Charm | Premium | Rs. 3,500 | ✅ |
| 7 | Purple Passion | Seasonal | Rs. 2,900 | ✅ |
| 8 | Peachy Keen | Trendy | Rs. 2,400 | ✅ |
| 9 | Seafoam Serenity | Modern | Rs. 2,350 | ✅ |
| 10 | Sunset Bliss | Exclusive | Rs. 3,100 | ✅ |

## 📸 How to Add Design Images

### Method 1: Download from Gmail (Easiest) ⭐

1. **Open Gmail** and find the email with designs from "almunir@gmail.com"
2. **Right-click each image** → Click "Download image"
3. **Rename** to: `design1.jpg`, `design2.jpg`, etc.
4. **Move** all 10 images to the `images/` folder

### Method 2: Bulk Download

1. Open the email with all 10 designs
2. On desktop: Click the 📎 "Download all" button
3. Extract the ZIP file
4. Rename files to `design1.jpg`, `design2.jpg`, etc.
5. Move to `images/` folder

### Method 3: Using Tools

**For Windows:**
```bash
# If you have 7-Zip installed
7z x "downloaded-images.zip" -o"images/"
```

**For Mac/Linux:**
```bash
unzip downloaded-images.zip -d images/
```

## 🚀 Deploy to GitHub Pages

### Step 1: Push to GitHub

```bash
# Navigate to your repo directory
cd your-local-repo-path

# Add all files
git add .

# Commit changes
git commit -m "Add Al-Munir Boutique design products with images"

# Push to GitHub
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to **GitHub** → Your repo `muhammadasifrafique446-byte/boutique`
2. Click **Settings** → **Pages**
3. Under "Source", select `main` branch
4. Click **Save**
5. Your site will be live at: `https://muhammadasifrafique446-byte.github.io/boutique/`

## 🔧 Customization

### Update WhatsApp Number

Find this line in `index.html`:
```html
https://wa.me/+923001234567?text=...
```

Replace `+923001234567` with your actual WhatsApp number:
```html
https://wa.me/+92YOURPHONENUMBER?text=...
```

**Example:**
```html
https://wa.me/+923005551234?text=Hi%20Al-Munir%20Boutique%2C%20I%27m%20interested%20in%20Summer%20Rose%20design
```

### Change Prices

1. Open `index.html` in any text editor
2. Find: `<div class="product-price">Rs. 2,500</div>`
3. Change the number to your price
4. Save and commit

### Update Design Names & Descriptions

Find each design section and modify:
```html
<div class="product-name">Summer Rose</div>
<div class="product-description">Beautiful summer design with floral patterns and comfortable fabric</div>
```

## 📱 Features

✅ **Responsive Design** - Works on mobile, tablet, desktop
✅ **WhatsApp Integration** - One-click ordering
✅ **Beautiful Animations** - Smooth hover effects
✅ **Modern Color Scheme** - Hot pink, rose gold, teal, gold
✅ **Professional Layout** - Easy to navigate
✅ **Fast Loading** - Optimized for performance

## 🎨 Color Palette

- **Primary Pink**: #d4145a
- **Accent Orange**: #fbb03b
- **Teal**: #17a4b8
- **Rose Gold**: #e0a76f
- **White**: #ffffff

## 📞 Support

For help with:
- **Website changes**: Edit `index.html`
- **Image issues**: Check `images/` folder
- **Deployment**: Use Git commands above
- **WhatsApp setup**: Update phone number in links

## 📝 Notes

- All design images should be in `images/` folder
- Image format: JPG or PNG
- Recommended image size: 800x600px or larger
- Keep file names simple: `design1.jpg`, `design2.jpg`, etc.

---

**Website Version**: 1.0  
**Last Updated**: June 21, 2026  
**Created for**: Al-Munir Boutique
