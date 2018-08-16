# JourneyToTheFFT
A blog about my journey to learn Fourier algorithms and eventually implementing the FFT.  All animations are done on Matlab.  I know it seems like cheating to use Matlab, but its a really intuitive visualization software that easily manages complex numbers.  I'm still deciding whether to do the final implementation of the FFT in C or in some sort of WebGL or Javascript script that I can run in the browser.  

1. Correlation function by integration

2. Cross Correlation

3. Integral Transform

4. Convolution algorithm

5. The Fourier Series and its Motivations

  A key part that I never really understood, mostly because I am mathematically lazy, is that complex representations of functions ARE STILL REAL.  The Complex Fourier Series breaks down the input function into a sum of exponentials with increasing frequency.  Even though there are imaginary numbers in the function, the resulting values are REAL.  I'm still a noob at imaginary numbers, so my intuition isn't great at seeing that.

  Animations below show visualizations of the complex representation of sine and cosine functions.

  ![Alt text](https://user-images.githubusercontent.com/14359191/44233744-8debc400-a159-11e8-8b9f-04b88e5ae5b0.gif)
  ![Alt text](https://user-images.githubusercontent.com/14359191/44233746-8f1cf100-a159-11e8-99d6-87b6ad02e6db.gif)

6. Complex numbers, complex exponentials, and complex integrals

  I always found it difficult to understand mathematics without a visual representation of what
  my calculations were doing in a geometric sense.  Especially in engineering mathematics, many
  concepts have a very useful visual representation and I really wanted to explore complex numbers in this visual fashion.  It is not commonly taught this way in the university classroom, and I always felt that complex numbers were a mystery to me beyond simply memorizing Euler's formula and its identities.  

  It's kind of a "see it to believe it" syndrome that I have, and I feel like many other people feel.  I can't stress how eye-opening the 3blue1brown videos were to my understanding of complex numbers.  

  ![Alt text](https://user-images.githubusercontent.com/14359191/43619004-87a56382-9680-11e8-972a-0978d3b7bb3f.gif)

  ![Alt text](https://user-images.githubusercontent.com/14359191/43619005-88658054-9680-11e8-8309-5f689b2c7f0c.gif)

  Really weird stuff happens with complex numbers when you perform simple operations on them.

7. From Fourier Series to Fourier Transform

  ![Alt text](https://user-images.githubusercontent.com/14359191/44192223-796ce480-a0e3-11e8-9643-17ba3c2d3a90.gif)
