# About Lumina
Lumina is an exploration into the vast narratives of the universe, where each celestial formation tells a unique story shaped by cosmic phenomena. This project captures and condenses the essence of these expansive temporal actions into singular, poignant moments for viewers. It vividly portrays gravitational lensing, the spacetime continuum, and the intricate fabric of space, showcasing the mesmerizing interplay of light and space as they are twisted and refracted by gravity.Lumina is not only a reflection of cosmic phenomena but also a metaphor for human exploration and discovery. As technology propels us further into space, this collection serves as an artistic parallel, emphasizing humanity's enduring quest to understand and connect with the cosmos.

# Making of Lumina

Lumina is a further exploration of using p5.js and WebGL shaders together to generate a striking visual style that maintains a balance between organic and digital elements. We employed a **serial** technique to structure the process.

n this project, we created basic shapes using `vertex()` & `curveVertex()` functions in p5.js. Later, these shapes were processed through an FBM (Fractal Brownian Motion) shader to create a cloudy texture. This cloudy texture was then passed into another shader, which applied a swirl effect to it. For the final process, we used a custom shader to manipulate the canvas, creating fractured and bent entities. 

## Detailed explanation of the **serial** process.

1. Creating shapes using `vertex()` & `curveVertex()` in p5js.

   ![step 1](assets/1_1.jpg) ![step 1](assets/2.jpg)

2. First shader; **FBM**

   ![step 2](assets/2_1v1.jpg) ![step 1](assets/2_2.jpg)
   
3. Second Shader; **Swirl**

   ![step 3](assets/3_1.jpg) ![step 1](assets/2_3.jpg)

4. Last Shader; **Spatialize**

   ![step 4](assets/4_1.jpg) ![step 1](assets/2_4.jpg)

5. Again adding *stars* on top of everything

   ![step 5](assets/5_1.jpg) ![step 1](assets/2_5.jpg)

## Compositions 

The visual structure contains 9 general composition type, each are highly varied, some examples;

* composition 1

![comp1](assets/comp1/comp1_1.jpg)![comp1](assets/comp1/comp1_2.jpg)![comp1](assets/comp1/comp1_3.jpg)

* composition 2

![comp2](assets/comp2/comp2_1.jpg)![comp2](assets/comp2/comp2_2.jpg)![comp2](assets/comp2/comp2_3.jpg)

* composition 3

![comp3](assets/comp3/comp3_1.jpg)![comp3](assets/comp3/comp3_2.jpg)![comp3](assets/comp3/comp3_3.jpg)

* composition 4

![comp4](assets/comp4/comp4_1.jpg)![comp3](assets/comp4/comp4_2.jpg)![comp4](assets/comp4/comp4_3.jpg)

* composition 5

![comp5](assets/comp5/comp5_1.jpg)![comp5](assets/comp5/comp5_2.jpg)![comp5](assets/comp5/comp5_3.jpg)

* composition 6

![comp6](assets/comp6/comp6_1.jpg)![comp6](assets/comp6/comp6_2.jpg)![comp6](assets/comp6/comp6_3.jpg)

* composition 7

![comp7](assets/comp7/comp7_1.jpg)![comp7](assets/comp7/comp7_2.jpg)![comp7](assets/comp7/comp7_3.jpg)

* composition 8

![comp8](assets/comp8/comp8_1.jpg)![comp8](assets/comp8/comp8_2.jpg)![comp8](assets/comp8/comp8_3.jpg)

* composition 9

![comp9](assets/comp9/comp9_1.jpg)![comp9](assets/comp9/comp9_2.jpg)![comp9](assets/comp9/comp9_3.jpg)


   

