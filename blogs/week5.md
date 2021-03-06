**Finishing Up**
========================
<sup>*This is a blog entry from [License Plate Object Identification Blogs](http://chenyumin.com/p/license-plate-object-detection-5-finishing-up).*</sup>

This project is finished.  


The basic method for extracting the license plate region can be described by the following steps.
1. Input of the original image  
2. Normalization (Contrast Stretching)  
3. Identification of the blue vertical band to the left of the plate  
4. Edge detection  
5. Morphological operation  
6. Finding the license plate region  


Results:

| Original | Result |
| :---: | :---: |
| ![Original](./img/week5-reg1-original.jpg) | ![Output](./img/week5-reg1-output.jpg) |
| ![Original](./img/week5-reg2-original.jpg) | ![Output](./img/week5-reg2-output.jpg) |
| ![Original](./img/week5-reg3-original.jpg) | ![Output](./img/week5-reg3-output.jpg) |
| ![Original](./img/week5-reg4-original.jpg) | ![Output](./img/week5-reg4-output.jpg) |

         

<br>

------------------------
Previous: [Week 3: Edge Detection](./week3.md)  
Next: [Week 5: ...s](./week5.md)