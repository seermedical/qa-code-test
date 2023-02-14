# qa-code-test

First of all, congratulations for making it through to the code test!

We really appreciate your time and interest in Seer. The test focuses on your scripting and test scoping skills. 

Below you'll find information to get you started.

### What language do I write in? 

Use the language you're most comfortable with. 

### How do I submit this code? 

1. Pull down this repo & get coding!
2. Once complete, zip all the files
3. Email the zip to the member of our peeps team who reached out to organise the test

### How long will this take? 

The tests are designed to take around 45 minutes and no more than 60 minutes. 
   
# QA Coding test

## 1 - Scripting

Create a new file called `scripting` in your preferred language.

Copy and paste the `patients` array into `scripting` 

Create a function `getPatientCreatedAfter`.

It takes one argument `date`

It returns a list of names of people that were created after `date`

e.g. `getCreatedAfter('2019-12-10') // returns ['Ervin Howell']`

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

## 2 - Write a helper function called getUrl()

Create a new file called `helpers` in your preferred language. 

The function, `getUrl`, takes one parameter `environmentVariable` and returns a string which is the corresponding URL for the specified environment 

| Environment name | URL | 
|---|---|
|production| https://my.website|
|uat | https://my.uat.website|

## 3 - Defining test scope 
This is a snapshot of our public facing website.  Create a new file called `test_scope.md` to get started. Make sure to document any assumptions you make about the image (e.g. its interactivity) in the process

1. Based on what you can see in the image, define the test scope
2. Identify which scenarios should be automated
3. With code or pseudo code, script one automated test


![Snapshot of Seer's public facing homepage](support_image/Seer_home_page.png)
