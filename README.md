# Tactiles
```
// Add a tactile sensation. 
addTactile(tactiles, {aVibrationPattern, svgShape})

// If holding cursor in an svg-shape, play associated vibration pattern. 
finger.onholdandmove(cursor -> vibeId = startVibration(tactiles, cursor))

// When not moving, stop vibrating 
finger.onstopmove(stopVibration(vibeId))
```
