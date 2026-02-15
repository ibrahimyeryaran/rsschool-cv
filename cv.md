# İbrahim Yeryaran

## Contacts

**E-mail:** ibrahimyeryaran@gmail.com<br/>
**Telegram:** @ibrahimyryrn<br/>
**GitHub:** [ibrahimyeryaran](https://github.com/ibrahimyeryaran)

## About Me

I am a conscientious person who works hard and pays attention to details. I am flexible, quick to pick up new skills and eager to learn from others. I also have lots of ideas and enthusiasm.

## Skills

- HTML5, CSS3, SASS
- js, React, Next js
- Git/GitHub
- NPM, Webpack
- VS Code, WebStorm
- Figma

### Code Example

```javascript
export default function promiseAll(iterable) {
  return new Promise((resolve, reject) => {
    const results = new Array(iterable.length);
    let unresolved = iterable.length;

    if (unresolved === 0) {
      resolve(results);
      return;
    }

    iterable.forEach(async (item, index) => {
      try {
        const value = await item;
        results[index] = value;
        unresolved -= 1;

        if (unresolved === 0) {
          resolve(results);
        }
      } catch (err) {
        reject(err);
      }
    });
  });
}
```

## Education

- **University:** Ege University - Mathematics and CS

## Training & Certificates

The Complete Javascript Course, Udemy (Jonas Schmedtmann), 2024
The Ultimate React Course, Udemy (Jonas Schmedtmann), 2024
Understanding Typescript, Udemy (Maximilian Schwarzmüller), 2024
React Native - The Practical Guide (Maximilian Schwarzmüller), 2024
RS School JS/FE Course English (https://app.rs.school/certificate/pjy9nke8), 2025

## Languages

- Turkish - Native
- English - Intermediate
