<h1>
  <span style="background: #000000; color: #ffb749">
    rsschool-cv
  </span>
  <hr>
  <span style="background: #fff; color: #3b2f4f">
    Vadim Chervoniak
  </span>
</h1>

## Contacts
- Location: Ukraine, Kyiv region
- Phone: +380-933-789-883
- Email: vadim4web@gmail.com
- GitHub: [@vadim4web](https://github.com/vadim4web)

## About Me

I’m a 37 y/o full-stack developer from Ukraine with focus on vue, nuxt, react, node.js, and a polyglot in modern web technologies.

## Skills

- Frontend: Vue, React, JavaScript/TypeScript,
HTML5, CSS3/SCSS
- Backend: Nuxt.js, Node.js, PHP, Python
- Databases & APIs: SQL, RESTful APIs, GraphQL
- Tools & DevOps: Git, Bash, NPM, Google Cloud
Platform (GCP), AWS

## [Code example](https://www.codewars.com/kata/reviews/541c8b5e7e4b4c61e2000149/groups/6730adba30786694b28816ab)

```js

function digitalRoot(n) {
  // Base case: if n is a single-digit number, return n
  if (n < 10) {
    return n;
  } else {
    // Calculate the sum of the digits
    const sum = (n + '').split('').reduce((acc, cur) => acc + +cur, 0);
    // Recursive call with the new sum
    return digitalRoot(sum);
  }
}

```

