# 3D Rotating Dragon Carousel with Centered Model

## Overview

This project showcases a **3D rotating carousel of dragon images** with a **centered model image** behind it. It is built with **HTML and CSS**, featuring **CSS variables, keyframe animations, and 3D transforms**. The carousel rotates infinitely around the model, creating an engaging visual effect.

---

## Features

* **3D rotating carousel:** Images rotate around a central axis using `rotateY` and `translateZ`.
* **Responsive layout:** Carousel and model image adjust to screen size.
* **CSS variables:** Each carousel item has `--position` and the slider has `--quantity` to easily manage rotation.

---

## File Structure

```
project/
│
├── index.html          # Main HTML file
├── styles.css          # CSS file with styling and animations
├── images/
│   ├── dragon1.jpeg
│   ├── dragon2.jpeg
│   ├── ...             # Dragon images 1-10
│   └── model.jpeg      # Centered model image
└── README.md           # Project description
```

---

## Usage

1. Clone or download the repository.
2. Make sure all images are placed in the `images/` folder.
3. Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).
4. Watch the carousel rotate around the centered model.

---

## Customization

* **Number of carousel items:** Change the `--quantity` CSS variable in the `.slider` div.
* **Add/remove images:** Add `<div class="item" style="--position:X"><img src="images/dragonX.jpeg"></div>` inside the slider.
* **Add a model image:** Add an image to be in a center i.e. it acts as a center point.
* **Animation speed:** Modify the `animation-duration` property in `.banner .slider`.

---

## Technologies Used

* HTML5
* CSS3 (Flexbox, CSS Variables, 3D Transforms, Keyframes)


---

## Screenshots

![Sample Screenshot](images\screenshot.png)
*Dragons rotates.*

---

