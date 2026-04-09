# Metronome

A simple, visual web-based metronome for musicians.

## Access

Use the metronome at **https://markerrj.github.io/metronome/**

## Features

- **Customizable Tempo**: Set BPM between 30 and 300
- **Visual Feedback**: Flashing circle indicates each click, with lighter flash on the downbeat (every 4th beat)
- **Simple Interface**: Large circle with BPM input and play/pause button

## Usage

### Starting the Metronome

The metronome starts automatically when you load the page.

### Setting BPM

There are several ways to adjust the tempo:

**1. Click and Type**
- Click on the BPM display in the center of the circle
- Type your desired BPM value (30-300)
- Press **Enter** to confirm the new BPM
- Press **Escape** to cancel and revert to the previous value

**2. Scroll to Adjust**
- Hover over the BPM display
- Use your mouse scroll wheel to quickly adjust BPM
  - Scroll up: Increase BPM (faster tempo)
  - Scroll down: Decrease BPM (slower tempo)
- Scroll quickly for larger adjustments (±10 BPM)
- Scroll slowly for fine-tuning (±1 BPM)
- BPM changes take effect immediately without pressing Enter

### Play/Pause

Click the "Play" button below the circle to start or stop the metronome. When running, the button displays "Pause". When stopped, it displays "Play".

## Technical Details

- Built as a single self-contained HTML file
- Uses Web Audio API for click sounds (sine wave tones with optional noise burst for downbeats)
- Precise timing using requestAnimationFrame and setTimeout for accurate BPM
- Browser compatibility: Modern browsers with AudioContext support
