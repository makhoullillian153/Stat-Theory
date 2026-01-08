# Why Homework?
This semester your performance is assessed using different forms of work such as reading quizzes, a final project, exams, and homework. Homework plays a critical role in learning the material for this course. Learning new things requires practice. Somebody can explain really well how to play a guitar. No matter how clearly they present the lesson, you won’t know which parts you can do well and which you need to work on more until you try to play the chords yourself. It takes repetition to build muscle memory. The more practice, the more efficient you are likely to become.

Homework is a time to further explore concepts we have discussed in class, identify where you need more practice, and build connections with previous material. Your ideas are still forming. Studying is the period where concepts come into focus and crystallize. After the exam, you are ready to build more levels on top of your foundation. If your foundation never settles, you may experience difficulty learning and incorporating new ideas and methods on top of a shaky or incomplete foundation.

I do not expect your homework to be flawless this semester. There are going to be times you make mistakes. Some are minor, others will help bring into focus which concepts you should review further. Success in this course does not mean you are not making any errors. How you manage the occasions when you do get stuck is how to be successful in this course!

# Use of AI on Homework
**My intention is there is no need for you to use AI this semester.** I present material in class and assign readings/videos that cover all of the topics and learning objectives for the course. This course is designed for you to complete homework based on the methods presented in class. If you make some errors on your homework, that is to be expected and a part of the learning process. When you do run into questions, you can ask me for help. Making mistakes can be frustrating, but that is also when deep and lasting learning occurs. **This course is designed so you do not need to use AI this semester, and my preference is you ask me for help if you are stuck.**

AI can be an extremely useful teaching/learning tool. **AI can also harm to your learning and prevent you from growing, so be careful and mindful how you use it.** AI provides access to tons of information. Some of the information is accurate, but AI can also provide confusing, misleading, and incorrect results. Sometimes it is not clear what is the source of the information. As your instructor, I want to make sure you are consuming accurate information from reliable sources. I also want to make sure you are using AI as a tool for learning and not over relying on AI and using it as a crutch. If we take the AI away, you still need to be able to stand on your own understanding.

**You are allowed to use AI to check or verify your own work.** In that case, please include your own original answer first. If your AI prompt returns the same or a very similar answer, then there is no need to tell me you used AI to check your answer. If AI returns a different answer or method, then I would like you to summarize that interaction and explain how your answer evolved to your final answer. See examples to help illustrate what that might look like.

**You are allowed to use AI to help you answer a question you are unable to answer yourself.** In that case, you must indicate you were unable to get started on the problem. You are not in trouble if you find yourself in this situation, so please be honest with me and yourself. It is helpful for us both to know. In that case, please include a summary of your interaction with AI that led you to your final answer. See examples to help illustrate what that might look like. Please omit any prompts that were not relevant or useful in your process.

# Thoughts About Preparing for Exams
**On exams and quizzes this semester, you are not allowed to use AI.** It is best to be honest with yourself in the learning process. If you are getting everything correct on homework but relying on AI, you are not likely to do well on the exam when you cannot use AI. If AI is helping you learn, grow, and understand concepts you previously struggled to understand great. **Avoid over reliance on AI to solve your problems!**

**If you are relying on AI to answer a few questions on an assignment, this is a warning there are gaps in your understanding that should be explored further so you can continue to grow and learn concepts in the future.** Be sure you indicate in your work which questions you could not solve yourself and needed the help of AI to solve. Review that content further (try another similar example) to see if you have corrected the misunderstanding. If you are totally stuck, you should ask a human (me preferably) for help.

**If you are relying on AI to answer most of the questions on an assignment, this an indication you struggling to understand the material on the assignment.** However, you are not in trouble from a disciplinary point of view. This is a warning that you will continue to have trouble learning material on the next assignment unless you fill in the missing gap in content. The sooner you seek help, the better! It is very possible I reach out to you to see if I can help support you. Please do not think there is something wrong. I just want you to succeed in the course, and I’m offering to help. We can work together to get you back on track, and you can be very successful in the course if you seek help.

# AI and Academic Integrity
**Presenting someone else’s work, words, or ideas as your own without proper attribution or citation is called plagarism.** This includes taking work/ideas from other students in the course, from other sources you find online, as well as using responses from AI that you claim are your own. If I see work that seems odd or different from methods we’ve discussed and it is not explained how you arrived at that answer, I will reach out to you to make sure it is indeed your work. If it becomes clear during that conversation you have claimed somebody else’s (which includes AI) work as your own, that is plagiarism and a violation of the academic integrity policy.
* The first instance, at minimum you will not be able to earn credit for the work. Depending on the extent (for example multiple questions on a single assignment), the penalty can be worse, including losing credit on the entire assignment.
* If the violation happens a second time, you will lose credit on the entire assignment, no matter the extent. Depending on the extent, the penalty can be worse. In addition, I will file an academic integrity report with the University.
You are not in trouble provided the work is yours. If you are unable to explain your work to me, then that is problematic, and that might be an indication that you have violated the policy.

# Collaboration with Others
**Collaboration with others in the course is encouraged as long as you do so responsibly.** Talking with classmates is a great way to provide/receive help and learn. It is totally fine to compare work on a homework question. If all parties have independently reached the same answer using very similar methods, that is not plagiarism. If your answers are different, then you are not permitted to use someone’s answer and claim it as your work. For example, a classmate can explain a similar example to you, and then you can correct your work on the homework problem yourself.

