# cs1027-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS1027 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs1027-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131827&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1027 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Learning Outcomes

In this assignment, you will get practice with:

• Creating classes and objects of those classes

• Overloading constructors

• Implementing equals(), toString(), getters, and other methods

• Working with arrays

• Using loops and conditionals

Introduction

Most of us are probably familiar with the beloved family game ‘Scrabble’. In

Scrabble, players collect seven random tiles, each consisting of a letter A through Z (for the sake of simplicity, let us that assume the ‘blank’ tile does not exist in this version of the game). Players then use these tiles to create words that consist of one or more of the letters they’ve randomly selected.

When a word is created using one or more of the seven selected tiles, the value of each of the tiles is summed, and that score is added to the player’s cumulative score. The individual value of each tile is presented below.

Given the letters of seven randomized Scrabble tiles, you must determine the set of scores that a player could possibly obtain by placing these tiles. We will be assuming three traits that differ slightly from the traditional game of Scrabble:

1. There is an unlimited amount of every letter within the scrabble bag, thus it is reasonable to assume (though incredibly unlikely) that you could obtain something like [‘A’, ‘A’, ‘A’, ‘A’, ‘A’, ‘A’, ‘A’].

2. You will be placing these tiles during the first turn on the board. Thus, you do not need to worry about combining your word with any pre-existing letters that might have already been placed on the Scrabble board.

3. Assume that there exist no word or letter bonuses. We will simply be basing the score off the tile values.

As an example, assume that your seven randomized tiles read:

{‘A’, ‘C’, ‘A’, ‘A’, ‘B’, ‘A’, ‘H’}

The output should be 1) a list of length n of words that can be created using these letters, and 2) a list of length n containing the scores (integers) for each of the words of length 1 ≤ m ≤ 7 that can be created using these letters (like ‘AA’, or ‘AAH’, which are both words within the Collins Scrabble Word dictionary, surprisingly). So two of the scores that will be in your score set for the above tile set are 2 (A (1) + A (1) = 2), and 6 (A (1) + A (1) + H (4) = 6).

Provided Files

The following is a list of files provided to you for this assignment. Do NOT alter these files.

– CollinsScrabbleWords2019.txt

– TestGame.java

Classes to Implement

For this assignment, you must implement two java classes: Tile and Scrabble. Follow the guidelines for each one below.

Tile.java

This class represents a single Scrabble tile that will be used in the game.

The class must have the following private variables:

• value (char)

The class must have the following public methods:

• public Tile() [constructor] o Initialize value to ‘ ’

• public Tile(char) [constructor] o Initialize value to the given argument

• public void pickup() o Generate a random character between A and Z (inclusive) and set the value to that letter. o Feel free to use ‘java.util.random’ for this method

• public char getValue() o Returns the tile value

Scrabble.java

This class represents the Scrabble game in which there are seven randomly selected tiles, and scoring is performed for each possible word (this will be the tougher class to implement).

The class must have the following private variables: • tiles (Tile[ ])

The class must have the following public methods:

• public Scrabble() [constructor] o Initialize the Tile array and ‘pickup’ for random values

• public Scrabble(Tile [ ]) [constructor] o Initialize the tile array with the given argument

• public String getLetters() o Return a string that is all of the tile characters (for example, “ABFEODL”)

• public ArrayList&lt;String&gt; getWords() o Create an ArrayList of Strings with n elements. Each element should represent a word that can be created using the current tiles.

o The algorithm for this method should reference the provided file

CollinsScrabbleWords2019.txt o ** do NOT put this file somewhere on your local machine and hardcode the local directory. This will likely cause your tests to fail on GradeScope. Also, do not put it within a folder in the relative path.

• public int[ ] getScores() o Create an int array with n elements. Each element in this list should represent each individual score for each word that can be created using the current tiles. This should be returned in ascending order.

• public Boolean equals(Scrabble) o Compare the given Scrabble object from the argument with the ‘this’ object to see if they are equal (do they have the same tiles?).

Marking Notes

Functional Specifications

• Does the program behave according to specifications?

• Does it produce the correct output and pass all tests?

• Are the classes implemented properly?

• Does the program produce compilation or run-time errors on Gradescope?

• Does the program fail to follow the instructions (i.e, changing variable types, etc)

Non-Functional Specifications

– Are the variables and methods given appropriate, meaningful names?

Avoid things like ‘temp’, ‘myvar’, and ‘goodForNothingVariable’.

– Is the code clean and readable with proper indenting and white-space? – Is the code consistent regarding formatting and naming conventions?

– Submission errors (i.e, missing files, too many files, etc.) will receive a penalty of 5%

– Including a “package” line at the top of a file will receive a penalty of 5%

** Remember you must do all the work on your own. Do not copy or even look at the work of another student. All submitted code will be run through similaritydetection software.

Assignments must be submitted to Gradescope, not on OWL. If you are new to this platform, see these instructions on submitting on Gradescope.

Rules

• Please only submit the files specified below.

• Do not upload the .class files! Penalties will be applied for this.

• Forgetting to submit is not a valid excuse for submitting late.

Files to Submit

• Tile.java

• Scrabble.java

Grading Criteria

Functional Specifications

[1] Tile.java

[6] Scrabble.java

[10] Passing Tests

Non-Functional Specifications

[1] Meaningful variable names, private instance variables

[1] Code readability and indentation

[1] Code comments
