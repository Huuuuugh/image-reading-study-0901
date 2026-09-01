Image reading study
===================

Open the batch page you were assigned (batch_01.html ... batch_10.html) in Chrome or
Edge, enter your Worker ID, and answer every question about the image shown.
Answer exactly what is drawn — do not infer what 'should' be there.
If the thing the question asks about is not present in the image at all, answer with
a single dash -
Count an item only if it is more than half visible; ignore anything cut in half or
less by the edge of the picture.
The images are AI-generated and may contain garbled text, misaligned layouts, or
empty cells. Answer exactly what is actually printed.
When all questions are answered you will receive a completion code; export the JSONL
answer file and submit both.


1. THE BRIGHT GREEN RECTANGLE
-----------------------------
Some pictures have a thin bright-green rectangle drawn on them. The green rectangle
marks the thing the question is asking about. It was drawn on top of the picture
afterwards: it is not part of what was printed or photographed. So never answer with
the colour, size or position of the green rectangle itself, and never count it as an
object in the picture.


2. WHICH ONE, WHEN THE PICTURE HOLDS SEVERAL
--------------------------------------------
Some questions say "this row", "this line", "this cell", "this window", "this end",
"this card", while the picture holds more than one of that thing. Work down this
list and stop at the first rule that applies:

  a. A green rectangle is drawn  ->  answer about what is inside the green rectangle.
  b. No green rectangle, and only one of them is more than half visible  ->  answer
     about that one (the half-visible rule above decides it).
  c. No green rectangle, two or more are more than half visible, but they would all
     give the same answer  ->  give that answer.
  d. No green rectangle, two or more are more than half visible, and they would give
     different answers  ->  answer with a single dash -
     Do not guess which one was meant. A dash here is a correct answer, not a
     refusal, and it is never counted against you.


3. THREE KINDS OF DRAWING, IN PLAIN WORDS
-----------------------------------------
Technical drawings. A "plan" is the view looking straight down from above, like a
floor layout. A "section" is what you see after sawing the object through and
looking straight at the cut face. An "elevation" is a flat face or wall seen
straight on. A short zig-zag or wavy line drawn across a part means the part is
longer than the paper and has been broken off there; it is called a break line. The
boxed strip of writing under or beside a drawing that carries its title, scale and
date is called the title block.

Round charts. A compass rose, a spider-web chart (also called a radar chart) and a
clock face are all read the same way: from the middle outwards. A wedge runs from
the centre out to the outer edge; the centre end is the smallest value, the outer
edge is the largest, and the name of that wedge's axis is printed near the outer
edge. A clock face may be lettered with Roman numerals (I, II, III, IV, ...); if the
question asks for a number, answer in ordinary digits (1, 2, 3, 4, ...).

Tables, and the word "figure". In these questions the word "figure" always means a
printed NUMBER — never a picture, a drawing or an illustration. A "line of figures"
is a printed line with numbers on it. A row is one line running across a table,
usually a name on the left and its number on the right. A merged cell is one big box
that spans several rows or several columns of the grid around it. An LCD is the lit
numeric display on a machine's front panel.


4. HOW TO WRITE THE ANSWER
--------------------------
  a. Copy the characters that are printed. Keep a comma that sits inside a number
     (1,500 stays 1,500) and keep a decimal point (0.79 stays 0.79). Keep a leading
     zero (007 stays 007).
  b. Leave out a currency symbol, and leave out a unit of measurement, unless the
     question asks for it:  $0.79 -> 0.79,  12 pt -> 12,  25c -> 25,  20 kg -> 20.
  c. Keep the capitals as they are printed: if the picture says BEFORE, write
     BEFORE. When the question offers a list of words to choose from, answer with
     the word exactly as the question spells it.
  d. When a question fixes the exact shape of the answer, follow it to the letter.
     Example: "Answer strictly as 'day=<number> month=<Mon>' and nothing else."
  e. When a question asks for several values, separate them with single commas and
     no spaces (4,4,2,0), in the order the question names.
  f. Yes-no and a-b answers are entered with the page's buttons or the y / n / a / b
     keys; write nothing else in those.
