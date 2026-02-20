# Modern VR Villa - A-Frame Experience

A realistic 3D VR experience of a modern two-story villa built using **A-Frame**. This project features sophisticated architectural design, autonomous pet behavior, realistic GLTF models, and interactive navigation.

## 🚀 Features

### 🏰 Architecture & Exterior
- **Two-Story Villa**: Interlocking volumes with balconies and floor-to-ceiling windows.
- **Realistic Textures**: Custom skybox texture and high-quality materials for walls, roof, and landscaping.
- **Infinity Pool**: Animated water with a sleek glass edge.
- **Outdoor Amenities**: 
    - **Basketball Court**: Full-size court located in the front yard.
    - **Truck**: Large realistic vehicle parked in front.
    - **Landscaping**: Upgraded realistic **Fall Trees** for a seasonal aesthetic.

### 🏠 Interior Realism
- **Living Room**: Premium couch, marble coffee table, and an **Animated Pug** pet with autonomous wandering logic.
- **Kitchen & Dining**: Modern island, stainless fridge, and glass dining suite.
- **Bedrooms**: All rooms standardized with realistic **GLTF Single Beds** for a consistent premium look.
- **2nd Floor Hall**: Enhanced lounge area with a large comfortable couch facing a wall-mounted TV.
- **Bathroom**: Detailed bathtub and vanity unit with modern fixtures.

### 🕹️ Controls & Navigation
- **Enhanced UI Menu**: 2D overlay with quick-teleport buttons for:
    - **Exterior**: Entrance, Front Yard, Basketball, Pool Side.
    - **1st Floor**: Living Room, Kitchen, Bedroom.
    - **2nd Floor**: Hall, Bedrooms, Bathroom, Balcony.
    - **Aerial**: Roof View for a bird's-eye perspective of the villa.
- **Movement Controls**:
    - **Desktop**: `W`, `A`, `S`, `D` to move, Mouse Click + Drag to look.
    - **VR Mode**: Fully immersive experience with look-based navigation.

## 🛠️ Technology Stack
- **A-Frame**: WebVR framework for 3D/VR development.
- **Three.js**: Internal engine for custom textures and geometry.
- **JavaScript**: Custom components for water animation, autonomous pet movement, and navigation logic.
- **CSS**: Responsive glassmorphism-style UI for the interaction menu.

## 🏃 How to Run
Due to CORS security restrictions, it is recommended to run a local web server:

### VS Code (Live Server)
1. **Open `index.html`** in VS Code.
2. Click **"Go Live"** in the status bar.
3. Access at `http://127.0.0.1:5500/index.html`.

### Alternative Methods
- **Python**: `python -m http.server 8000`
- **Node.js**: `npx http-server`

---
*Created with a focus on interior realism and immersive VR interaction.*
