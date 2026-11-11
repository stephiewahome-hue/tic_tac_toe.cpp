# Game Development – Lesson 3: C++ Game Programming

Let's study this lesson properly, from the beginning, as if you are learning it for the first time. I'll explain the concepts in simple language, give you examples from actual games, explain the code, and show you what to remember for your CAT.

Our goal is not just to memorize answers. It is to understand why things work.

Your PDF covers four main areas:

1. C++ in the gaming industry.
2. Mathematics used in game development.
3. Game theory in video game development.
4. The Minimax algorithm and Tic-Tac-Toe programming in C++.

Let's start with Topic 1.

# TOPIC 1: C++ IN THE GAMING INDUSTRY

## 1. First, what is C++?

C++ is a programming language used to create computer programs, including video games.

Think about a game like a racing game.

When you play, the game needs to:

- Move your car.
- Detect when your car hits another car.
- Calculate your speed.
- Display graphics.
- Respond immediately when you press a button.

Someone has to write instructions telling the computer how to do all these things.

C++ is one of the languages developers use to write those instructions.

## 2. Why is C++ important in game development?

According to your notes, C++ is recognized as an industry-standard language.

The biggest reason is HIGH PERFORMANCE.

What does high performance mean?

Imagine playing a racing game.

You press the accelerator, but the car takes three seconds to respond.

That would be a terrible gaming experience!

Games need to respond quickly to player actions.

This is where C++ is useful.

Your notes mention:

High performance (minimum latency) is an essential requirement for game design.

Let's understand two important terms:

- Performance: How efficiently and quickly a game runs.
- Latency: The delay between an action and the computer's response.

For example:

| Player action | Low latency                 | High latency           |
| ------------- | --------------------------- | ---------------------- |
| Press jump    | Character jumps immediately | Character jumps late   |
| Press fire    | Action responds quickly     | Action responds slowly |
| Turn a car    | Car turns immediately       | Car turns late         |

CAT POINT

C++ is useful in game development because it offers high performance and helps reduce latency.

## 3. Which game engines use C++?

First, what is a game engine?

A game engine is software that provides tools for creating video games.

Think of it as a toolbox containing things like:

- Graphics tools.
- Physics systems.
- Sound systems.
- Animation tools.
- Collision detection.

Your notes mention these engines:

