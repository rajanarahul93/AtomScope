# Carbon Atom Visualization

A 3D interactive visualization of a Carbon atom built with **React**, **@react-three/fiber**, and **@react-three/drei**. This project demonstrates the atomic structure of Carbon, including its nucleus, electrons, and orbitals, with dynamic features like isotope selection and animated electron movements.

## Features

- **Dynamic Nucleus Representation**
  - Visualizes protons and neutrons in a spherical arrangement.
  - Distinguishes protons (gold) and neutrons (silver) with vibrant colors.

- **Isotope Selection**
  - Choose between Carbon-12, Carbon-13, and Carbon-14 isotopes.
  - Dynamically adjusts the number of neutrons in the nucleus.

- **3D Orbitals**
  - Includes both spherical (`s`) and dumbbell-shaped (`p`) orbitals.
  - Animates electrons moving along their respective orbitals.

- **Interactive Controls**
  - Rotate, pan, and zoom the 3D visualization using intuitive camera controls.

- **UI Labels**
  - Display isotope information, proton/neutron count, and a legend for orbital types.

## Technologies Used

- **React**
- **@react-three/fiber**: A React renderer for Three.js.
- **@react-three/drei**: A collection of helpers for React Three.js.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajanarahul93/AtomScope.git
   cd AtomScope
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open the project in your browser:
   ```
   http://localhost:3000
   ```

## Usage

1. Use the dropdown menu to select an isotope of Carbon (12, 13, or 14).
2. Rotate, zoom, and pan the 3D visualization using mouse controls.
3. Observe the dynamic electron movements and labeled orbitals.

## Project Structure

```
AtomScope/
├── public/
├── src/
│   ├── components/
│   │   ├── Nucleus.js        # Nucleus and nucleon arrangement logic
│   │   ├── Orbital.js        # S and P orbital representations
│   │   ├── Electron.js       # Electron movement animations
│   │   └── UI.js             # Isotope selector and UI labels
│   ├── App.js                # Main application component
│   └── index.js              # Application entry point
├── package.json
└── README.md
```


## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.



## Acknowledgements

- [@react-three/fiber](https://github.com/pmndrs/react-three-fiber)
- [@react-three/drei](https://github.com/pmndrs/drei)
- [Three.js Documentation](https://threejs.org/docs/)

---

