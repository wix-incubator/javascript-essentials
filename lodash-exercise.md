#Lodash Workout

##Some Tutorials
- [lodash Docs](https://lodash.com/docs)
- [Intorduction to lodash (video)](https://egghead.io/lessons/core-javascript-introduction-to-lodash)
- [Applicative Programming In JavaScript With lodash.js](http://tech.pro/tutorial/1611/functional-javascript)
- [More tutorials here](http://bit.ly/1xSVC8R)

##The Excercise

Given this **person** schema:
```javascript
 {
	firstName: string,
	lastName: string,
	age: number,
	skills: ['run', 'jump', 'swim', 'dance'],
	gender: string (male / female),
	married: boolean
}
```
adult schema extends person with:

```javascript
children: {  // an object with key-value pairs, as firstName: person
	'childName': {person},
	'childName': {person},
	etc...
}
```

Given an array of adults perform the following tasks using lodash. Note that each task is a separate problems:

1. filter by age under 30 and has the skills 'run' and 'swim'.
1. filter by children who can swim or dance, and sort by gender and age.
1. get an array of population, which contains all the people (adults and children) in the array.
1. filter by people who have daughters and are not married.
1. filter by married people who can jump.
1. filter by people who have last name that starts with 'j' or later in the alphabet, and have married children.
1. change the collection so that the name of each person is: 
name:  ```{first: 'string', last: 'string'}```
1. instead of firstName and lastName
1. get an array of all children
1. get an array of just the ages: 
Let's say you want to do something when a certain event occurs. However, the event is fired very often when it happens. For example, when dragging something or scrolling, you want to perform some complex action, but you don't want it to happen so many times since it will slow down the UI.
1. Create a function ```doSomething``` which will only execute at most 1/x times.
1. Create a function which will only execute 1/x seconds.
1. Given a function,  ```get(url, data, successCallback)``` , create a function that will perform the get, but will always use a given url 'baseUrl' and specified data 'someData'.



