- 👋 Hi, I’m @velomana
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
velomana/velomana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//Question number 1.
// The output will be: "I am 25 years old."
var finalNumber = 25;
var sentence = 'I am ' + finalNumber + ' years old.';
console.log(sentence);

// questionnumber 2.
// The output will be: "My dog's name is Greg." 
var dogsName ="Greg";
var sentence = "My dog's name is {dogsName}";
console.log(sentence);

// questionnumber 3.
//unitialise the variable cost to the value 2.
//initialise the variable sentence to say The bread cost 2.
// the output will be "The bread cost $2"
var cost = 2;
var sentence = `The bread cost $${cost}.`;
console.log(sentence);



// questionnumber 4.
// Problem Setup: create a variable Name and Age and give them a value of (i.e="Mbola/25")
var Name = "Mbola";
var age = 25;
//concatenate the sentence using single quotes. 
//Describe/tell someone how to set up the problem and provide the answer.
var sentence = 'My name is ' + Name + ' and I am ' + age + ' years old.';
console.log(sentence);



// Problem Setup: create a variable distric/population and give it the value of distric name and population amout.
var distric = "fort dauphin";
var population = 450000;
// Construct the sentence using backticks
var sentence = `The population in ${distric} is ${population} ppls`;
console.log(sentence);


// Problem Setup:create a variable product/price and give it the value of product name and price amount.
var product = "bicycle";
var price = 5000;
// Construct the sentence using format specifiers
var sentence = `The %s costs $%.2f.`;
sentence = sentence.replace("%s", product).replace("%.2f", price.toFixed(2));
console.log(sentence);


//questionnumber .
// Initialise the variavle X to the value of 2 .
//Initialise y to the value of 4, Initialise total to the following equation:
var x= 2;
var Y= 4;
var totalZ= (x+Y)-(Y-x);
console.log(totalZ);
//this will give the result as 4 .


// question number6 
// Initialise the variavle T to the value of 6 .
//Initialise G to the value of 3, Initialise total to the following equation:
var T= 6;
var G= 3;
var totalW=(T*G)/(T+G);
console.log(totalW);
// this wiil the result as 2.
