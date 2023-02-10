# qa-code-test

First of all, thank-you for your interest in Seer!
This repo contains code problems designed for the QA hiring process. 

Please only spend 30-60 minutes on this test. You're time means a lot to us. 

Pull down this repo and branch of main. The branch naming convention is `test/<your_first_name>_<your_last_initial>`

If you haven't worked with git before, [here is a good overview](https://www.youtube.com/watch?v=USjZcfj8yxE) for beginners. And otherwise more specific videos: 
* [Download git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Clone a repo](https://www.youtube.com/watch?v=CKcqniGu3tA)
* [Make a branch](https://www.youtube.com/watch?v=snxybJkFeUo)
   
# Mid Level code testing

## Activity - Scripting

This activity contains four scripting problems for you to demonstrate your knowledge of coding principles. They're designed to be fairly quick responses so don't overthink them.  

1. Create a new file called `scripting`. Write in any language or create as `.md` if you're using pseudo code. 
2. Copy and paste the problems below into the scripting file. Then you can start coding.

```javascript

// 1. Log the 3rd item in the animals array
const animals = ['possum', 'koala', 'platypus', 'quokka']

// 2 Concatenate the strings below
const stringOne = 'A picture is worth'
const stringTwo = '1000 words'

// 3 Create a function `getProp` that takes the argument `keyName` and returns that property for each item in the `people` array

const people = [
  {
    "name": "Leia Organa",
    "height": "150",
    "mass": "49",
    "hair_color": "brown",
    "skin_color": "light",
    "eye_color": "brown",
    "gender": "female",
    "created": "2014-12-10T15:20:09.791000Z"
  },
  {
    "name": "R2-D2",
    "height": "96",
    "mass": "32",
    "hair_color": "n/a",
    "skin_color": "white, blue",
    "eye_color": "red",
    "gender": "n/a",
    "created": "2014-12-10T15:11:50.376000Z"
  },
  {
    "name": "Luke Skywalker",
    "height": "172",
    "mass": "77",
    "hair_color": "blond",
    "skin_color": "fair",
    "eye_color": "blue",
    "gender": "male",
    "created": "2014-12-09T13:50:51.644000Z"
  }
]

// 4 Keep count!

//The code below has bugs. It's not working! Can you debug or make suggestions to fix it? 

const researchAtSeer = `Medical technology is stronger when research shapes its development — that’s why our Seer Research team works alongside all teams at Seer. Seer researchers are renowned in the industry and pioneers in world-first seizure risk forecasting technologies.`

function countSeer(str){
    const myArr = str.split('  ')
    const my_count = 0

    myArr.forEach((word) => {
        if(word.contains('s')) myCount ++
    })

    return my_count
}


console.log(countSeer(researchAtSeer)) // expecting 3
```

## Activity - Write a helper function called getUrl()

1. Create a new file called `helpers`. Write in any language or create as `.md` if you're using pseudo code. 
2. The function, getUrl, takes one parameter `environmentVariable` and returns a string which is the corresponding URL for the specified environment 

| Environment name | URL | 
|---|---|
|production| https://my.production.website|
|uat | https://my.uat.website|

## Activity - Defining test scope

1. This is a snapshot of our public facing website. Based on what you can see in the image, define a test scope.
2. Create a new file called `test_scope.md` to get started.


![Snapshot of Seer's public facing homepage](support_image/Seer_home_page.png)
