# Shopify Developer Tools

Essential bookmarklets for faster Shopify theme development and debugging.

## 🚀 Quick Installation

1. **Drag** the green button from the tool page to your browser's bookmarks bar
2. **Navigate** to any Shopify store 
3. **Click** the bookmark to use the tool

*Note: If dragging doesn't work, click "Show Code" to copy the bookmark manually.*

## 🛠️ Tools

### 🎯 Admin Navigator
Jump directly from any Shopify storefront page to the corresponding admin page.

**Works with:**
- Products → Product admin page
- Collections → Collection admin page  
- Pages → Page admin page
- Blog articles → Article admin page
- Home page → Themes admin
- Cart page → Checkout settings

**Features:**
- Handles custom domains automatically
- Fetches resource IDs via JSON endpoints when needed
- Opens admin pages in new tabs
- Works on both `.myshopify.com` and custom domains

### 🔧 Preview Bar Unhider
Force the Shopify preview bar to show when it's been hidden by themes or apps.

**Use when:**
- Preview bar is invisible or hidden
- Theme CSS is conflicting with preview bar styles
- Apps are interfering with preview bar display
- Need to access preview bar functionality for debugging

**Features:**
- Forces hidden preview bars to become visible
- Overrides CSS rules that hide the preview bar
- Positions preview bar correctly at bottom of screen
- Adds body padding to prevent content overlap
- Provides console logging for debugging

## 💡 Usage Tips

- **Admin Navigator**: Use when you need to quickly edit content you're viewing on the storefront
- **Preview Bar Unhider**: Use when developing themes and the preview bar disappears
- Both tools work across all Shopify stores and handle edge cases automatically
- Tools are safe to use and don't modify your store data

## 🔧 Troubleshooting

- **Bookmarklet not working?** Try copying the code manually and creating a new bookmark
- **Still can't see preview bar?** Check if your theme has custom CSS hiding preview elements
- **Admin navigator going to wrong page?** The tool will fallback to the themes admin if it can't determine the specific page

---

*Created for Shopify theme developers and merchants who need faster workflows.*
