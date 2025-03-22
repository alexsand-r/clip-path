
# 📐 Custom css clip-path polygon
<p align="center">
  <img src="img/Screenshot_6.png" alt="Image 1" width="430" height="325">
</p>
This project demonstrates how to create a custom `clip-path` for an image using CSS.

🔗 Live Demo:  (alexsand-r.github.io/clip-path/)

## Steps to create:

1. **Create the polygon outline**  
   - Open a vector editor (e.g., Figma, Adobe Illustrator, Inkscape).  
   - Draw the desired shape that will be used as a clipping path (`clip-path`).  
   - Export the outline in SVG format.  

2. **Generate CSS code**  
   - Go to [PlantCSS](https://www.plantcss.com/).  
   - Upload the created SVG file or manually set the polygon coordinates.  
   - Copy the generated CSS code.  

3. **Apply clip-path to the image**  
   - Add the generated CSS code to your stylesheet.  
   - Apply `clip-path` to the image, for example:  

  ```css
.picture {
    max-width: 100%;
    display: block;
    clip-path: polygon(4.092% 54.8%, 3.507% 32.331%, 3.49% 31.982%, 
    3.463% 31.008%, 3.459% 29.518%, 3.512% 27.625%, 3.654% 25.438%, 
    3.92% 23.066%, 4.342% 20.621%, 4.954% 18.213%, 5.79% 15.952%, 
    6.883% 13.949%, 8.296% 12.189%, 10.086% 10.594%, 12.282% 9.174%, 
    14.91% 7.941%, 17.999% 6.907%, 21.574% 6.081%, 25.665% 5.476%, 
    30.298% 5.103%, 35.501% 4.973%, 41.3% 5.098%, 47.203% 5.4%, 
    52.69% 5.839%, 57.748% 6.483%, 62.364% 7.398%, 66.527% 8.649%, 
    70.225% 10.304%, 73.445% 12.429%, 76.175% 15.091%, 78.402% 18.355%);
}


📫 Contact Me:
1inboxna@gmail.com

