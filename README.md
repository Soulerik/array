# array
function largestOfFour(arr) {
  // You can do this!
  function compareNum(a, b) {
    return a - b;
  }
  myArray = [];
    for (i = 0; i < 4; i++) {
    arr[i].sort(compareNum);
    myArray.push(arr[i][3]);
  }
  
  
  return myArray;
}

largestOfFour([[4, 5, 1, 3], [13, 27, 18, 26], [32, 35, 37, 39], [1000, 1001, 857, 1]]);
