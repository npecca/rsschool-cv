# About Myself

Hello! I'm Mark, currently residing in the beautiful city of Brest. I am a student at the BSU Physics Faculty, always curious and eager to learn new things. My interests have led me to explore the field of programming, a discipline where I can constantly learn and solve problems. I am quick to pick up new skills and am ready to dive into any challenge.

- Email: <mark.karynos@gmail.com>
- LinkedIn: [Click!](https://www.linkedin.com/in/mark-karunas-0514381b8/)
- Telegram: @npecca
- Discord: npecca

# My Skills

## Programming Languages 

- Familiar with JavaScript
- Some knowledge in C
- Basic knowledge of HTML/CSS

## Tools and Concepts 

- Understanding of basic data structures and algorithms
- Familiarity with Git and GitHub for version control

## Soft Skills

- Problem-solving skills
- Attention to detail
- Ability to learn quickly

# Languages I Speak

- Russian: Fluent
- English: Intermediate level

# Code Example
Here's my solution to the following [kata](https://www.codewars.com/kata/55c04b4cc56a697bb0000048/javascript) from codewars:
```javascript
function scramble(str1, str2) {
  const str1Counts = [...str1].reduce((counts, char) => (counts[char] = (counts[char] || 0) + 1, counts), {});
  const str2Counts = [...str2].reduce((counts, char) => (counts[char] = (counts[char] || 0) + 1, counts), {});

  return Object.keys(str2Counts).every((char) => str1Counts[char] >= str2Counts[char]);
}
```