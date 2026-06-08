# Pulsar Simulator

An interactive pulsar visualisation built with JavaScript and p5.js.

This project demonstrates how pulsars emit beams of radiation and how those beams produce periodic signals when they sweep across an observer's line of sight. Users can adjust pulsar properties, move the observer, zoom around the scene, and observe changes in the received signal waveform in real time.
## Features

- Interactive 2D pulsar visualisation
- Adjustable pulsar spin rate
- Adjustable beam width
- Real-time signal strength graph
- Draggable Earth observer
- Distance-based signal attenuation
- Camera pan and zoom controls
- Preset pulsar configurations
- Large procedural star field
- Live frequency and period calculations
- Reset view button

## Controls

### Mouse Controls

- Left click and drag empty space to pan the camera
- Drag Earth to move the observer position
- Mouse wheel to zoom in and out

### Sliders

#### Spin Rate
Controls how quickly the pulsar rotates.

Higher values produce:
- Higher frequency
- Shorter period
- More frequent pulses

#### Beam Width
Controls the angular width of the pulsar beams.

Higher values produce:
- Wider pulses
- Longer detection times
- Broader peaks in the waveform

### Presets

Several preset pulsar types are included:

- Slow Pulsar
- Typical Pulsar
- Fast Pulsar
- Millisecond Pulsar
- Custom

Selecting a preset automatically adjusts the simulation parameters.

## Physics Model

The simulator models:

- Rotating pulsar beams
- Observer line-of-sight detection
- Signal intensity variation
- Distance attenuation
- Pulse generation over time

Signal strength is calculated using a Gaussian beam profile based on the angular separation between the observer and the pulsar beam direction.

Distance attenuation reduces signal intensity as the observer moves farther away from the pulsar.

## Technologies Used

- HTML5
- CSS
- JavaScript
- p5.js

## Running Locally

1. Download or clone the repository.
2. Open `index.html` in a web browser.

No installation is required.

## Future Improvements

Planned features include:

- Magnetic axis tilt controls
- 3D pulsar visualisation
- Noise and interference simulation
- Exportable waveform data
- Multiple observer modes
- Educational information panels


NOTE: These might not be added as I have school to deal with too, but if they are, I will update the site with a messsage notifying users about it.

## Educational Purpose

This simulator is intended as an educational tool to help visualise:

- Pulsar rotation
- Radio pulse generation
- Frequency and period relationships
- Observer geometry
- Signal attenuation effects

The model prioritises visual understanding while incorporating simplified physical behaviour, hence why I didn't purely maximise on astronomical accuracy while building this.

## License

MIT License
