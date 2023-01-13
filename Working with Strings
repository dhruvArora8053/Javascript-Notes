/////////////////////////////////////////////////
//Working with Strings Part 1:
const airline = 'TAP Air Portugal';
const plane = 'A320';
console.log(plane[0]);
console.log(plane[1]);
console.log(plane[2]);
console.log('B737'[0]);

console.log(airline.length);
console.log('B737'.length);

console.log(airline.indexOf('r'));
console.log(airline.lastIndexOf('r'));
console.log(airline.indexOf('Portugal'));

console.log(airline.slice(4));
console.log(airline.slice(4, 7));

console.log(airline.slice(0, airline.indexOf(' ')));
console.log(airline.slice(airline.lastIndexOf(' ') + 1));

console.log(airline.slice(-2));
console.log(airline.slice(1, -1));

//Practical example:
const checkMiddleSeat= function(seat){
  const s= seat.slice(-1);
  if(s==='B'||s==='E'){
    console.log('You got the middle seat 😒');
  }else{
    console.log('You got lucky 🎉');
  }
}

checkMiddleSeat('11B');
checkMiddleSeat('23C');
checkMiddleSeat('2E');

//string is a primitive and primitives have no methods but our string has lots of them, it is because when we call a method javascript automatically converts string into an object and when the operations are done object is converted back to a regular string primitive.
console.log(new String('Jonas'));
console.log(typeof new String('Jonas'));

//and infact all string methods return primitives even if called on a string object.
console.log(typeof new String('Jonas').slice(1));
