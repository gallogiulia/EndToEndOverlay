# Ecamm Live Lawn Bowls Scoreboard Overlay 🎳

This is a lightweight HTML overlay for Ecamm Live that displays real-time lawn bowls scores from a shared Google Sheet.

## 📺 Features
- Displays live match scores
- Organized by division (Men's/Women's, Singles/Pairs)
- Auto-refreshes every 15 seconds
- Fully transparent background for Ecamm browser overlay

## 🔗 Live Overlay URL
(Host this repo with GitHub Pages and paste the URL here)

## 🛠 How to Use
1. Update the Google Sheet with new scores
2. The [Apps Script](https://script.google.com/macros/s/YOUR_SCRIPT_ID/exec) returns live JSON
3. `index.html` fetches and displays the scores automatically
4. Load the hosted URL in Ecamm Live as a browser overlay

## 📝 Customization
- To change colors or font sizes, edit the `<style>` section in `index.html`
- You can adjust refresh interval (`setInterval`) in the script

## 🧪 Credits
Built with ❤️ using Google Sheets + Apps Script + Ecamm Live

