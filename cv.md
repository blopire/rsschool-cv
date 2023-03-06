## Ranis Ferdinandovich
Junior Front-End Developer

## Contacts
* telegram: @blopire
* gmail: ranis.ferdinandovich@gmail.com

## About me
My goal is to become a front-end developer. I like to study and sit at books. I have no work experience, but I have a desire to start working in an IT company.

## Skills
* JavaScript
* HTML
* CSS

## Code Example
```javascript
function digPow(n, p) {
                            // convert values ​​to string to count each character
  let a = String(n);
  let b = String(p);
  let sum = 0;
  let averageValue;
                            // the sum of the value "n" raised to the power of "p"
  for (let i = 0; i < a.length; i++) {
    sum += (a[i]) ** (b++);
  }
                            // checking our expression
    averageValue = Math.round( sum / n )
    if ( averageValue * n === sum ) {
      return averageValue;
    } else {
      return -1;
  }
}
```