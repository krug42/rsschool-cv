# Alexandr Smirnov
## Contacts
- **Location**: Arkhangelsk, Russia
- **Telegram**: [@krug42](https://t.me/krug42)
- **Email**: [smrnv42@gmail.com](smrnv42@gmail.com)
- **GitHub**: [krug42](https://github.com/krug42)
- **Discord** rs-school server nickname: *Alexandr (@krug42)*  

## About me
I am 29 years old, was always inspired by fast and well-looking interfaces, so some years ago (5 to be precise) I tried to get in frontend profession, but failed. Now relearning and retrying to enter the profession, hope this time i will get more luck!  
I hope my strengths are healthy perfectionism and ability to find connect with different people, providing comfortable, toxicity excluded communication with them.

## Skills
- Core JS
- HTML/CSS with pre/post-processing, using BEM methodology
- git
- Basic node.js  
#### Wish to learn:
- TypeScript
- Webpack and other modern build tools
- React and its ecosystem as a primary framework
- Vue, Preact, Svelte as a secondary
- ReactNative and other crossplatform frameworks
- Tailwind
- Testing tools (mocha, jest, puppeteer)
- Data visualization libraries
- Canvas and WebGL libraries
- Advanced node.js
- Docker

## Pet projects and code examples
- [Test task](https://github.com/krug42/test-apptech) for [Apptech](https://career.habr.com/companies/applied-technologies) - simple payment calculator written on React
- Solution for [Steps in Primes codewars kata](https://www.codewars.com/kata/5613d06cee1e7da6d5000055):  
```js
function isPrime(n) {
  for (let i = 2, s = Math.sqrt(n); i <= s; i++) {
    if (n % i == 0) return false;
  }
  return n > 1;
}


function step(g, m, n) {
  const arr = [];
  for (let i = m; i <= n; i++) {
    if (isPrime(i)) arr.push(i);
  }
  for (let i = 0; i < arr.length - 1; i++) {
    for (let j = 1; j < arr.length - i; j++) {
      if (arr[i + j] - arr[i] == g) return [arr[i], arr[i + j]];
    }
  }
  return null;
}
```

## Education
[Northern (Arctic) Federal University](https://narfu.ru/en/), Applied informatics bachelor, 2012-2016.

#### Courses and learning materials
- [javascript.info](https://javascript.info) - I believe the best javascript guide at the time
- [HTML Academy](https://htmlacademy.ru/) - interactive guide to HTML and CSS
- [RS.school](https://rs.school) Frontend Stage 1 course *in progress*

## Languages
- **Russian** - native
- **English** - B1. Fluent in reading and listening, a lack of practice in speaking and writing
