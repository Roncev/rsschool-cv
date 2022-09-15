## Matsvei Chystsik

### Contacts :

* Discord: Joint Left
* E-mail: moteoo@gmail.com

### About myself:
Once completed stage 1, but failed interview with mentor for stage 2 (СSS part was my bad).
Now trying to recollect what is it all about after ~4 years break.

### Code example: 
```// partition the items array so that all values for which pred returns true are
// at the end, returning the index of the first true value
function partitionOn(pred, items) {
let arr = []; //copy of items
for(var i in items) {
arr[i] = items[i]
}
let end = []; // array for true values
for (let i =0; i<arr.length; i++) { //looping through arr
  if (pred(arr[i])) {
    end.push(arr[i]) // push true value into end array
    arr.splice(i,1)  // remove ture value from initail array
    i-- //one step back
   }
 } 
let p  = arr.length; // position to return 
arr = arr.concat(end); // create final array
for (let j =0; j<arr.length; j++) { // replace all items in items
  items[j] = arr[j]
 }
 
return p
}
```
Источник <https://www.codewars.com/kata/525a037c82bf42b9f800029b/solutions/javascript?filter=me&sort=best_practice&invalids=false> 

### Work experience:
~ 6 years EPAM contractor as a Scientific Curation Specialist (Chemist)

### Education and courses:
* University of Gdansk: Medicinal Chemistry, Bachelor
* University of Gdansk: Virus Molecular Biology, Master

### Languages:
* English - unconfirmed B2 
* Polish - C1 (but not used for a long time)
