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
* [JavaScript Basics on Code Basics](https://ru.code-basics.com/languages/javascript)
* [JavaScript Manual](https://learn.javascript.ru/)
* [HTML Basics on Code Basics](https://ru.code-basics.com/languages/html)
* [CSS Basics on Code Basics](https://ru.code-basics.com/languages/css)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
* [IT Fundamentials](https://learn.epam.com/study/path?rootId=1471991)
### Languages:
* English - Fluent
* Russian - Native

