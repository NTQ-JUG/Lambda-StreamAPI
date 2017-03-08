# Lambda-StreamAPI

# Content
## Lambda Expression
* What is Lambda Expression?
* Functional interfaces?
* Why do we need lambda expressions?

## [Stream API](https://github.com/studyindepth/fpjava/blob/master/notes/streams.md)
* What is a Stream?
* How streams change our way of programing and make our code better?
    * common operations on collections: using streams vs for-loop
  
## Exercise 1
* Given two collections of interested topics, e.g: Java Stream API, Java Concurrency, Object-Oriented Programming,...
    * one collection maintains currently intersted topics (of a person)
    * one collection contains newly updated interested topics (a person may edit their interested topics)
    * a Topic has an unique id, a name, a description

* Find out all 
    * newly added interested topics
    * updated interested topics
    * deleted interested topics
   
## Exercise 2
 * Given a list of programmers in a company
    * a Programmer has id, division, team, gender, name
 *  Process the list and categorize programers into divisions, as below:
 
```javascript
{
  "division_1": [
    "Programmer 1",
    "Programmer 2",
    "Programmer 3",
    "Programmer 4"
  ],
  "division_2": [
    "Programmer 5",
    "Programmer 6",
    "Programmer 7"
  ]
}
 ```
 *  Process the list and categorize programers into divisions, then teams, then genders, as below:
 
```javascript
{
  "division_1": {
    "java": {
      "male": [
        "Programmer 1",
        "Programmer 2",
        "Programmer 3"
      ],
      "female": [
        "programmer 4"
      ]
    },
    "php": {
      "male": [
        "Programmer 5, Programmer 6"
      ],
      "female": [
        "Programm 7"
      ]
    }
  }
}
 ``` 
## Note
Please create a github account and fork this repository and start the study and do the exercises. When you're done just send a [pull/merge request](https://help.github.com/articles/about-pull-requests/) to this repo.

    
