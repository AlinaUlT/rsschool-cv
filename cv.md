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
* [JavaScript Basics on Code Basics](https://ru.code-basics.com/languages/javascript)
* [JavaScript Manual](https://learn.javascript.ru/)
* [HTML Basics on Code Basics](https://ru.code-basics.com/languages/html)
* [CSS Basics on Code Basics](https://ru.code-basics.com/languages/css)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
## Languages:
* English C1 (I have been living in America for almost 5 years, I went to a local college (Sierra College at Rocklin Campus) and took first ESL courses, then Academic English course 1A level) 
* Russian - Native
