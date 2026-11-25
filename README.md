# Particle Simulation

A GPU particle generator written in TypeScript with Three.js. The particles are drawn by custom GLSL vertex and fragment shaders, so their motion is computed on the GPU rather than in JavaScript.

## How to run

1. Clone the repo and run `npm install`
2. Run `npm start` and open the address Parcel prints

## Code

- `src/ParticleEngine.ts` builds the particle geometry and material
- `src/VertexShader.ts` and `src/FragmentShader.ts` hold the GLSL
- `src/Main.ts` sets up the scene, camera and render loop
