# Co-E

const dropdowns = document.getElementsByClassName("myDropdown");
let sum = 0;

for (let i = 0; i < dropdowns.length; i++) {
  const dropdown = dropdowns[i];
  sum += parseInt(dropdown.value);
}

console.log("The sum of the dropdown values is: " + sum);
