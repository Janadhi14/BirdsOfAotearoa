# Birds of Aotearoa Website

<img width="1728" alt="Screenshot 2023-09-14 at 1 02 08 PM" src="https://github.com/Janadhi14/COSC203/assets/100277240/1ac3373d-03ca-45f7-8dea-f6e2a4c22e6f">
<img width="1728" alt="Screenshot 2023-09-14 at 1 01 56 PM" src="https://github.com/Janadhi14/COSC203/assets/100277240/92eb9184-b207-435d-8521-a75e96127499">

## Link to website:
https://disja508.cspages.otago.ac.nz/birdsnz


## Description 
This website contians information about NZ's birds and displays the birds in a grid based container with individual panels continaing infomraiton about the birds that is extracted through the use of JS from the nzbirds JSON file alsongside the corresponding images of that bird from various different photographers.
This website also contians the functionality for a dark and light mode toggle button on the top right which is able to change elements on the page to correspond with the selected theme, and references stored information on the users storage in order to remember what theme was used previously. Users are also able to filter thorugh the differnt birds. You are also able to click on the conservation status circles on the side panel which shows all the birds of the same conservation status.


## Additional functonality 
- have added a toggle dark and light mode for users using javascript and css with the toggle button on the top right for users to change the color scheme for the website  
- added hover functionality for aside compoements and panel elements for the birds where they pop out and brighten when hovering over with the mouse 
- added a favicon of a black kiwi
- added transitions for multiople compoenents so when loading the page elements to make it look smoother. 
- added functionality for clicking on the status circles and then using javascript function to go and filter and show all the birds of that status.



## Refernces:
- Darkmode functionality was referenced and implemented from: https://codepen.io/kevinpowell/pen/EMdjOV

- chatGPT assisted in generating comparator function in javascript as my initial implementation wasn't working properly "// simple comparator function
function createComparator(key, reverse = false) {
  return (x, y) => {
    const a = x[key];
    const b = y[key];
    // if the keys are in reverse
    if (reverse) {
      return a < b ? 1 : (a > b ? -1 : 0);
    }
    return a < b ? -1 : (a > b ? 1 : 0);
  };
}
//creating a nested comparator 
function createComparatorNested(key1, key2, reverse = false) {
  return (x, y) => {
    const a = x[key1][key2].value;
    const b = y[key1][key2].value;

    if (reverse) {
      return a < b ? 1 : (a > b ? -1 : 0);
    }
    return a < b ? -1 : (a > b ? 1 : 0);
  };
}" 
