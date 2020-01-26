# Defanging-an-IP-Address
LeetCode Challenge - Javascript


// iterate and search through each character until it finds a "."
// use regex
// then replace it with "[.]"
// return output with the brackets in place

function defangIPaddr(address) {
  return address.replace(/\./g, '[.]');
}
