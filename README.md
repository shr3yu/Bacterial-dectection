Project requirements:

Using the STM-32 F401RE, students in ECE 198 were asked to build a prototype that would aid in solving an issue in the medical field.

The problem:

According to the study, “Degree of bacterial contamination on mobile phone and keyboard surfaces [...],” pathogenic bacteria can be found on almost all mobile and keyboard surfaces. 
In fact, out of the 25 phones that were tested, 92% were found to be contaminated with infectious bacteria. 

Mobile phones are near parts of the body that serve as common infection gateways, such as the hands, face, ears, nose, and lips.
Similarly, keyboards are one of the most commonly used interfaces, which are rarely disinfected. Hence, it's necessary to note that one’s failure to sanitize mobile 
and keyboard surfaces may eventually lead to developing a bacterial infection.

The solution:

Using the STM32CUBE-IDE, specific output, input, ground, and voltage pins were programmed such that once a mobile phone was placed inside an enclosed cardboard box, UV LED lights on a breadboard would illuminate the surface. Then, the OV5642 camera captures the illuminated phone. The image is put through an algorithm that detects color different from its background environment.
A percentage of the number of bacteria on the phone's surface is displayed on an LCD screen. 

Access the [design document](https://github.com/shr3yu/Bacterial-dectection/blob/main/Design%20document.pdf).
