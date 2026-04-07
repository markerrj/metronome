# Overview
Metronome is intended to be a simple web application implementing a metronome for musicians.

All the code should live in a single index.html file and functionality should be implemented in standard Javascript without using any frameworks. Use of libraries for functionality is fine.

Features are limited with this metronome. It is focused on 4/4 tempos with bpm settings 30-300.

What differentiates this metronome from others is its ease of usability and its visual display, which is detailed below.

# Visual Design
The page should be only a large, thick bordered circle with a large 3-digit capable text field in the middle of the circle. The circle and the 3-digit text field (used for BPM input and display) should be centered in the webpage and take up about 75% of the browser window.

The circle starts out as a black border. When the metronome clicks, the circle should flash green. Since this metronome is focused on 4/4 time, every 4th click of the metronome should be displayed as different, lighter shade of green.

Below the BPM text field should be a single large play/pause button. Clicking this should alter the play/pause state of the metronome.

# Usability
Users should be able to click on the BPM text field and directly input a new BPM with a keyboard. They should also be able to set the new BPM and have it start being used by hitting the enter key. For text editing like this, the new BPM only takes effect when enter key is hit. While editing the BPM field, but before the user hits enter key, hitting the escape key should reset the value of the BPM text field to the prior value.

When the user's mouse cursor is hovering over the BPM text field, the BPM text field should have a glow around it. Moving the mouse scroll wheel should increment or decrement the BPM count by 1 BPM when scrolling slowly or by 5 BPM when scrolling quickly. When the BPM is adjusted by mouse wheel scrolling, the new BPM should take effect immediately without waiting for an enter key to be pressed.

The metronome should be configured by default on first page load with 100bpm. The metronome should also be playing by default.
