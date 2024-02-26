### Statment
Mister Hamed is preparing a leaderboard for his top students.

He has an array of student objects where each student has the following properties:

```js
{
  name: '..',
  class: '..',
  grades: {
    math: [1 - 25],
    physics: [1 - 25],
    programming: [1 - 25],
    english: [1 - 25],
  }
}
```

Mister Hamed wants to filter the array to leave only students who got a total grade **greater than or equal to _85_**, he also wants to **add the `totalGrade`** property to each students in the returned array.

### Objective
Can you help mister Hamed to achieve his needs using at least two array method you've learned this week?

### Startup code
```js
const getLeaderBoard = (students) => {
  // do you magic
  return students;
}

const students = [
  {
    name: '3bkreem',
    class: '3rd',
    grades: {
      math: 25,
      physics: 25,
      programming: 25,
      english: 25
    }
  },

  {
    name: 'Samer',
    class: '3rd',
    grades: {
      math: 10,
      physics: 15,
      programming: 12,
      english: 19
    }
  },

  {
    name: 'Ahmed',
    class: '3rd',
    grades: {
      math: 20,
      physics: 20,
      programming: 20,
      english: 20
    }
  },

  {
    name: 'Ali',
    class: '3rd',
    grades: {
      math: 20,
      physics: 25,
      programming: 19,
      english: 22
    }
  },

  {
    name: 'Elgoker',
    class: '3rd',
    grades: {
      math: 23,
      physics: 25,
      programming: 19,
      english: 22
    }
  }
]

console.log(getLeaderBoard(students));
```