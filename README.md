# FCC_JS
const sum = 10 + 10;

const myArray = [18, 64, 99];

myArray[0] =45

function testNotEqual(val) {
  if (val !=99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testNotEqual(10);
                                                  //04.06.22
const names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  if(strokes == 1){
  return "Hole-in-one!"
} 
  else if (strokes == par){
  return "Par"
  }
  else if (strokes <=par-2){
    return "Eagle"
  }
  else if (strokes == par-1){
    return "Birdie"
  }
  else if (strokes == par+1){
    return "Bogey"
  }
  else if (strokes == par+2){
    return "Double Bogey"
  }
  else if (strokes >= par+3){
    return "Go Home!"
  } 
 }
golfScore(5, 4);

                   function multiply(arr, n) {
                      if (n <= 0) {
                        return 1;                                             //Recursion
                      } else {
                        return multiply(arr, n - 1) * arr[n - 1];
                      }
                    }
                    
                                                arr.hasOwnProperty(prop)


                                                Math.floor(Math.random() * (max - min + 1)) + min
                                                
                                                Object.freeze(obj)              //changing the object will be rejected
                                                
                                     function howMany(...args) {}                //Буквально это значит: «собери оставшиеся параметры и положи их в массив».


