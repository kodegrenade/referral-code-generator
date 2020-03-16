## Referral Code Generator

> A package that helps you generate referral code for your users.

#### Installation

```
npm install referral-code-generator
```

#### Usage

> Import or require the package

```javascript
import referralCodeGenerator from 'referral-code-generator'
```

```javascript
let referralCodeGenerator = require('referral-code-generator')
```

> Generating your referral code

```javascript
referralCodeGenerator(username, wordlength, numberlength, type)
```

```javascript
example 1: 

referralCodeGenerator('temitope', 4, 7, 'lowercase')

result: the above code will return the word 'temi' in lowercase and 7 random digits
```

```javascript
example 2: 

referralCodeGenerator('temitope', 3, 6, 'uppercase')

result: the above code will return the word 'tem' in uppercase and 6 random digits
```

> Parameters

```
username: This is your user's unique name.
```

```
wordlength: The number of alphabets you want to extract from the username to form the referral code.
```

```
numberlength: The number of random digits you want to generate.
```

```
type: The word case format you want. [uppercase, lowercase].
```