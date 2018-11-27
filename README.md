# _Caleb Ockwig's Computer Science Portfolio!_
<details> 
  <summary><b>Web Page</b></summary> 
  <a href="https://ockwigc.github.io/OckwigWebPage2/">Link!</a>
  
 
  <p> <b>About the Project</b> <br>I thought it was a good way to introduce HTML and CSS into the course. Some problematic areas were lining up the pictures and getting them to show correctly. Other than that I was able to use html to create bodies and headers, and even links to websites (I used the same things here for these links) Anyway, If you wanna see some good pictures of my dog! click it.</p>
  </details>
  <br>

  <details> 
  <summary><b> Lightning!</b></summary>
  <a href="https://ockwigc.github.io/lightning2/">Link!</a>
  <p> <b>About the Project</b> <br> I thought this project was fun. I had some tough time starting out but I figured it out and initally the 'lightning' was supposed to be one color but I thought it looked cooler with it being random and changing color so I kept it. Another feature I added was sthe ability to clear away the screen by making a simple button of if the mouse is clicked between X and Y and then just making the screen either black or white. </p>
  <p>
  </details>
  <br>

  <details><summary> <b>Dice</b> </summary>
  <a href="https://ockwigc.github.io/dice3/">Link!</a>
  <p> <b>About the Project</b> <br> This project was good at re-introducing the Math class and Math.random(). It was fun to make it random colors too. The most challenging part was making the counter. I initially had it as a void method but that wasn't changing the sum the way I wanted it to so I ended up changing it to an int method which solved my issue.</p>
  </details>
  <br>

  <details> <summary> <b>Chemotaxis </b></summary>
  <a href="https://ockwigc.github.io/chemotaxis4/">Link!</a>
  </details>
  <br>

  <details><summary><b> Starfield</b> </summary>
  <a href="https://ockwigc.github.io/starfield5/">Link!</a>
  <p> <b>About the Project</b> <br> This project offered more experience using the Math class such as Math.cos() and Math.sin(). The hardest part was getting the particles to bounce around the screen and using an interface. </p>
  </details>  
  <br>

  <details> <summary><b> College Presentation </b></summary>
<a href="https://docs.google.com/presentation/d/e/2PACX-1vTOROAp5601MPr28pQ-yjpbVH7zN_lOFOv4SHpJflWcWFjNYG-UB2A5JB_5MDFEKUerzCmiDd7gl286/pub?start=false&loop=false&delayms=3000">Link!</a>
  </details>
* ChallengingCode!

```Java
void mousePressed()
{   
  if (mouseX<300&&mouseY<200) {
    background(0);
    fill(255);
    text("click here for Black", 0, 50);

    text("click here for White", 600, 50);
  }

  if (mouseX>600&&mouseX<900&&mouseY<200) {
    background(255);
    fill(0);
    text("click here for Black", 0, 50);

    text("click here for White", 600, 50);
  }
  ```
