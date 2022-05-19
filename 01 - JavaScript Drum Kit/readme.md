
# JS Drum Kit

A forked project from JavaScript30.com for learning purpose.

## New learnings:
1. window.addEventListener('keydown', function(e){});
2. document.querySelector() & document.querySelectorAll()
3. data-* attribute

<div data-key="65" class="key">

-- Used to create custom attributes that can hold data for use in JS


4. Audio on website
  <audio data-key="65" src="sounds/clap.wav"></audio>
  $("audio").play();

5. <kbd> : keyboard input

## Methodology
- Use data-* attributes to bind keyboard inputs with audio tags
- when a key is pressed, recognize the corresponding audio & key box, and play the sound & transform the key boy by adding CSS class
- As the transition finishes, remove the CSS class