**It is not okay to allow another student to use your work.** If I suspect you have taken or shared work with another student, then I will reach out to all parties to make sure everyone can explain the work to me individually. If it becomes clear that a student has submitted work they do not understand or are unable to explain to me, then I reserve the right to penalize all parties involved (the giver and taker of ideas) according to the policy explained in the previous section.

# Examples of Showing Work on Homework
Suppose you are asked to find the mean hurricane force diameter of all storm observations in the data frame named ``storms`` in the ``dplyr`` package.

```
library(dplyr)
```
# Solution without AI
```
mean(storms$hurricane_force_diameter, na.rm = TRUE)
```
[1] 14.9207

The mean hurricane force diameter is $14.9207$ nautical miles.

---
**_Note:_** We have done examples in class very similar, so there is no need to explain any further. If you use AI to check your work and it gives the same result, you do not need to state that. You got the right answer on your own using techniques you’ve learned in this class. Well done!

---

# Partial Solution without AI
```
mean(storms$hurricane_force_diameter)
```
[1] NA

The mean hurricane force diameter is **NA** nautical miles, but this does not make sense. Not sure what I did wrong?

---
**_Note:_** You were close. You knew to use the ``mean()`` function so you will earn some partial credit. You tried this on your own and were not quite correct. I would leave a comment in your work about using the argument na.rm = TRUE when the vector contains missing values. Hopefully you can avoid making that mistake again. It’s great you tried to solve this on your own!

---

# Solution Using AI to Check and Improve
```
summary(storms$hurricane_force_diameter)
```
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 

   0.00    0.00    0.00   14.92    0.00  300.00    9512 

The mean hurricane force diameter is $14.92$ nautical miles.

I was not certain if this is the best since the output includes other statistics that we are not asked to provide. I typed the prompt below into Gemini AI:

> What is the R formula for computing the mean of a numeric vector?

R provided the following suggestion: ``mean(df$var)``. I knew to change the data frame name from ``df`` to ``storms`` and the variable name from ``var`` to ``hurricane_force_diameter``. Then I ran the code below:

```
mean(storms$hurricane_force_diameter)
```

[1] NA

The output **NA** does not make sense and is not the same as my previous answer. I gave Gemini AI the following prompt next:

> My data frame is named storms and the variable of interest is ``hurricane_force_diameter``. The output of ``mean(storms$hurricane_force_diameter)`` is **NA** but that is not correct. Why do you think I am getting output **NA**, and how can I fix the code?

The response explained this may be due to missing values stored in the vector ``storms$hurricane_force_diameter``. They suggested I include the argument ``na.rm = TRUE`` to account for the missing values. That worked!

```
mean(storms$hurricane_force_diameter, na.rm = TRUE)
```

[1] 14.9207

This is better than my original answer since (1) it is more accurate and (2) there is only one value output instead of getting the five number summary as well. However, one positive thing about using the ``summary()`` function is that it handles missing values better than the ``mean()`` function.

---
**_Note:_** In documenting this process, there is learning going on, and you have a record of your thought process when you review these materials for the exam.

---

---
**_Tip_** You do not need to include all of the prompts and responses you obtained. Only include the prompts that were useful in obtaining your final answer and please summarize the exchange concisely.

---

# Solution Entirely Using AI
I unfortunately was not able to solve this question on my own. To solve the problem, I looked at notes from class but could not find a similar example. Next I tried using AI. I typed the following prompt into ChatGPT:

> How can I find the mean of a numeric variable in R that has some missing values?

ChatGPT suggested the code below:

```
my_values <- na.omit(df$var)
mean(my_values)
```

I realize my data frame and variable are named ``storms`` and ``hurricane_force_diameter``, so I modified the code as follows and added comments to the code to explain what the code is doing:

```
my_values <- na.omit(storms$hurricane_force_diameter)  # remove missing values
mean(my_values)  # compute mean of vector with no missing values
```

[1] 14.9207

The mean hurricane force diameter is 14.9207 nautical miles.

---
**_Note:_** Good for you and I to both know you were stuck and unable to solve at first without getting help for AI. You are not in trouble. I might suggest trying another similar example in a day or so to see if this workflow is helping you or if relying on AI is hindering you. If you are not able to do similar examples, then it is a good time to ask a human (me) for help.

---

# Solution Entirely Using AI
I unfortunately was not able to solve this question on my own. To solve the problem, I looked at notes from class but could not find a similar example. Next I tried using AI. I typed the following prompt into ChatGPT:

> How can I find the mean of a numeric variable named ``hurricane_force_diameter`` that has some missing values in the data frame storms using R?

ChatGPT suggested the code below:

```
my_mean <- function(x) {
  clean_data <- na.omit(x)  # remove missing values
  n <- length(clean_data)  # compute number of elements in x
  xbar <- sum(clean_data) / n  # sum of x divided by n
  xbar  # print xbar to screen
}

my_mean(storms$hurricane_force_diameter)
```

[1] 14.9207

The mean hurricane force diameter is 14.9207 nautical miles.

---
**_Note:_** This code is way more complicated than needed. This was intended to be a simple one line command answer. Using code such as this on an exam is time consuming and inefficient; thus, you would not earn full credit for this work on homework or the exam since it is not an elegant way to compute a mean.

---
