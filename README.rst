===================
What is wordGroupz?
===================

wordGroupz is a vocabulary building application which helps you to
store any word you come across classified into different groups. It
also features offline wordnet dictionary support and online wiktionary
and webster dictionary support. You can research about a word with the
help of the wiktionary browser, and write down your own notes for a word
if required. It also has pronunciation support for words downloaded from
wiktionary.

It is a free software licensed under the GNU General Public License version
2 and is written in pygtk/Python.

This project is hosted at http://gitorious.org/wordgroupz/ and its wiki is
located at http://gitorious.org/wordgroupz/pages/Home


USAGE
-----

When you first open wordGroupz (Applications->Education->wordgroupz), you
see a welcome screen, with the stored wordlist on the left hand side, and
below it, the interface to add a word to the database.

To add a word, you can enter a word in the "Word" textBox, then select
or add a new group from the "Group" drop down menu or leave it blank.
Then you may add some notes for your word or keep it blank. When you click
the "Add" button, the word and its details get saved in the database.

You can search for a word in the word list by typing the word in the search
bar above the word list display.

Now, when you click on a word from the words treeview on the left hand
side, you see , in place of the welcome screen, the details for the word.
You will be able to see a "Play" button, "Delete" button and a "Dictionary"
drop down list. You can play the pronunciation of a word by clicking on the
"Play" button, delete the selected word by clicking on the "Delete" button.
The "Details" tab shows you a well organized definitions of the word from
the respective dictionaries. This is READ_ONLY.

The "Wiktionary" tab lets you search for the selected word in wiktionary,
http://en.wiktionary.org/ . You can reload the wiktionary page for the
word selected word. Using the "Back" and "Forward" button, you can go
backwards and forwards through the opened web pages.

The "Notes" tab lets you add or edit existing notes for the selected word.

wordGroupz has two games: Flash Cards and M.C.Q. (Multiple Choice Question)
to help you learn the words in an interactive way. To play the games, click on
"Games" in the menubar of wordGroupz and select either 'Flash Cards' or 'MCQ'.

In the Flash Card interface, you see a word, check its meaning by clicking on
'Check'. If you know the word, click 'I knew it', else 'Dammit'. Then you are
taken to the next word. By default, the words are displayed first and in an
alphabetical order. Select 'Definition' from 'Game Modes' to show definitions
first, and try to guess the word. Check 'Random' in the 'Game Modes' menu to
show the words/definitions in a random way.

In the MCQ interface, you can select the number of questions you would like
to attempt. Here, a word is shown and 4 options are provided. One of the 4
options is a correct answer. Click 'Proceed' to move to the next question. When
you complete the entire test, click the 'Review' button to view your test review.

On the basis of performance on the tests/games, wordgroupz shows the accuracy %
for a word beside it in the words tree view. Based on this report, you will
be able to focus on the words where your accuracy is less.


INSTALL
-------
As root, do 'python setup.py install'


DEPENDENCIES
------------
- python DB-API 2.0 interface for SQLite 3.x
- python-sqlite2
- pygtk2
- pywebkitgtk
- urllib2
- python-BeautifulSoup
- gstreamer-python
- espeak


CREDITS
-------
The wordGroupz icon has been taken from http://www.openclipart.org/detail/60205
It has been designed by mazeo.

