# Time-Complexity-and-Big-O-Notation

An analogy to a real-life issue:

* This morning I wanted to eat some pizza; So, I asked my brother to get me some from Dominos, which is 3 km away.

* He got me the pizza, and I was happy only to realize it was too little for 29 friends who came to my house for a surprise visit!

* My brother can get 2 pizzas for me on his bike, but pizza for 29 friends is too huge of an input for him, which he cannot handle.

![image](https://github.com/Rizwanahmad07/Time-Complexity-and-Big-O-DAY01/assets/110217443/e3c67863-ce42-4b03-8641-38ac8bbfe6f2)

What is Time Complexity?

Time Complexity is the study of the efficiency of algorithms. It tells us how much time is taken by an algorithm to process a given input.

Time Complexity: Sending GTA 5 to a friend: 

* Imagine you have a friend who lives 5 km away from you. You want to send him a game. Since the final exams are over and you want him to get this 60 GB file worth of game from you. How will you send it to him in the shortest time possible?

* Note that both of you are using JIO 4G with a 1 Gb/day data limit.

* The best way would be to send him the game by delivering it to his house. Copy the game to a hard disk and make it reach him physically.

* Would you do the same for sending some small-sized game like MineSweeper which is in KBS of size? Of Course no, because you can now easily send it via the Internet.

* As the file size grows, the time taken to send the game online increases linearly – O(n) while the time taken by sending it physically remains constant. O(n0) or O(1).

Calculating Order in terms of Input Size:

In order to calculate the order(time complexity), the most impactful term containing n is taken into account (Here n refers to Size of input). And the rest of the smaller terms are ignored.

Let us assume the following formula for the algorithms in terms of input size n:

![image](https://github.com/Rizwanahmad07/Time-Complexity-and-Big-O-DAY01/assets/110217443/9020fc4f-c5a3-4101-9c51-952ba2875390)

Here, we ignored the smaller terms in algo 1 and carried the most impactful term, which was the square of the input size. Hence the time complexity became n^2. The second algorithm followed just a constant time complexity.

* Note that these are the formulas for the time taken by their program.

What is a Big O?

* Putting it simply, big O stands for ‘order of’ in our industry, but this is pretty different from the mathematical definition of the big O. Big O in mathematics stands for all those complexities our program runs in. But in industry, we are asked the minimum of them. So this was a subtle difference.

Visualizing Big O:

* If we were to plot O(1) and O(n) on a graph, they would look something like this:

![image](https://github.com/Rizwanahmad07/Time-Complexity-and-Big-O-DAY01/assets/110217443/14074dd3-2ae1-4421-b5b0-03d5a9c51a51)

So, this was the basics of time complexities. You don't have to worry about things passing you by. We’ll learn more deeply in the coming videos. For now, just stay with me.


