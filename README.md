# คู่มือการใช้งาน calculator

- สามารถบวกเลขได้
- ลบได้
- คูณได้

## วิธีใช้งาน

ต้องลง NodeJS ก่อน [สามารถดาวน์โหลดได้ที่นี่](https://nodejs.org/en/)

วิธี require module
```js
const calculator = require('calculator-katesuphapan')
```

### วิธีการบวก
การบวกให้ใช้ function `plus`
```js
calculator.plus(1,2) 
```