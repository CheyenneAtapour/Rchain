## Extending Rchain

Rust is quickly becoming one of the most popular languages in the blockchain industry. It is also equally important to understand how different components of a blockchain work. So to knock two birds with one stone your group will be extending Rchain. 

### Getting started
 1. Understand and familiarize with the [Rchain codebase](https://github.com/Mereep/rchain)
	 * Learning Rust [[1]](https://doc.rust-lang.org/rust-by-example/)[[2]](https://youtu.be/U1EFgCNLDB8) 
 2. Run Rchain as per [example](https://github.com/Mereep/rchain/raw/gh-pages/Blockchain%20Article%20Part%201.pdf) 
	 * Multiple users on the network
	 * Both example attacks
   
### Objectives
Now that you have the basic Rchain running, its time to extend it! As a team you will work together on 1 github repo to extend Rchain. The repo should contain a README with set up instructions and the code should be commented. This is due 1 week from now

 1. Extend *World State* with *get_total_tokens()* to display the current token total in the network.
 2. Extend *World State* with *get_transactions_for()*  display all the transactions in coronological order and block # for a given id.
 	 * Tip: 1 & 2can be calculated by walking through the chain
 3. Add signed message functionality 
 4. Scale to 10 users on the network.
 5. Build a presentation that covers the fundamentals of your groups chain and a series of screenshots that provides 1-3 functionality. 
 

