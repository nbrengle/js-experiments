FIRST NAME : Nathaniel  
LAST NAME : Brengle  
GITHUB URL :  
* Part 1 : https://github.com/nbrengle/js-experiments  
* Part 2 : https://github.com/nbrengle/js-set-array-subclass
* Part 3 : https://github.com/nbrengle/angular-simple-email-lookup
TODAYS DATE : 16 September 2017  
CSC 436  
HOMEWORK : #2  
COMPLEXITY: Medium  
APPROX HOURS INVESTED IN ASSIGNMENT :  
* Part 1: ~4  
* Part 2: ~8
* Part 3: ~6
EXPECTED GRADE : A-  
PARTICIPATION SOURCE CODE :  
* Angular Reddit Clone Complete @ https://github.com/nbrengle/angular-reddit-clone
* React Timer App @ https://github.com/nbrengle/react-timer-app
> React participation assignment included as my "going above and beyond"  

APPLICATION INTENT :  
* Part 1 : To demonstrate the differences between pure JS and jquery  
> I probably spent _way_ too long on this. I found myself compulsive about righting wrongs from the previous assignment and dedicated a lot of time to making the functions more composable  
> Sort Alphabetical and Remove Symbols are not reversible  
> The gray color cannot be restored after Random Color is called.
* Part 2 : To implement a pure js version of the Set data structure w/o using Es6's `Set`  
> Also spent way too long on this one  
> I got very hung up on doing this as an extension of Array and proving that it worked. This is all well and good, but my first pass through testing using AVA was replete with extensive failures of the configuration variety; apparently I can't get babel to transpile extensions of builtins no matter how many babel-plugins I throw at the problem. I eventually settled on a jank mechanism of using `console.assert()` because I'd already spent way too much time trying to do something more elaborate.   
> While I gained the ability to make an arbitrary set, it's also possible to use Array mechanisms to violate the uniqueness constraint ... and I didn't really show off using `typeof`. I'm definitely over-thinking things like this.
* Part 3 : Simple email search app (angular)  
> Did it simply in one component for simplicity. Most of the time spent was chasing down a red herring because `console.log(classList)` returns `undefined` because `console.log(Object)` is `undefined`. The email json is explicitly not included in the github version for privacy concerns. This zipped version should work as expected.

TO RUN :  
* Part 1 : Open the HW2-Part1.html page in browser
* Part 2 : Navigate to js-set-array-subclass. Run `npm start` and then run `node index.js` to see the final data structures
* Part 3 : Navigate to angular-simple-email-lookup. Run `ng serve`. Type in a name.
