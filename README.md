# Yue Zeng, zeng0057

```js
function calculateBMI(weight, height) {
  let myHeight = height * height;
  return weight / myHeight;
}
console.log(calculateBMI(90, 1.91));

let bmi = calculateBMI(90, 1.91);

function interpretBMI(bmi) {
  if (bmi < 18.5) {
    return "Underweight";
  }
  if (18.5 <= bmi < 25) {
    return "Normal weight";
  }
  if (25 <= bmi < 30) {
    return "Overweight";
  }
  if (bmi >= 30) {
    return "Obese";
  }
}
console.log(interpretBMI(bmi));

let bmi = calculateBMI(90, 1.91);
function interpretBMI(bmi) {
  if (bmi < 18.5) {
    return "Underweight";
  }
  if (18.5 <= bmi < 25) {
    return "Normal weight";
  }
  if (25 <= bmi < 30) {
    return "Overweight";
  }
  if (bmi >= 30) {
    return "Obese";
  }
}
console.log(interpretBMI(bmi));
```

![T3 Screenshot 2024-04-11 at 10.45.47 AM](./screenshot/T3-Screenshot.jpg)
![T4 Screenshot 2024-04-11 at 10.50.49 AM](./screenshot/T4-Screenshot.jpg)
![T5 Screenshot 2024-04-11 at 10.53.18 AM](./screenshot/T5-Screenshot.jpg)
