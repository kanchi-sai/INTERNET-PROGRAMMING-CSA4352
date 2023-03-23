function findLCM(num1, num2) {
  let maxNum = Math.max(num1, num2);
  let lcm = maxNum;
  
  while (true) {
    if (lcm % num1 === 0 && lcm % num2 === 0) {
      return lcm;
    }
    lcm += maxNum;
  }
}

// Example usage:
console.log(findLCM(12, 18)); // Output: 36
