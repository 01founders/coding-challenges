Coding Challenges — Code It Like a Pro

Welcome to a set of fun and practical coding challenges designed to sharpen your skills!
You can solve these challenges in any language you like, but we highly encourage using Go (Golang) for that extra punch of performance and simplicity.

You have 30 minutes to complete all the tasks. Please refrain from using AI tools or searching Google for solutions. The goal is to test your coding skills and problem-solving abilities without relying on external help.
A staff member will be around to check your code and verify that the output is correct.

🟢 Challenge I: Hello
Description:
The classical introductory exercise. Just say "Hello, World!".

Objective:
Write a function that returns the string:
"Hello, World!"

Details:
This is the traditional first program when learning a new language.
Focus on understanding function structure and basic output.

Usage:
go
Copy
Edit
HelloWorld() ➞ "Hello, World!"

🍓 Challenge II: fruitCheckout
Description:
Jack is shopping for fruits at the grocery store. The shop only accepts cash, so he needs to calculate the total cost before heading to the ATM.

Objective:
Create a function that returns the total price in pence based on the fruit type and quantity.

Fruit Prices:
Apple: 15p per item

Banana: 20p per item

Mango: 22p per item

Kiwi: 18p per item

Strawberry: 20p per item

Function Signature:
go
Copy
Edit
fruitPrice(fruitName, quantity) -> int
Usage:
go
Copy
Edit
fruitPrice("Strawberry", 5) ➞ 100  
fruitPrice("Mango", 3) ➞ 66

🐦 Challenge III: birdCounts
Description:
You're a passionate bird watcher, and you've been recording how many birds visit your garden each day. You’ve recently digitized your daily bird counts and now want to analyze your data.

Objective:
Create a function that accepts an array of bird counts (one per day) and returns the total number of birds recorded.

Function Signature:
go
Copy
Edit
sumBirds(...counts) -> int
Usage:
go
Copy
Edit
sumBirds(2, 5, 0) ➞ 7  
sumBirds(3, 3, 3, 3) ➞ 12  
sumBirds() ➞ 0

⚡️ Challenge IV: isPowerOf2
Description:
You need to determine whether a number is a power of 2. A number is a power of 2 if it can be written as 2^n (e.g., 1, 2, 4, 8, 16, 32, ...).

Objective:
Create a function that accepts any number of integers and returns an array of booleans — true if the number is a power of 2, false otherwise.

Function Signature:
go
Copy
Edit
isPowerOf2(...numbers) -> []bool
Usage:
go
Copy
Edit
isPowerOf2(64, 513, 512) ➞ [true, false, true]  
isPowerOf2(1024) ➞ [true]  
isPowerOf2(3, 6, 7) ➞ [false, false, false]

🚀 How to Submit
You need to complete all the challenges within 30 minutes.

Solve the challenges in Go (preferably), or in any language you're comfortable with.

Create a separate file for each task in the same repository, named according to the challenge (e.g., hello.go, fruit_checkout.go, etc.), and include your solution in that file.

Once you've completed the task, a staff member will come to check your code and ensure that the output is correct.

Happy hacking! 💻🔥
Got questions or suggestions? Open a PR or raise an issue.
