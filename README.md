# qa-code-test

First of all, thank-you for your interest in Seer!

This repo contains code problems designed for the QA hiring process. 

Please no more than 60 minutes on this test. You're time means a lot to us. 

Pull down this repo and branch of main. 

The branch naming convention is `test/<your_first_name>_<your_last_initial>`

If you haven't worked with git before, [here is a good overview](https://www.youtube.com/watch?v=USjZcfj8yxE) for beginners. And otherwise more specific videos: 
* [Download git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Clone a repo](https://www.youtube.com/watch?v=CKcqniGu3tA)
* [Make a branch](https://www.youtube.com/watch?v=snxybJkFeUo)
   
# Mid Level code testing

## Activity - Scripting

This activity contains scripting problems for you to demonstrate your knowledge of coding principles and test automation.

Create a new file called `scripting` in your preferred language.

Copy and paste the patients array into `sscripting` 
Create a function `getPatientCreatedAfter`.
It takes one argument `date`
It returns a list of names of people that were created after `date`
e.g. getCreatedAfter('2019-12-10T15:20:00.000000Z') // returns ['Ervin Howell']

```javascript
const patients = [
  {
    "id": 1,
    "name": "Leanne Graham",
    "username": "Bret",
    "email": "Sincere@april.biz",
    "phone": "1-770-736-8031 x56442",
    "createdOn":"2014-12-12T15:19:00.000000Z"
  },
  {
    "id": 2,
    "name": "Ervin Howell",
    "username": "Antonette",
    "email": "Shanna@melissa.tv",
    "phone": "(+61) 411 239 128",
    "createdOn":"2021-01-09T02:19:00.000000Z"
  },
  {
    "id": 3,
    "name": "Clementine Bauch",
    "username": "Samantha",
    "email": "Nathan@yesenia.net",
    "phone": "1-463-123-4447",
    "createdOn":"2016-05-07T11:35:00.000000Z"
  }
]
```

## Activity - Write a helper function called getUrl()

Create a new file called `helpers` in your preferred language. 
The function, getUrl, takes one parameter `environmentVariable` and returns a string which is the corresponding URL for the specified environment 

| Environment name | URL | 
|---|---|
|production| https://my.website|
|uat | https://my.uat.website|

## Activity - Defining test scope
This is a snapshot of our public facing website.  Create a new file called `test_scope.md` to get started. Make sure to document any assumptions you make about the image (e.g. its interactivity) in the process

1. Based on what you can see in the image, define the complete test scope
2. Identify which scenarios should be automated
3. With code or pseudo code, write out the automated test


![Snapshot of Seer's public facing homepage](support_image/Seer_home_page.png)
