# Simple Wall Dashboard

This project is a fullscreen 2×2 grid dashboard designed for wall displays or always-on monitors.  
It shows:

- **Webcam Kempten**
- **Digital clock** (via timeanddate.com)
- **Webcam Augsburg**
- **Bavaria radar animation (DWD)**

The page **automatically refreshes all images and the iframe**.

---

## Features

- Clean **2×2 fullscreen layout** using CSS Grid  
- Smooth **hover animations**  
- **Auto-refresh** for webcams, radar, and clock  
- **Dark theme** design  
- Simple to modify and extend

---

## Structure

### Grid Layout

```html
<div class="grid">
  <div class="cell"> <!-- Webcam Kempten --> </div>
  <div class="cell clock-cell"> <!-- Clock --> </div>
  <div class="cell"> <!-- Webcam Augsburg --> </div>
  <div class="cell"> <!-- Bavaria Radar --> </div>
</div>
