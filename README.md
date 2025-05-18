# Interactive Rubik's Cube

This README provides detailed instructions for installing and running the **Interactive Rubik's Cube** project built with Next.js 13 (App Router) and React Three Fiber.

---

## 🔧 Prerequisites

- **Node.js (v16 or higher)**: Download and install from [https://nodejs.org/](https://nodejs.org/).
- **npm** (bundled with Node.js) or **Yarn** / **pnpm**.
- A modern browser with **WebGL** support (Chrome, Firefox, Edge, Safari).
- *(Optional)* A code editor such as **Visual Studio Code** for a better development experience.

---

## ⚙️ Installation

1. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```
   npm install three @react-three/fiber @react-three/drei
# or yarn
# yarn add three @react-three/fiber @react-three/drei


---

## 🚀 Running the Development Server

Start the Next.js development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open your browser and navigate to:
```
http://localhost:3000
```

---

## 🗂️ Project Structure

late/
├── app/
│   └── page.jsx         # Main page
├── components/
│   ├── Layout.jsx       # Main layout
│   ├── WeatherPanel.jsx # Weather display
│   ├── AirQuality.jsx   # Air quality component
│   └── Chart.jsx        # Charts component
├── public/              # Static files
└── .env.local           # API keys



## Available Scripts

    npm run dev: Start development server

    npm run build: Create production build

    npm start: Start production server

    npm run lint: Run ESLint 


## 🎮 Usage & Controls

- **Rotate Layers**
  - Click on any cube face to rotate the corresponding layer around that axis.
  - Use the buttons below for quick rotations:
    - **Horizontal**: rotates the middle layer around the Y-axis.
    - **Vertical**: rotates the middle layer around the X-axis.

- **Scramble**
  - Click the **Scramble** button to apply a series of random 90° rotations.

- **Reset**
  - Click the **Reset** button to restore the cube to its solved state.

- **Camera Controls**
  - **Orbit**: Left-click and drag.
  - **Zoom**: Scroll wheel or pinch.
  - **Pan**: Right-click and drag or two-finger drag.

---

## 🎨 Customization

- **Cube Scale**: Adjust the overall size by editing the `scale` prop on the `<group>` wrapping `<RubiksCube>` in `app/page.jsx`.

- **Button Styles**: Modify the `buttonStyle` object in `app/page.jsx` to change colors, padding, border radius, etc.

- **Colors**: Update the `COLORS` object in `app/page.jsx` to customize face colors or background.

---




