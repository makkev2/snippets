## Destructuring
```javascript
const person = {
  first: 'Evan',
  last: 'Yank',
  country: 'USA',
  city: 'New York',
  links: {
    social: {
      twitter: 'https://twitter.com/yanke',
      facebook: 'https://facebook.com/yanke',
    },
    web: {
      blog: 'https://ey.com'
    }
  }
}

const { twitter, facebook } = person.links.social;
console.log(twitter, facebook);
```
