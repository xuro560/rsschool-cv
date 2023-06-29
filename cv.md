
# CV Zhukesheva Anel

=

**Address**: Kazakhstan, Astana

**E-mail**: xuro560@gmail.com

**Telegram**: @xurozuro

**Github**: 
-

## About me

I love reading and exploring new things.

### How it started

From developing apps on C++ and C# in college to learning JavaScript at home. All thanks for [Diana Smith](https://diana-adrianne.com/) - her distinguished skills inspired me to start my own journey in Frontend development!

### Ultimate goals

- [x] Create own repository to save JavaScript cheatcodes and completed tasks on [Leetcode](https://github.com/xuro560/kataPreparing)
- [ ] Create Landing page with portfolio
- [ ] Create Calculator app on JavaScript

-

## Skills

### Software

* JavaScript
* HTML
* CSS, SCSS
* Git
* MySQL

### Other
* Google Workspace
    + Google documents
    + Google sheets
* Microsoft Office
    * Word
    * Excel
    * Visio

* Adobe Photoshop - graphic design
* QlikSense - analytics
* Miro - boarding and diagrams
* Bitrix24 - administration, development

-

## Education

### Siberian Automobile and Highway University
    2016 - 2020
    Automated information processing systems and management
### Almaty College of Energy and Electronic Technologies
    2013 - 2016
    Management

## Codewars task [TwoSum](https://www.codewars.com/kata/52c31f8e6605bcc646000082/train/javascript)

Case: Write a function that takes an array of numbers (integers for the tests) and a target number. It should find two different items in the array that, when added together, give the target value. The indices of these items should then be returned in a tuple / list (depending on your language) like so: (index1, index2).


Code:

```
function twoSum(numbers, target) {
   let array = [];
    for (let i = 0; i < numbers.length; i++) {
 
        for (let j = i+1; j < numbers.length; j++) {
            if (numbers[i] + numbers[j] === target) {
                array.push(i);
                array.push(j);
            }
        }
        
    }
    return array;
}
```

