****
# Ekaterina Slizhewskaya
****
### Contacts

* Location: Minsk, Belarus
* Phone: +375 29 355 39 42
* E-mail: katjaslizhewskaja@yahoo.com
* GitHub: [Normandy72](https://github.com/Normandy72)
* Telegram: @katja_slizhewskaja


### About Me


I found myself in programming. I'm interested in JavaScript, HTML and CSS. I have a great desire to improve this way and maintain high quality product. I always work for the result.
### Skills


* C#, .NET Framework
* C++ (basic)
* OOP (principles, patterns)
* Python (basic)
* MySQL
* JavaScript
* HTML
* CSS
* Git, GitHub 
* Adobe Photoshop, Figma


### Code example


**Kata from CODEWARS (6 kyu)**: *The function 'fibonacci' should return an array of fibonacci numbers. The function takes a number as an argument to decide how many no. of elements to produce. If the argument is less than or equal to 0 then return empty array.*
```
function fibonacci(n) {
  let fibArray = [0, 1];
  if(n <= 0 || typeof n != 'number') return [];
  if(n === 1) return [0];
  for(let i = 2; i < n; i++)
    {
      fibArray.push(fibArray[i - 1] + fibArray[i - 2]);
    }
  return fibArray;
}
```