[File:Unreal Engine Logo.svg - Wikimedia Commons](https://images.openai.com/static-rsc-4/Q4mNATOh7YzkMAezLT_xZAgee9tp_vb8UG_CE2bYG_tR0ddAsW8TI3ADOCynxIGHthPHJqM0m0qpsfu9nAknYoG-nf-G4m5Xrg2ZNxgmE-ngp8qqQHq2DRrEU3s4hWS_n3wCquLG5fJQnGmrXel1gzDpT-Y0yyiodRPPhN7uX0Y?purpose=inline)

Unreal Engine

Uses C++ for game programming. It is a major engine for developing 3D games.

[Godot Engine | Catálogo | NeoAxis é uma versátil plataforma 3D e 2D em tempo real](https://images.openai.com/static-rsc-4/K_mKLPaEIkcYLAwmSajgEBzvUWdGWrzE-5dNigoLRA8KqNO-Bp0DJ9-QKZ7CoMiJkaZIdcSeuZpP0WQzrnuKj2cGTdCrPIjQYQCaqzWd2QRdvzhvAaA5Jv-cjXeGW8v1swp48my_cu7K0kVrYH5kJXu-BTc3AZiKXwnh9eQqEcE?purpose=inline)

Godot

A game engine that supports C++ among other programming options.

[Unity Logo PNG Vector (SVG) Free Download](https://images.openai.com/static-rsc-4/gX7hKYN8ophljwr9ccAI6JlM1g07g2oQqOB3_d-Q5cFA1g8M7UHeHsqx6mHINxOZjPc5tdE_i2i8q5LXz2zUa9rMGrOZSg68QAataUFWBMSsqznLHLBF5Gz3tLkJmjDQdAN87zhTYtBZsFrjgay3iJ8mqYIlLeL3d1Mn8cTDshA?purpose=inline)

Unity

Your notes explain that Unity is written in C#, while its runtime uses C++.

### C++ versus C\#

Your notes make an important comparison:

| C++                              | C#                       |
| -------------------------------- | ------------------------ |
| Commonly used with Unreal Engine | Commonly used with Unity |
| Offers high performance          | Beginner-friendly        |
| Widely used in game development  | Fully supported by Unity |

Remember: C++ and C# are different programming languages. They are not the same thing.

## 4. Where is C++ used?

Your PDF explains that C++ has been used to develop games for different platforms:

- Windows
- Mac
- Linux
- Android
- iOS

This means C++ is not limited to one type of computer or device.

## Check your understanding – Topic 1

Try these questions before we continue. Don't worry if you get something wrong; I'll explain it.

Topic 1 mini-test

0/4 answered

1\. What is the biggest advantage of C++ in game development according to your notes?

A. Beautiful graphics

B. High performance

C. Internet connectivity

D. Low storage usage

2\. What does latency mean?

A. The delay between an action and a response

B. The size of a game

C. The number of players

D. The game's background colour

3\. Which programming language is commonly used with Unreal Engine?

A. HTML

B. CSS

C. C++

D. SQL

4\. Which language is fully supported by Unity according to your notes?

A. C#

B. PHP

C. Java

D. Python

Check my answers

# TOPIC 2: MATHEMATICS USED IN GAME DEVELOPMENT

This is an important topic because games are not just about pictures and buttons. Behind almost every movement, rotation, jump and collision, there is mathematics.

Imagine creating a football game.

The computer must know:

- Where the ball is.
- How fast the ball is moving.
- Which direction it is travelling.
- How high it should bounce.
- When it touches the ground.

Mathematics helps the computer calculate all these things.

Your notes identify several branches of mathematics.

## 1. Algebra – Linear Algebra

Let's begin with vectors.

What is a vector?

A vector is a mathematical quantity that has both:

1. Magnitude (size or amount).
2. Direction.

For example, imagine a character moving to the right.

[Math 1. Vectors | Unity basics course](https://images.openai.com/static-rsc-4/uxFh98BKu0oXRZXEoaweB9Kg4c-N5Kw7jzJk8CfNsKYJiW_6_ju-yH_4b80D6YYTfc_9FQS-jlAEPJs2kxW_ZnE53DKX0ReGxX--zOxkIxTb1yTiB004TiyDKQLmcvo0M_ls3XLNHx47dla9aAdTBailfPGTbVZhDtz1ck4mkfo?purpose=inline)

[borbware.github.io](https://borbware.github.io/unity-basics-course/math/1-vectors.html?utm_source=chatgpt.com)

The vector tells the computer which direction the character should move and how much movement is required.

Your notes give three examples of where vectors are used:

- Position of an on-screen button.
- Direction of a camera.
- Velocity of a racing car.

Let's understand velocity.

Velocity tells us how fast something moves and in which direction.

For example:

- A car moves at 50 km/h towards the north.
- Another car moves at 50 km/h towards the south.

They have the same speed but different velocities because their directions are different.

Remember: Linear algebra is important because it helps developers control positions, directions and movement using vectors.

## 2. Trigonometry

Trigonometry is the study of relationships between the angles and lengths of triangles.

That sounds difficult, but let's make it simple.

Imagine a character shooting an arrow in a game.

The arrow can travel:

- Upwards.
- Downwards.
- To the left.
- To the right.
- Diagonally.

How does the computer know which direction the arrow should travel?

It uses trigonometry!

Your notes identify three important trigonometric functions:

# sin

Sine

# cos

Cosine

# tan

Tangent

These functions help calculate relationships between angles and distances.

### Understanding the code in your PDF

Your notes provide this example:

```
d2r = pi / 180;

// Move an object in a given direction
this.x += speed * cos(direction * d2r);

this.y += speed * -sin(direction * d2r);
```

Let's break it down.

Line 1:

```
d2r = pi / 180;
```

This converts degrees into radians.

What are degrees?

You normally measure angles in degrees:

- 0°
- 45°
- 90°
- 180°
- 360°

But many programming trigonometry functions, including C++'s `sin()` and `cos()`, use radians.

Therefore, we convert degrees to radians.

Line 2:

```
this.x += speed * cos(direction * d2r);
```

This calculates how much the object moves horizontally (along the X-axis).

Line 3:

```
this.y += speed * -sin(direction * d2r);
```

This calculates how much the object moves vertically (along the Y-axis), using the coordinate convention in the example.

Let's use a simple illustration:

[Tutorial: Trigonometry Basics for Game Physics](https://images.openai.com/static-rsc-4/qptijCMCHqAQ2DAm2HQj_1_1MVDyU4T-WstVdvzN2rQEDccr1fe-wZoTYXolepnYl1tzCVwzyIBkZQMDo4_wphm0oj9I9gd7CgRVcJ136nJKWLZ1gpFnpirt4OTznRFnlBBwYW50_7NDoAhLXF6A9eaF2dTHvkBM2G1rPoI8T2M?purpose=inline)

[80.lv](https://80.lv/articles/tutorial-trigonometry-basics-for-game-physics?utm_source=chatgpt.com)

The important thing to understand is:

- Cosine helps calculate horizontal movement.
- Sine helps calculate vertical movement.
- Speed determines how far the object moves.

CAT POINT

Trigonometry is used to move objects in different directions in a game.

## 3. Calculus

Now, let's understand calculus.

Your notes explain that calculus is used in physics engines.

First, what is a physics engine?

A physics engine is a system in a game that simulates physical behaviour.

For example:

- A ball falling.
- A character jumping.
- Objects colliding.
- Dust particles moving.
- Objects bouncing.

[Refine your animation - Unity Learn](https://images.openai.com/static-rsc-4/rjRbARjjEkkzsTDLwf-m0ydfFk0ZUlvmeWIqiicmxnWst7qh4havnfXe3tMe5gcu5wdcBlaxoYeDMSzlWDaL2uT9HvgKUVNu8To1gl9vSdUypdaHZukdszUP623qAeUEu27Pyg9btswHiviByHc23RoWHmX9QXWi3TipqEdtgdQ?purpose=inline)

[learn.unity.com](https://learn.unity.com/course/creative-core-animation/tutorial/refine-your-animation?version=6.0\&utm_source=chatgpt.com)

Imagine dropping a ball.

The computer needs to calculate:

1. Where the ball is currently.
2. How fast it is moving.
3. How its position changes over time.

This is where calculus becomes useful.

### What does an integrator do?

Your PDF mentions an integrator in a physics engine.

An integrator takes information about an object at time \\(t\\) and uses mathematical formulas to determine its new position or vector.

Let's simplify that.

Imagine:

- At 1 second, a ball is at position 5.
- At 2 seconds, the ball has moved.
- At 3 seconds, it has moved again.

The integrator helps calculate the updated position as time passes.

Your notes also mention collision detection.

Collision detection means identifying when two objects touch or overlap in a game.

For example, when a character touches a coin, the game detects the collision and can collect the coin.

Remember: Calculus is used in physics engines to calculate changes in motion and position over time.

## 4. Other branches of mathematics

Your PDF also lists:

| Branch               | Simple meaning                                     |
| -------------------- | -------------------------------------------------- |
| Linear Algebra       | Working with vectors and positions                 |
| Discrete Mathematics | Studying separate, countable values and structures |
| Applied Mathematics  | Applying mathematical ideas to practical problems  |

Notice that Linear Algebra appears twice in your notes. It is listed among the main branches and again in the additional list.

## 5. Specific mathematical elements used in games

Your PDF lists four additional elements. Let's understand each.

A. Matrices

A matrix is a rectangular arrangement of numbers in rows and columns.

In game development, matrices are useful for:

- Moving objects.
- Rotating objects.
- Scaling objects.
- Transforming 3D scenes.

Example of a matrix:

\\[ \begin{bmatrix} 1 & 2\\\ 3 & 4 \end{bmatrix} \\]

Don't worry about calculating with matrices yet. Just understand their purpose.

B. Delta Time

This is very important in game development.

Delta time is the time taken between two frames of a game.

Imagine a game running on two different computers:

- Computer A displays 60 frames per second.
- Computer B displays 30 frames per second.

If movement is based only on the number of frames, the game could run at different speeds on the two computers.

Delta time helps make movement consistent over time.

C. Unit and Scaling Vectors

These help describe direction and size.

A unit vector has a magnitude of 1.

Scaling vectors are useful when changing the size of an object along different axes.

For example, making a game object wider or taller.

D. Dot and Cross Products

These are mathematical operations involving vectors.

- Dot product: Helps calculate relationships between directions, including how aligned two vectors are.
- Cross product: Produces a vector perpendicular to two input vectors in 3D space.

They are useful for calculations involving direction, angles and 3D orientation.

TOPIC 2 SUMMARY

| Mathematics              | Main use                          |
| ------------------------ | --------------------------------- |
| Algebra / Linear Algebra | Positions, directions and vectors |
| Trigonometry             | Movement in different directions  |
| Calculus                 | Motion and physics calculations   |
| Discrete Mathematics     | Separate mathematical structures  |
| Matrices                 | Transformations of game objects   |
| Delta Time               | Consistent movement over time     |
| Dot Product              | Comparing vector directions       |
| Cross Product            | Finding perpendicular directions  |

# TOPIC 3: GAME THEORY IN VIDEO GAME DEVELOPMENT

Now we are moving into a very interesting topic.

Have you ever played Tic-Tac-Toe?

Imagine you are playing against someone.

You want to win, but your opponent also wants to win.

You must think about:

- Where should I place my X?
- What if my opponent places O there?
- How can I stop my opponent from winning?
- Which move gives me the best chance?

This is the idea behind game theory.

## 1. What is game theory?

According to your PDF:

Game theory started as a mathematical exploration of human behaviours.

In simple language:

Game theory is the study of how people or players make decisions when their outcomes depend on the decisions of others.

Let's use an example.

You and your friend are playing a game.

You choose one move, and your friend chooses another.

Your decisions affect each other's chances of winning.

That is game theory!

## 2. Zero-sum game

This is an important examination concept.

A zero-sum game is a game where one player's gain is equal to another player's loss.

Imagine two players:

- Player A wins 10 points.
- Player B loses 10 points.

The total is zero.

\\[ 10+(-10)=0 \\]

[C-50　『チェスプレイヤー』 | ウェブで授業研究 Find！アクティブラーナー](https://images.openai.com/static-rsc-4/oSwGNrn-jjGhMB9cZ651aXCSVNT0jdKWQNuQpuTXnDmCCICKtCNr2XCwO0NED0oCPEIh-kxBNOFCgivKx2brQGwChTl1IEm9JDkUpWgBNVworKJlYZeb9EYdpavVkk39UymvAPlzmTVM61LEAzWVbOEbMjxKwzozUdH1GSPEuc4?purpose=inline)

[find-activelearning.com](https://find-activelearning.com/set/913/con/634?utm_source=chatgpt.com)

Think of a simple win-or-lose game:

- If you win, your opponent loses.
- If your opponent wins, you lose.

This is a zero-sum situation.

## 3. How is game theory used in video game development?

Your notes explain that game theory helps developers balance the odds.

What does balancing the odds mean?

Imagine a fighting game.

Player A has a very powerful character, while Player B has a very weak character.

Player A wins almost every time.

That game might feel unfair.

Game theory can help developers think about decisions, strategies and competing players to create fairer gameplay.

It can also help players choose optimal decisions.

Optimal decision-making means choosing a decision that gives the best possible outcome according to the game's objectives.

CAT POINT

Game theory helps developers design fair games and helps players make strategic decisions when competing against others.

# TOPIC 4: THE MINIMAX ALGORITHM

This is probably one of the most important concepts in your lesson.

Let's take our time here.

## 1. What is Minimax?

Minimax is a decision-making algorithm used in games.

Your PDF defines it as a decision rule used to minimize the worst-case potential loss.

In simple words:

Minimax helps a computer choose the best move while assuming that the opponent will also make the best possible move.

Let's understand it with Tic-Tac-Toe.

Imagine you are X, and the computer is O.

You want to win.

The computer also wants to win.

The computer cannot simply choose a random square.

It must think:

- Can I win with this move?
- Can the opponent win next?
- Can I block the opponent?
- Which move gives me the best result?

That is where Minimax comes in.

## 2. Understanding MAX and MIN

Your notes identify two important players:

# MAX

Maximizer

Tries to get the highest possible score.

Wants the best outcome.

# MIN

Minimizer

Tries to get the lowest possible score for MAX.

Wants to reduce MAX's advantage.

Let's say we assign these scores:

| Result | Score |
| ------ | ----- |
| Win    | +1    |
| Draw   | 0     |
| Lose   | -1    |

These are the values given in your notes.

MAX wants +1.

MIN tries to prevent MAX from getting +1.

### Let's do an example

Imagine MAX has two possible moves.

[Zero Sum Game. AI in games can be dumb or smart. What… | by James Min | Medium](https://images.openai.com/static-rsc-4/ysMewE2L-5Ca-vz30PDevpnFlmuwiUEhH4WDYLfRC9FS-Rw9DFDrrA4j6B-wNPg97pselmRhSDfpa2UbAjr60SlDFjeLRKOxrEbnvwIrA0WMidUCm2TrDs9t6u98GuRpw5HgpqnfN956xh0oy4bgQjMvRzk-4WMV0pnRs8URFbM?purpose=inline)

[medium.com](https://medium.com/%40jmin499/zero-sum-game-ef2ce1789dca?utm_source=chatgpt.com)

Suppose:

- Move A can lead to outcomes of +1 or -1.
- Move B can lead to outcomes of 0 or -1.

MIN will choose the outcome that is worse for MAX.

For Move A:

\\[ \min(1,-1)=-1 \\]

For Move B:

\\[ \min(0,-1)=-1 \\]

MAX then compares the worst outcomes:

\\[ \max(-1,-1)=-1 \\]

Both moves have the same worst-case score.

The important principle is:

- MAX chooses the highest value.
- MIN chooses the lowest value.

This is why it is called MINIMAX.

## 3. Why is Minimax called a recursive algorithm?

Your PDF says Minimax is recursive.

What does recursion mean?

Recursion happens when a function calls itself to solve a problem.

Imagine the computer asking:

1. What happens if I make this move?
2. What happens if my opponent responds?
3. What happens if I respond again?
4. What happens after that?

It keeps examining possible future moves until it reaches an ending position.

Then it works backwards to decide which move is best.

This is also why your notes mention backtracking.

Backtracking means going back through explored possibilities to evaluate which choice is best.

## 4. Games that use Minimax

Your PDF identifies:

- Tic-Tac-Toe.
- Go.
- Chess.
- Isola.
- Checkers.

These are examples of games where players make competing decisions.

## 5. Rules of Tic-Tac-Toe

[Blank Tic Tac Toe Board Printable](https://images.openai.com/static-rsc-4/rHHzFhLAPfGjy3ufLh8_5eNAQzA8n106E5FjCjGmY3eYO3guAZnESE_zb8ADCZxmSL3tsxfXSsSVEKCQQNFLcV57SdSJCWl09d3F_xzqTVdUGbu1dwOv2lVOatbCPozVhn-k8vmABw4tERc_0Mcby42taMu67TK3UfDIdnrNw3A?purpose=inline)

There are nine squares arranged in a 3 × 3 grid.

The rules:

1. One player uses X.
2. The other player uses O.
3. Players take turns placing their marks in empty squares.
4. The first player to get three marks in a row wins.
5. The marks can be horizontal, vertical or diagonal.
6. If all nine squares are full and nobody wins, the game ends in a draw.

### Let's understand the three winning directions

[Simple Tic Tac Toe - Play Online Games Free](https://images.openai.com/static-rsc-4/LbsWKzTeh6KHTrJFjiYnJiYh84SDhHbc6RscuvYNeCraRbKrZAiHFwnmxmYI1qzyYkBrG_qGaUKbbZC7P7T6KG_hM4c65a1f5uuP-Y9zCzuIDvAVZ_XpuxBlbFU-Ni7Ea6hIfKWLsC8_4a98E_ob8t9Nv8Wz5mZEXCmy1u81W7w?purpose=inline)

Horizontal

[Game Tic Tac Toe Nhiều Người Chơi Miễn Phí | trochoi net](https://images.openai.com/static-rsc-4/6LTNzuBNyrXL-K4_H-VdFI6BBL0dRcEP5JgqITH4cPnGeEvCoem-wGhvXjL_qiH0PRZEp-3oZRmor7PA6XGt8_sSljt62xHxaObkZ4C5Plf1Iu4F3Qfpd2vLvRHJFtOT1YDl7Mc_adyAdeLUYdUqUB0ybtnb2oec3Kdx8a5KDV4?purpose=inline)

Vertical

[Tic Tac Toe - 1.0](https://images.openai.com/static-rsc-4/zhf-9itlVqyl-8d30SnBnFIUKUzlS2FQR-aJl7-dqNjwsJ88l6au2Jlj-1GmpXSM4WnzvEChjSAFju9o73lPTiR1tRCEryUWiJ8rvlc93wzslhVVplr60yycpH-HwDUwDhJDSxs6MmNLqqTw52orwIihz8dUwdSvX2OALO4l2f4?purpose=inline)

Diagonal

## 6. How many possible Tic-Tac-Toe outcomes are there?

Your notes give this calculation:

\\[ 9!=362,880 \\]

Why?

At the beginning, X has nine possible squares.

After X makes a move, O has eight possible squares.

After that, X has seven, and so on.

Therefore:

\\[ 9\times8\times7\times6\times5\times4\times3\times2\times1 \\]

\\[ =362,880 \\]

This is the number of possible move orderings if we consider all nine squares being filled without stopping early for a win.

Your notes explain that a computer can calculate possible outcomes for a simple game like Tic-Tac-Toe.

Important distinction: Your PDF explains Minimax as an algorithm, but the C++ program that follows is a two-human-player Tic-Tac-Toe program. It does not actually implement Minimax.

# TOPIC 5: TIC-TAC-TOE GAME IN C++

Now we are at the programming section of your PDF.

This is where the concepts become practical.

We are going to understand the code, not just look at it.

## 1. What is the program supposed to do?

The program creates a Tic-Tac-Toe game for two human players.

- Player 1 uses X.
- Player 2 uses O.
- Players take turns.
- The program updates the board.
- The program checks whether someone has won.
- The program announces a draw if nobody wins.

## 2. Understanding the C++ code

### Part A: Importing libraries

Your PDF starts with:

```
#include <iostream>
#include <stdlib.h>

using namespace std;
```

Let's understand each line.

`#include <iostream>`

This allows the program to use input and output operations.

For example:

```
cout << "Hello";
```

Displays information on the screen.

```
cin >> choice;
```

Receives information from the user.

`#include <stdlib.h>`

This includes the standard library for general-purpose functions.

`using namespace std;`

This allows us to write `cout` and `cin` without repeatedly writing `std::cout` and `std::cin`.

### Part B: Creating the board

Your PDF:

```
char board[3][3] = {
    {'1','2','3'},
    {'4','5','6'},
    {'7','8','9'}
};
```

This is one of the most important lines.

Let's break it down.

- `char` means character.
- `board` is the name of the array.
- `[3][3]` means three rows and three columns.

The board looks like this:

## TIC-TAC-TOE BOARD

# 1

# 2

# 3

# 4

# 5

# 6

# 7

# 8

# 9

Each number represents a position a player can select.

Why use numbers?

Because players need to tell the computer which square they want to use.

For example, if Player 1 chooses 5, the computer places X in the middle.

### Part C: Declaring variables

Your PDF:

```
int choice;
int row, column;

char turn = 'X';

bool draw = false;
```

Let's understand them.

| Variable | Meaning                                  |
| -------- | ---------------------------------------- |
| `choice` | Stores the square selected by the player |
| `row`    | Stores the row number                    |
| `column` | Stores the column number                 |
| `turn`   | Stores whose turn it is, X or O          |
| `draw`   | Stores whether the game ended in a draw  |

Important programming terms:

- `int` means integer (whole number).
- `char` means character.
- `bool` means Boolean, which can be `true` or `false`.

For example:

```
char turn = 'X';
```

This means the game starts with Player 1, who uses X.

### Part D: The display_board() function

Your PDF introduces:

```
void display_board()
```

What is a function?

A function is a block of code designed to perform a particular task.

Here, the task is displaying the Tic-Tac-Toe board.

The program uses `cout` to display the board.

For example:

```
cout << board[0][0];
```

This displays the value in the first row and first column.

Remember that array indexing in C++ starts at zero.

| Position                 | Array index   |
| ------------------------ | ------------- |
| First row, first column  | `board[0][0]` |
| First row, second column | `board[0][1]` |
| First row, third column  | `board[0][2]` |

### Part E: The player_turn() function

Your PDF:

```
void player_turn()
```

This function is responsible for getting the player's input and updating the board.

First, it checks whose turn it is:

```
if(turn == 'X'){
    cout << "Player 1 [X] turn";
}
else if(turn == 'O'){
    cout << "Player 2 [O] turn";
}
```

What does this mean?

- If the turn is X, Player 1 plays.
- If the turn is O, Player 2 plays.

Next:

```
cin >> choice;
```

This receives the player's selected number.

For example, the player enters 5.

### Part F: The switch statement

Your PDF contains:

```
switch(choice){
    case 1: row=0; column=0; break;
    case 2: row=0; column=1; break;
    case 3: row=0; column=2; break;
    case 4: row=1; column=0; break;
    case 5: row=1; column=1; break;
    case 6: row=1; column=2; break;
    case 7: row=2; column=0; break;
    case 8: row=2; column=1; break;
    case 9: row=2; column=2; break;
}
```

This is very important.

A switch statement helps the program choose an action depending on the player's input.

Let's say the player enters 5.

The computer executes:

```
case 5:
    row = 1;
    column = 1;
    break;
```

That means position 5 corresponds to the middle square.

Try selecting a position

1

2

3

4

5

6

7

8

9

You selected position 5.

Row: 1

Column: 1

Notice that `break` tells the program to stop executing the remaining cases after finding the matching case.

### Part G: Updating the board

Your PDF:

```
if(turn == 'X' &&
   board[row][column] != 'X' &&
   board[row][column] != 'O'){

    board[row][column] = 'X';
    turn = 'O';
}
```

Let's understand this carefully.

The program checks three conditions:

1. Is it X's turn?
2. Is the selected square not occupied by X?
3. Is the selected square not occupied by O?

If all conditions are true:

```
board[row][column] = 'X';
```

The computer places X in the selected square.

Then:

```
turn = 'O';
```

It changes the turn to Player 2.

The program has a similar section for O:

```
board[row][column] = 'O';
turn = 'X';
```

This means after O plays, the turn goes back to X.

What happens if a player selects an occupied square?

The program displays:

```
cout << "Box already filled! Please choose another!";
```

It then calls `player_turn()` again to request another move.

### Part H: Checking whether the game is over

Your PDF:

```
bool gameover()
```

This function checks whether the game should continue.

Remember:

`bool` means the function returns either `true` or `false`.

The program first checks rows and columns.

```
for(int i = 0; i < 3; i++)

if(board[i][0] == board[i][1] &&
   board[i][0] == board[i][2] ||

   board[0][i] == board[1][i] &&
   board[0][i] == board[2][i])

    return false;
```

This might look complicated, but let's simplify it.

The first condition checks horizontal wins.

For example:

X | X | X

The second condition checks vertical wins.

For example:

X | O | O

X | O | O

X | O | X

The program also checks diagonal wins:

```
if(board[0][0] == board[1][1] &&
   board[0][0] == board[2][2] ||

   board[0][2] == board[1][1] &&
   board[0][2] == board[2][0])

    return false;
```

This checks both possible diagonal directions.

Next, the program checks whether empty squares remain:

```
for(int i = 0; i < 3; i++)
    for(int j = 0; j < 3; j++)

        if(board[i][j] != 'X' &&
           board[i][j] != 'O')

            return true;
```

If an empty square exists, the game can continue.

If no empty squares remain:

```
draw = true;
return false;
```

The game ends in a draw.

### Part I: The main() function

Your PDF ends with:

```
int main()
{
    cout << "TIC TAC TOE";

    while(gameover()){
        display_board();
        player_turn();
        gameover();
    }
}
```

The `main()` function is where program execution begins.

Let's understand the sequence:

1. Display the game title.
2. Check whether the game can continue.
3. Display the board.
4. Ask the current player to play.
5. Check the game status again.
6. Repeat until the game ends.

Finally, the program announces the winner or a draw.

Important observation about your PDF's code: It is a teaching example, not a fully robust implementation. For instance, the invalid-move branch does not safely prevent an out-of-range selection before accessing the board, and the winner-checking function uses `false` to signal both a win and a draw. Understand the intended logic, but don't assume the printed code handles every possible input safely.

## How the entire program works together

START PROGRAM

main()

Display board

display_board()

Player selects a square

player_turn()

Update the board

Place X or O

Check game status

gameover()

Game continues

Repeat the process

Game ends

Announce result

# FINAL REVISION: WHAT YOU MUST KNOW FOR YOUR CAT

Here is the whole lesson in examination-friendly language.

| Topic            | What to remember                                               |
| ---------------- | -------------------------------------------------------------- |
| C++              | A programming language used in game development                |
| High performance | C++ helps games run efficiently                                |
| Latency          | Delay between an action and a response                         |
| Game engine      | Software containing tools for creating games                   |
| Unreal Engine    | Commonly uses C++                                              |
| Unity            | Fully supports C#                                              |
| Vector           | Has magnitude and direction                                    |
| Trigonometry     | Helps calculate movement in different directions               |
| Sine             | Used to calculate vertical components                          |
| Cosine           | Used to calculate horizontal components                        |
| Calculus         | Used in physics engines                                        |
| Integrator       | Calculates updated positions and vectors over time             |
| Matrices         | Used for transformations                                       |
| Delta time       | Time between frames                                            |
| Game theory      | Study of strategic decision-making                             |
| Zero-sum game    | One player's gain equals another player's loss                 |
| Minimax          | Finds the best move assuming the opponent also plays optimally |
| MAX              | Maximizes the score                                            |
| MIN              | Minimizes the score                                            |
| Recursion        | A function calls itself                                        |
| Backtracking     | Revisiting possibilities to find a suitable solution           |

# CAT PRACTICE TEST

Now let's see whether you have understood the lesson.

These are practice questions based on your PDF, not actual examination questions.

15 CAT-style questions

15/15 answered

1\. Which programming language is recognized as an industry standard in game development in your notes?

A. Java

B. C++

C. HTML

D. CSS

2\. What is latency?

A. Game resolution

B. Computer storage

C. Delay between an action and response

D. Game animation

3\. Which mathematical branch helps calculate angles and directions?

A. Trigonometry

B. Discrete mathematics

C. Statistics

D. Calculus

4\. Which mathematical concept is used to represent direction and magnitude?

A. Matrices

B. Vectors

C. Variables

D. Loops

5\. Calculus is used in which game development system?

A. Sound system

B. Physics engine

C. Menu system

D. Login system

6\. What does Delta Time represent?

A. Time between two frames

B. Game loading time

C. Time to finish a game

D. Player reaction time

7\. What is a zero-sum game?

A. Both players always win

B. A game without rules

C. One player's gain equals another player's loss

D. A game without players

8\. What is the purpose of Minimax?

A. Create graphics

B. Choose an optimal move

C. Increase internet speed

D. Store game files

9\. What does MAX do in Minimax?

A. Minimizes the score

B. Maximizes the score

C. Stops the game

D. Creates the board

10\. What does MIN do in Minimax?

A. Maximizes the score

B. Draws the board

C. Minimizes the score

D. Changes programming languages

11\. What does recursion mean?

A. A function calling itself

B. Deleting a function

C. Printing a board

D. Changing a variable

12\. What is the purpose of the switch statement in the Tic-Tac-Toe program?

A. To check internet connectivity

B. To map the player's choice to a board position

C. To create graphics

D. To calculate speed

13\. Which C++ command receives input from a player?

A. cout

B. cin

C. return

D. break

14\. Which function displays the Tic-Tac-Toe board?

A. gameover()

B. main()

C. display_board()

D. player_turn()

15\. What happens when all nine squares are occupied and there is no winner?

A. The game continues

B. The game is a draw

C. X automatically wins

D. O automatically wins

Submit my answers

My advice: Pay particular attention to Mathematics, Zero-sum games, MAX and MIN, recursion, and the Tic-Tac-Toe code. Make sure you can explain what each function does, not just recognize its name.

When you're ready, we can do a fresh C++ and Minimax practice session tomorrow.
