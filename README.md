# Rotating Wireframe Torus

This project demonstrates a simple 3D graphics application using Three.js to create and animate a rotating wireframe torus.

## Description

The application creates a white wireframe torus that rotates continuously against a black background. It's built using HTML5, CSS, and JavaScript, with Three.js for 3D rendering.

## Features

- Responsive design that fills the entire browser window
- Continuous rotation of the torus on both X and Y axes
- Automatic resizing to maintain display when the browser window is resized

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Three.js (loaded from CDN)

## Setup and Running

1. Clone this repository to your local machine.
2. Open the `index.html` file in a modern web browser.
3. The rotating torus should appear immediately, filling the browser window.

## Technical Details

- The torus is created using `THREE.TorusGeometry` with the following parameters:
  - Radius: 10
  - Tube: 3
  - Radial segments: 8
  - Tubular segments: 24
- The wireframe material is white (`0xffffff`)
- The background is black (`0x000000`)
- The camera is positioned at z = 30
- Rotation speed is set to 0.01 radians per frame for both x and y axes

## Customization

You can easily customize the appearance and behavior of the torus by modifying the following:

- Torus geometry parameters in the `THREE.TorusGeometry` constructor
- Material color in the `THREE.MeshBasicMaterial` constructor
- Background color in `scene.background = new THREE.Color(0x000000);`
- Camera position (`camera.position.z`)
- Rotation speed in the `animate` function

## Dependencies

This project uses Three.js, which is loaded from a CDN. An internet connection is required to load the library unless you modify the code to use a local copy of Three.js.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](../../issues) if you want to contribute.

## Author

Yamaoka Takeshi

---

Enjoy exploring and modifying this 3D graphics demo!
