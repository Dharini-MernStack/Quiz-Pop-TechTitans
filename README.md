TECH - TITANS QUIZ-POP
- ```src/index.html``` : This is the root HTML document/Homepage of the quiz page

 ```src/music.html``` : This is the  HTML documentwhich displays the music quiz questions
  ```src/music.js``` : Core logic of music quiz questions
   ```src/coding.css``` : This is the stylesheet on which styling for the elements and body was added.

   Similar files with same logic was added in all 3 categories

- ```src/api```: This folder contains scripts that provide a simulated backend that you can use in development, if needed. This is powered by Mock Service Worker (https://mswjs.io). If you're building data/remote API based apps, you can use this utility to simulate an API without actually building one during development. 
  - ```src/api/browser.js```: Please do not edit this file. It enables the use of Mock Service Worker.
  - ```src/api/routes.js```: This file may be edited to incorporate custom API routes for Mock Server Worker. By default, a root route (/) that returns a text message as a JSON object is present. You can learn more about MSW and how to define your own custom API routes for development by visiting https://mswjs.io/docs/

- ```src/public```: This folder contains the MSW utility file (mockServiceWorker.js) which should not be edited/removed. Any files you place in this folder can be directly accessed in your HTML document. Use this for placing static assets such as images. 

