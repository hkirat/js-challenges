## Flappy bird

 - Initialize an empty index.html, index.js file. Import index.js inside index.html
 - Create a canvas of 800x800 with a blue background color
 - Create a single variable called birdX and initialize it to 800 / 2
 - Create a gravity variable set it to 9.8
 - Create a velocity variable set it to 0
 - Create an infinite for loop that updates birdX and velocity based on the time (11th standard physics)
 - Update the position of the bird on canvas based on that
 - Catch the keyboard up event and set velocity to +20 when the keybaord up key is pressed
 - See your bird dance up and down

## Advanced TODOs
 - Calculate the time between renders, dont assume a certain framerate
 - Add bars throughout whose speed keeps on increasing and move towards the bird
 - In every interation, check if the bird collided with a bar