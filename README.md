var number = prompt("Give me numer, the randomness will be from 1 to yours number");
parseInt(number);
var randomNum = Math.random()*number + 1;
randomNum = Math.floor(randomNum)
document.querySelector('main').innerHTML = `Your random number is ${randomNum}`;
                       
