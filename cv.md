<<<<<<< HEAD
# Alina Ulasevich

## Contact information:
* **Location:** Krakow, Poland / Citrus Heights, Sacramento County, CA, USA
* **Phone:** +48 786 626-554 / 916-613-9454 (USA)
* **E-mail:** juliwu2517@gmail.com
* **GitHub:** https://github.com/AlinaUlT

## About Myself:
I started studying at RS School in December 2021 from stage 0. At the moment, I have moved to stage 1 and I strive to learn and continue to master the profession of a Front-End developer. I have already managed to work on one project to create a website for [Qualified Appliance Repair](https://www.qualifiedappliancerepair.net/).
### My strengths:
* Quick Learner
* Diligence
* Team Playing
* Сreativity

## Skills:
* CSS
* HTML
* JavaScript(basic)
* Git, GitHub
* VS Code

## Code example:
Consider an array/list of sheep where some sheep may be missing from their place. We need a function that counts the number of sheep present in the array (true means present).
```
function countSheeps(arrayOfSheep) {
 let result = 0;
 for (let i = 0; i < arrayOfSheep.length; i++){
   let sheepNumberI = arrayOfSheep[i];
   if (sheepNumberI === true) {
      result++;
    }
 } 
  return result;
} 
```
Next task: 
If you sort the arrays by their length, you will see, that their length-values are consecutive.
But one array is missing!
You have to write a method, that return the length of the missing array. 
If the array of arrays is null/nil or empty, the method should return 0.
When an array in the array is null or empty, the method should return 0 too!
There will always be a missing element and its length will be always between the given arrays.
```
function getLengthOfMissingArray(arrayOfArrays) {
  const lengths = (arrayOfArrays || [])
    .map(a => a ? a.length : 0)
    .sort((a, b) => a - b)
  
  if (lengths.includes(0)) {
    return 0
  }

  for (let i = 0; i < lengths.length - 1; i++) {
    if (lengths[i] + 1 !== lengths[i + 1]) {
      return lengths[i] + 1
    }
  }

  return 0
}
```
## Experience:
[Qualified Appliance Repair](https://www.qualifiedappliancerepair.net/)
## Education:
=======
## Alina Ulasevich
### Contact information:
* **Location:** Citrus Heights, Sacramento County, CA, USA
* **Phone:** +1 916-613-9454
* **E-mail:** juliwu2517@gmail.com
* **GitHub:** [AlinaUlT](https://github.com/AlinaUlT)
* **Codewars:** [AlinaUlT](https://www.codewars.com/users/rsschool_19d3afbbc16fcf7f)
### About Myself:

* Objective: Highly motivated junior developer with a foundation in JavaScript, TypeScript, and Angular framework. Eager to apply my skills in a professional environment and further enhance my understanding of front-end development.

As an aspiring front-end developer, I'm passionate about using my knowledge of HTML, CSS, and JavaScript to create a user-friendly and visually appealing web interface. While my industry experience is limited, my ability to learn quickly, combined with a rigorous self-learning regimen, has allowed me to lay a solid foundation in interface design principles.
I have a desire to constantly learn and improve. I understand that being a junior developer means not having anyone to teach me, but having the initiative and resourcefulness to learn from all possible sources. I am determined to pass on my passion for technology, my ability to learn quickly and my commitment to quality to a team where I can contribute and grow as a professional.

### Skills:
* Programming Languages: JavaScript, TypeScript(basics)
* Web Technologies: HTML, CSS, RESTful API
* Frameworks/Libraries: Angular, RxJS, NgRx (basic)
* Version Control System: Git
* Testing: Basic understanding of unit testing and end-to-end (E2E) testing using Jasmine, Karma, and Protractor.
* Others: MVC Design pattern, Responsive Web Design, Node.js, npm


### Code example:
```
function find(object, path) {
    return path.split('.').reduce((acc, pathName) => acc && acc.hasOwnProperty(pathName) ? acc[pathName] : undefined,object); 
}
```
```
const whosOnline = (friends) => {
let newObj = {}
let userStatus;
friends.forEach(eachFriend => {
  if(eachFriend.status === "offline"){
    userStatus = "offline";
  } else if(eachFriend.lastActivity > 10){
    userStatus = "away";
  } else {
    userStatus = "online";
  }
  if(!newObj[userStatus]){
    newObj[userStatus] = [];
  }
newObj[userStatus].push(eachFriend.username)
}) 
  return newObj;
}
```

### Experience:
* [Online Zoo](https://github.com/AlinaUlT/online-zoo)
* [Travel](https://github.com/AlinaUlT/travel) 
* [Gem Puzzle](https://github.com/AlinaUlT/gem-puzzle)
### Education:
* Sierra College at Rocklin Campus, CA; Major: Computer Science; Expected Graduation: 2025 
>>>>>>> rsschool-cv-html
* [JavaScript Basics on Code Basics](https://ru.code-basics.com/languages/javascript)
* [JavaScript Manual](https://learn.javascript.ru/)
* [HTML Basics on Code Basics](https://ru.code-basics.com/languages/html)
* [CSS Basics on Code Basics](https://ru.code-basics.com/languages/css)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
<<<<<<< HEAD
## Languages:
* English C1 (I have been living in America for almost 5 years, I went to a local college (Sierra College at Rocklin Campus) and took first ESL courses, then Academic English course 1A level) 
* Russian - Native
=======
* [IT Fundamentials](https://learn.epam.com/study/path?rootId=1471991)
### Languages:
* English - Fluent
* Russian - Native
>>>>>>> rsschool-cv-html
