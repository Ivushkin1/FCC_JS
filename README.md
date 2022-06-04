# FCC_JS
const sum = 10 + 10;

const myArray = [18, 64, 99];
// Only change code below this line
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
