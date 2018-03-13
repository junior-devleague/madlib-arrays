# MadLib Arrays

### Objective

You will be creating a story madlib style with arrays! Wherever you see the following: `--verb--` is where you will fill in with an item of your choice from one of your arrays. Example:

```
// Given sentence
"The cow --verb-- over the --noun--."

// Given array
var nouns = ['moon', 'cat', 'cougar'];
var verbs = ['jump', 'roll', 'swing'];

console.log("The cow " + verbs[0] + "ed over the " + nouns[0] + ".") // Produces "The cow jumped over the moon."
```

### MadLib Story

Mars was colonized in `--number(year)--` with the joint efforts of `--noun(country)--` and `--noun(country)--`. The space shuttles that `--verb--` the fleet were named `--noun(name)--`, `--noun(name)--`, and `--noun(name)--`. The first public voyage carried `--number--` humans and animals. A one-way ticket to Mars came with a hefty price of `--number--` bitcoin. For people watching the initial launch it was a `--adjective--` sight to see. The Earthlings `--verb--` for `--adjective--` as the space shuttles landed safely on the live stream. When it was time to exit the shuttles, the Earthlings were `--adjective(end with -ly)--` greeted by the local Martians.

#### Exercises

1.  Create a variable called `nouns` and insert the following:

    * 3 names
    * 2 countries

2.  Create a variable called `numbers` and insert the following:

    * A year between 2020 - 2100
    * 2 numbers between 10k - 50k

3.  Create a variable called `adjectives` and insert the following:

    * Adjective that ends with -ly
    * 2 adjectives

4.  Create a variable called `verbs` and insert the following:

    * 2 verbs that ends with -ed

5.  You will need to access your newly created arrays using bracket notation to fill in the blanks of the MadLib below. You may console log the whole story or break down the story by sentences and store them in a variable.

```
Example:
console.log("This is a " + adjective[1] + " story." + "JavaScript makes my brain " +  verb[3] + ".")

or

var sentence1 = "This is a " + adjective[1] + " story. ";
var sentence2 = "JavaScript makes my brain " + verb[3] + ".";
console.log(sentence1 + sentence2);
```
