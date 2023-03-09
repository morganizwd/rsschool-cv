# ___MY FIRST EVER AC___

> # Lobanovsky Ilya
![Face Reveal](https://sun9-73.userapi.com/impg/k214DjVSQOfPGhrgrSEJeU_wEUsOmJp5mQU-dg/vux7krLKpdU.jpg?size=1620x2160&quality=95&sign=722ad6a8268dc02cb771da5c4b67305d&type=album)
> ## Age: 19
___
> ### My contacts:
* [Telegram](https://t.me/morganizwd)
* [VK](https://vk.com/lil_lame)
* [Instagram](https://www.instagram.com/morganizwd/)
* [YouTube](https://www.youtube.com/channel/UCvgAXL5C2zJhm_byyMeXePg)
* [GitHub](https://github.com/morganizwd)
* [GitLab](https://gitlab.com/morganizwd)
___
> ## About myself:
I am a student. At the moment I live in Belarus, the city of Mogilev. I am a second-year student of the Belarusian-Russian University majoring in Software Engineering. I have experience in software development that I gained through my study projects, mostly course projects. You can check them out in my [GitLab](https://gitlab.com/morganizwd) repository.
___
>### My Projects by disciplines
1. __Programming__ (___Finshed___)
    * Calculation of travel payments to employees
2. __Computer graphics__ (___Finshed___)
    * Poly Racer (*Computer game in the "racing" genre on the unity engine*)
3. __DataBases__ (____In progress____)
    * Calculation of the load on educational departments
___
>### My skills:
1. C# (CodeWars 4kuy)
2. T-SQL (Microsoft SQL Server, Microsoft Access)
3. Python (Basic skills)
4. C++ (Basic skills)

Previously participated in the course from Epam (AutoCode -  .net)
___
> ### English level: B1 (according to Epam english test)
___
![English level](https://sun9-71.userapi.com/impg/tR5bYCymFag4CmYkuDCjJ2KQCLIm3dXaiWkJkg/7kMKe7Bjp60.jpg?size=583x148&quality=96&sign=624c4c8e7ee56d0f8fab1e1ea57db3f2&type=album)
___
> ### Solved CodeWars katas (Code examples)
* Write a function that accepts an integer n and a string s as parameters, and returns a string of s repeated exactly n times.
```javascript
function repeatStr (n, s) {
  return s.repeat(n);
}
```
* Your job here is to write a function (keepOrder in JS/CoffeeScript, keep_order in Ruby/Crystal/Python, keeporder in Julia), which takes a sorted array ary and a value val, and returns the lowest index where you could insert val to maintain the sorted-ness of the array. The input array will always be sorted in ascending order. It may contain duplicates.
```javascript
function keepOrder(ary, val) {
  let index = 0;
  while (index < ary.length && ary[index] < val) {
    index++;
  }
  return index;
}
```
* Some numbers have funny properties. For example:
89 --> 8¹ + 9² = 89 * 1
695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2
46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51
Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p
we want to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k * n.
In other words:
Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k
If it is the case we will return k, if not return -1.
Note: n and p will always be given as strictly positive integers.
```javascript
function digPow(n, p){
  let digits = n.toString().split('');
  let sum = 0;
  for (let i = 0; i < digits.length; i++) {
    sum += Math.pow(parseInt(digits[i]), p + i);
  }
  let k = sum / n;
  return Number.isInteger(k) ? k : -1;
}
```
