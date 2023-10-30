# Foundations of Computer Science Classwork 04
#### Name0:
#### Name1:
#### Name2:
#### Name3:
#### Period:
---
# `"theoretical hungry zebra creates cake"`

### Getting Started
In this repository you will find the following files:
- README.md (the file you are currently reading) contains all the instructions for this assignment.
  - You will also put the non-programming answers in this file.
- sentence.rkt is a racket file containing sample code and some instructions. The questions you have to answer will be based on the contents of this file.
  - You will need to modify some of these functions later on.
- nouns.txt, adjectives.txt, verbs.txt
  - These text files will eventually contain at least 10 words of the appropriate type (i.e. nouns.txt should only have nouns).

Copy the contents of sentence.rkt into DrRacket. Save that file to your computer. Also, create the txt files on your computer in the same directory as your racket file. To start, the txt files only need to have one word in each. Before doing anything else, make sure the racket code runs.

When you are done, make sure all the files on GitHub have your contributions.

---

### Task 0
Answer the following questions about the code:

#### Question 0
There is a variable called `nouns`, what is being stored in that variable? Be as specific as possible.

YOUR ANSER HERE (remove this line and add your response).

#### Question 1
What type of value is returned by the `noun`, `verb`, `article`, and `adjective` functions?

YOUR ANSER HERE (remove this line and add your response).

#### Question 2
What type of value is returned by the `wordy-noun`, `subject`, and `verb-phrase` functions?

YOUR ANSER HERE (remove this line and add your response).

#### Question 3
What does it appear that the `append` function does? (you may want to try using it in the interactions area).

YOUR ANSER HERE (remove this line and add your response).

#### Question 4
What does it appear that the `string-join` function does?

YOUR ANSER HERE (remove this line and add your response).

---
### Task 1
As you may have guessed, this program is meant to generate a random sentence, but right now it makes very boring sentences. So we will modify some of the functions to make it better. For this part, you will need to modify the code in sentence.rkt

#### Question 0
Nouns are cool, but sometimes we like to jazz them up with adjectives. Modify `wordy-noun` so that there is a 50% chance of either:
- Returning a list with a noun in it.
- Adding an adjective to the beginning of a list returned by `wordy-noun`.

#### Question 1
Sometimes, we put articles like "the" or "a" in front of a noun (or wordy-noun). Modify `noun-phrase` so that there is a 50% chance of either:
- Returning a "wordy-noun".
- Adding an article to the beginning of a "wordy-noun" list.

#### Question 2
A simple sentence contains a subject (in this case a noun-phrase) and a verb, eg "the cat eats". Sometimes it's nice to add an object after the verb, eg "the cat eats a fish". Modify `verb-phrase` so that there is a 50% chance of either:
- Returning a list with verb in it.
- Returning a list with a verb followed by a `noun-phrase`.

---
### Task 2
Now lets make your sentences better!

#### Question 0:
Make sure each txt file has at least 10 words.

#### Question 1:
Currently, `wordy-noun`, `noun-phrase` and `verb-phrase` each have a 50% chance of returning one of the two options available. What would you modify to change the split to these:
- 25% / 75%

YOUR ANSWER HERE

- 40% / 60%

YOUR ANSWER HERE

- 37% / 63%

YOUR ANSWER HERE
