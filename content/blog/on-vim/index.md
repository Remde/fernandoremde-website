---
title: On vim
date: "2021-03-11T18:12:03.284Z"
description: "And why I'm such a big fan of a 1991 technology"
---

<p>There are a few game-changing moments in our lives, be it personal or professional, that keep coming back to our memories.</p>
<p>Coding wise, I still remember how I felt when I wrote my first if statement. It came after a need: I needed to check a condition. To figure my age with a subtraction, I needed to know <b>if</b> my birthday month is less or higher than <i>current</i>.</p>
<p>If. Boom. Minds were blown. Code was written. Bad code. Nevertheless, it was enough to plant the seed for a lifelong passion. As well as a bunch of other problems. Who knew that a decade of intense computer usage would cause issues?</p>

<h3>vim</h3>
<p>vim is a 1991 text editor made for a time when we had no mice. We had awful keyboards, super slow computers, no IDEs at all, and very few, or even none, tutorials to help us through our every programming needs.</p>
<p>In vim, we move the cursor with <code>hjkl</code>, we don't copy or paste, we <code>yank</code> and <code>put</code>, and many other quirks; but what gives vim its greatness is the Modes system.</p>
<p>vim has five possible modes: <code>Normal</code>, <code>Insert</code>, <code>Visual</code>, <code>Command</code>, and <code>Replace</code>. In normal, you can't type. To type, you press <code>i</code>, go to <code>insert</code> mode, and then type. This allows for a plethora of keybinds and commands that otherwise would not be possible. <code>dd</code>, for instance, deletes an entire line. To change something between parenthesis, for example, you could do <code>ci(</code>. It's incredibly easy and even faster than using a mouse. And amazing for your wrist health.</p>

<h3>Motions and Operators</h3>
<p>What makes learning all the seemingly endless commands easy is the operators and motions system. To explain that, let's look at some motions.</p>
<p><b>Motions.</b> There is no mouse to control the cursor, so we have many keybinds to make navigation fast. <code>w</code> goes to the next word, and <code>b</code> to the previous word. <code>hjkl</code> is left, down, up, and right, respectively. <code>}</code> goes to the next block of code delimited by a blank line. We can also use numbers with that. <code>3w</code> jumps three words, <code>10j</code> jumps 10 lines down, and so it goes.</p>
<p><b>Operators.</b> Take <code>d</code>, the delete operator. <code>d</code> doesn't do anything by itself, it needs a motion. Remember them? Just append them now. <code>dw</code> deletes the next word. <code>d5b</code> deletes five words backwards. <code>d2}</code> deletes two blocks of code. You get the idea. Other operators include <code>y</code> for yanking, <code>c</code> for changing, and <code>></code> for identing.</p>
<p>It is a very unix-like philosophy of doing one thing and one thing only, keeping it orthogonal, and just combining everything together effortlessly. And the above is, of course, a very small fraction of everything that vim can do.</p>

<h3>Game-changing moments</h3>
<p>It takes a while to get comfortable with vim. After all, there are decades of bad habits to unlearn, and even more decades of new habits to learn. But it is a great feeling. It feels like playing piano, or playing a rhythm game, and seeing everything falling into place super fast is very satisfying. No moving hands and no awkward mouse movements.</p> 
<p>We, as developers, type. A lot. Code, documentation, PR descriptions, emails, messages. We rewrite, copy and paste code. We even write blog posts. Some of us. We type. It makes sense to invest in something that makes our jobs much easier, healthier and more productive, even if it looks like a behemoth at first sight.</p>
<p>vim is available in every unix machine (just run <code>vim</code>), as well as in plugin form for VS Code, IntelliJ, and every single one of your favorite IDEs. Run <code>vimtutor</code> and try it out! It may change the game for you.</p>
