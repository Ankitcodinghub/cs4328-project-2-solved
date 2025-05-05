# cs4328-project-2-solved
**TO GET THIS SOLUTION VISIT:** [CS4328: Project #2 Solved](https://www.ankitcodinghub.com/product/cs4328-project-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;49146&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4328: Project #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1 Overview</span>

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
In this project, we are going to build “Card Matching Fight”. Card matching fight is a simple card game with one dealer, 3 players, and a single deck of cards. The game is composed of three rounds. At the beginning of each round, the dealer shuffles the cards, deals the first three cards and waits for the round to finish, before repeating the same process for the next round. A winner in a round is the first player to get a match (i.e., two cards of equal rank). In each round, a different player is given the privilege to start.

Initially, the dealer shuffles the deck of cards and hands each player a single card in a round robin fashion (say starting from player 1 in round 1). Once the dealer is done handling the cards, the dealer places the remaining deck of cards on the table and the first round begins. Each player (starting from player 1), draws a card from the deck and compares it to the card he/she has. If they match, the player shows the hand, declares him/herself as a winner and the round completes. Otherwise, the player will discard one card (at random) by placing it at the end of the deck of cards on the table and the next player proceeds. Once a round ends, the dealer will shuffle the deck and hands a card to each player. In the second round, the second player starts drawing a card from the deck. In the third round, the third player starts drawing a card from the deck.

2 Implementation

This project is to implemented in C using POSIX threads. You can check:

<pre>https://computing.llnl.gov/tutorials/pthreads
</pre>
for a tutorial on the POSIX thread library. The main function should create a thread for the dealer and 3 threads for the players. Notice that we want to keep the threads synchronized and to protect any shared objects. Also, when a player wins, he/she needs to inform other players that the round is complete. Each thread should print a message when it finishes (e.g., “Player 1 wins and round completed”, “Player 2 round completed”, etc. The main program takes a seed as an argument for the random number generation (which will be used in shuffling and in discarding cards ).

3 The Output

The dealer and the players will write into a log file each action they talk. The log file should be able to describe exactly what is happening at each step. The log file should look something like this:

PLAYER 1: hand 5

PLAYER 1: draws 7

PLAYER 1: discards 7

PLAYER 1: hand 5

DECK: contents of the deck, separated by spaces (e.g., 1 2 3)

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 3

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CS4328 (Mina Guirguis ): Project #2

</div>
<div class="column">
4 SUBMISSION

</div>
</div>
<div class="layoutArea">
<div class="column">
The final messages for a round should look something like:

PLAYER 2: hand 3 PLAYER 2: draws 3 PLAYER 2: hand 3 3 PLAYER 2: wins

PLAYER 2: round completed PLAYER 1: round completed PLAYER 3: round completed DEALER: shuffle

The output of the program to the screen (not in the log file) should indicate the hand for each player, the status (win, lost) and the remaining deck of cards:

HAND card1 card2

WIN yes (or no)

DECK contents of the deck, separated by spaces (e.g., 1 2 3)

The hand of the winner would show two cards (the winning matching cards) and the hands of the other players would show only one card. A single run of the program should have 3 rounds with 3 winners.

4 Submission

Submission will be done through TRACS. Submissions will include the code, a report containing a brief overview of the design and implementation, the results of 5 independent runs of the program with different seeds, and instructions on to how to compile and run the simulator. Please upload a single zip file including all your files.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 3

</div>
</div>
</div>
