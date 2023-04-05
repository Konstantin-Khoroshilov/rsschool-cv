# Konstantin Khoroshilov

## Contact information
**Phone:** +7 977 8450755  
**E-mail:** manly41142009@yandex.ru  
**Github:** github.com/Konstantin-Khoroshilov  
**Discord:** K (@Konstantin-Khoroshilov) 

## Briefly About Myself:
My career had started and continues in commercial bank. This work has many advantages, but I don't consider it as my vocation.

I have been interested in frontend development even before it became mainstream. I once asked myself about hackers. Who are hackers and how do people become hackers? After a little research on the Internet, I found an advise. One of the authors of the internet articles suggested to start coding with HTML, CSS and Javascript. This is where my journey begins. I really enjoyed designing web-sites because you only need a few lines of code to get visible results. It was nice to create something interesting and see how my code works. I have completed several free tutorials and then I made couple of applications for my bank job. When I demonstrated my applications to my colleagues I got good feedback. Colleagues said that my apps are really useful so I dicided to go ahead and add some features to improve them. I felt inspired every time I started writing code and worked with great pleasure.

Soon I saw information about training course from Yandex.Practicum. With this course, I could become junior frontend developer as the authors said. Since I like programming so much I thought  it is a good idea to get paid for it. Looks like I was expecting too much from  this course.

I had successfully completed the Web Development training course but couldn't find a job for two months. My enthusiasm and confidence gone. Disappointment knew no bounds. So much so that I haven't done development for two years.

Nevertheless, I decided to return to development and take a course from RSS. I know this course is difficult. But I have experience, the skill of perseverance, patience and love for programming, so I intend to complete the course and not stop there.

## Skills and proficiency
* HTML5, CSS3
* JavaScript ES6
* React
* Node.js
* Express.js
* PostgreSQL
* Git
* Figma
* VS Code, WebStorm

## Code example
RGB To Hex Conversion

```javascript
function rgb (r, g, b) {
let result = '';
const hexNumerals = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 'A', 'B', 'C', 'D', 'E', 'F'];
Array.from(arguments).forEach(argument => {
  argument = argument > 255 ? 255 : argument;
  argument = argument < 0 ? 0 : argument;
  result += `${hexNumerals[Math.floor(argument / 16)]}${hexNumerals[Math.floor(argument % 16)]}`;
});
return result;
}
```

## Study work experience
- Landing page called "Learn to learn" created with HTML5, CSS, Flexbox Layout, CSS-animations, Git, BEM methodology.  
[GitHub Link](https://github.com/Konstantin-Khoroshilov/how-to-learn)

- Landing page called "Russian travel". Here, in addition to the technologies mentioned earlier, non-standard fonts were used; adaptive layout according to layouts from Figma; media queries and grid layout.  
[GitHub Link](https://github.com/Konstantin-Khoroshilov/russian-travel)

- Landing page called "Mesto" that works with Javascript. The project is working with the DOM; event listeners were used; created "live" form validation; used an object-oriented approach and classes; configured interaction with the API;
the code is divided into modules and assembled using Webpack; the babel, autoprefixer and cssnano plugins are additionally installed via npm.  
[GitHub Link](https://github.com/Konstantin-Khoroshilov/mesto)

- Application on React. Used functional components, hooks, work with the API.  
[GitHub Link](https://github.com/Konstantin-Khoroshilov/mesto-react)

- Application called "Mesto" on React + backend on Express + MongoDB database. Implemented registration, authorization, work with local storage, information about users and the cards they add is stored in the database. Frontend and backend communicate via REST API.    
[GitHub Link](https://github.com/Konstantin-Khoroshilov/react-mesto-api-full)

- Application called "Movies-Explorer": a service where you can find movies on demand and save them to your personal account. The frontend is built on React, makes REST API requests, implements registration, authorization, protects routes with authorization, validates data in forms, displays errors from the server, stores user data in a global state variable, and the token in localStorage, filters movies by user request , allows you to like and save movies.  
[GitHub Link](https://github.com/Konstantin-Khoroshilov/movies-explorer-frontend)  
The backend is built on Express and MongoDB. It handles routes to store and update user and movie data. Some routes are protected by authorization. Implemented logging, error handling, request validation, encrypted password storage, rights control.   
[GitHub Link](https://github.com/Konstantin-Khoroshilov/movies-explorer-api)

## Education
**PLEKHANOV RUSSIAN UNIVERSITY OF ECONOMICS**  
Bachelor's degree in economics

**Independent non-profit organization of continuing professional education "School of data analysis" (Yandex.Practicum)**  
The Web Development training course as offered by Yandex.Practicum (560 hours)

## English language
Level A2   
Studied English at school and university.    
I practiced English at work when I communicated with clients - representatives of international companies on issues related to servicing organizations in a bank.
