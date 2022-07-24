# Intro-to-Solidity...
* Solidity is a high-level programming language designed for implementing smart contracts. It is statically-typed object-oriented language. Solidity is highly influenced by Python, c++, and JavaScript which runs on the Ethereum Virtual Machine(EVM).Solidity is the most used and stable Blockchain Programming language recommended by developers worldwide.
* Solidity is a programming language for writing smart contracts. Learn how to build your first smart contract on the Ethereum blockchain...
* Solidity is primary language for blockchains running platforms.
* Solidity can be used to creating contracts like voting, blind auctions, crowdfunding, multi-signature wallets, etc.
* Solidity is a curly-bracket language designed to target the Ethereum Virtual Machine (EVM). It is influenced by C++, Python and JavaScript. You can find more details about which languages Solidity has been inspired by in the language influences section.

![download](https://user-images.githubusercontent.com/98481882/180621253-4f73b984-d873-4db2-8d0c-dd43273eab37.png) ![download](https://user-images.githubusercontent.com/98481882/180621317-b6b48ec3-95ec-46ed-b68f-27be0c9b7eff.png)



# WHAT IS SOLIDITY USED AND BASED FOR ?
* Solidity is an object-oriented programming language created specifically by the Ethereum Network team for constructing and designing smart contracts on Blockchain platforms. It's used to create smart contracts that implement business logic and generate a chain of transaction records in the blockchain system...
* Solidity is designed based on existing programming languages like C++, Python, and JavaScript, so it uses similar language structures found in these languages, most likely to make it easy for developer adoption. If you are a JavaScript or C++ developer, this will look familiar to you.
* Solidity is a statically typed programming language designed for developing smart contracts that run on the Ethereum Virtual Machine (EVM)

# Solidity advantages
* Benefits of Solidity Programming Language is :-
1) A simple, easy-to-use programming language to write smart contracts for dApps.
2) An open-source, object-oriented high-level programming language.
3) It provides an Application Binary Interface (ABI) to avoid syntax errors.
 
* iF u want more  detail about solidity  <-- click this above link -->

# INTRODUCTION TO SMART CONTRACTS..
* A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.
* Smart contracts are a type of Ethereum account.

![download](https://user-images.githubusercontent.com/98481882/180642734-ffccdbbf-fbf6-48a8-83c3-4ec4009e2aaa.jpg)


# Solidity – Types
* Solidity is a statically typed language, which implies that the type of each of the variables should be specified. Data types allow the compiler to check the correct usage of the variables. The declared types have some default values called Zero-State, for example for bool the default value is False. Likewise other statically typed languages Solidity has Value types and Reference types which are defined below:


# Value Types
* Value type variables store their own data. These are the basic data types provided by solidity. These types of variables are always passed by value. The variables are copied wherever they are used in function arguments or assignment. Value type data types in solidity are listed below: 
1) Boolean: This data type accepts only two values True or False.
2) Integer: This data type is used to store integer values, int and uint are used to declare signed and unsigned integers respectively.
3) Fixed Point Numbers: These data types are not fully supported in solidity yet, as per the Solidity documentation. They can be declared as fixed and unfixed for signed and unsigned fixed-point numbers of varying sizes respectively.
4) Address: Address hold a 20-byte value which represents the size of an  Ethereum address. An address can be used to get balance or to transfer a balance by balance and transfer method respectively.
5) Bytes and Strings: Bytes are used to store a fixed-sized character set while the string is used to store the character set equal to or more than a byte. The length of bytes is from 1 to 32, while the string has a dynamic length. Byte has an advantage that it uses less gas, so better to use when we know the length of data.

 * Example: In the below example, the contract Types initializes the values of different types of Values Types.
// Solidity program to demonstrate
// value types
pragma solidity ^ 0.5.0;

// Creating a contract
contract Types {

	// Initializing Bool variable
	bool public boolean = false;
	
	// Initializing Integer variable
	int32 public int_var = -60313;

	// Initializing String variable
	string public str = "GeeksforGeeks";

	// Initializing Byte variable
	bytes1 public b = "a";
	
	// Defining an enumerator
	enum my_enum { geeks_, _for, _geeks }

	// Defining a function to return
	// values stored in an enumerator
	function Enum() public pure returns(
	my_enum) {
		return my_enum._geeks;
	}
}
# SOLIDITY DEVELOPER

![1-2](https://user-images.githubusercontent.com/98481882/180642670-dff167c6-4e9b-4002-a2e0-e511ab670cf2.jpg)

* A Solidity developer is a blockchain developer who works with smart contracts on Ethereum-based applications. A Solidity developer job description may include: Developing and deploying smart contracts. Auditing smart contracts. Communicating with users to translate business goals into technical requirements.
* if u want to become a solidity developer first u need to learn the basics of programming. You need to know how to code in C++, JavaScript, or Python. Solidity requires some knowledge about object-oriented programming, and you should be familiar with data structures like lists and maps.
