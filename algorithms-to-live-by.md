## Optimal stopping problem

Best odds for finding the best apartment - spend 37% of your apartment hunt (eleven days if you've given yourself a month for the search); be prepared to immediately commit;

There is a particular set of problems that all people face, problems that are a direct result of the fact that our lives are carried out in finite space and time.

- What should we do, and leave undone, in a day or in a decade? 
- What degree of mess should we embrace - and how much order is excessive? 
- What balance between new experiences and favored ones makes for the most fulfilling life?

An algorithm is just a finite sequence of steps used to solve a problem, and algorithms are much broader - and older by far - than the computer. Long before algorithms were ever used by machines, they were used by people.

Origin - Persian mathematician al-Khawārizmī, 9 century, book of techniques for doing mathematics by hand called "al-Jabr wa'l-Muqābala"

al-jabr = algebra

earliest known math algorithms - four-thousand-year-old Sumerian clay tablet (near Baghdad) describes a scheme for long division.

cook bread, knit a sweater .. following an algorithm;

don't always consider all your options.  
don't necessarily go for the outcome that seems best every time.  
make a mess on occasion.  
travel light.  
let things wait.  
trust your instincts and don't think too long.  
relax.  
toss a coin.  
forgive, but don't forget.  
to thine own self be true.  
living by the wisdom of computer science doesn't sound so bad after all.  
and unlike most advice, it's backed up by proofs.

**OPTIMAL STOPPING / WHEN TO STOP LOOKING**

The ultimate catch-22 of the heart

Crucial dilemma is not which option to pick, but how many options to even consider.

37% Rule

**Look-then-leap rule**  
You set a predetermined amount of time for "looking" - that is, exploring your options, gathering data - in which you categorically don't choose anyone, no matter how impressive. After that point, you enter the "leap" phase, prepared to instantly commit to anyone who outshines the best applicant you saw in the look phase.

**Threshold Rule**  
Immediately accept an applicant if she is above a certain percentile. No need to look at an initial group of candidates to set this threshold, but we do, however, need to be keenly aware of how much looking remains available.

**EXPLORE / EXPLOIT - THE LATEST VS THE GREATEST**

Every day we are constantly forced to make decisions between options that differ in a very specific dimension: do we try new things or stick with our favorite ones? We intuitively understand that life is a balance between novelty and tradition, between the latest and the greatest, between taking risks and savoring what we know and love. But just as with the look-or-leap dilemma of the apartment hunt, the unanswered question is: what balance?

Exploration is gathering information, and exploitation is using the information you have to get a known good result. It's fairly intuitive that never exploring is no way to live. But it's also worth mentioning that never exploiting can be every bit as bad.

> "Seize the day, boys. Make your lives extraordinary." - Robin Williams, Dead Poets Society. 

> To try and fail is at least to learn; to fail to try is to suffer the inestimable loss of what might have been.

**Win-stay, lose-shift algorithm**  
Choose an arm at random, and keep pulling it as long as it keeps paying off. If the arm doesn't pay off after a particular pull, then switch to the other one. Would one disappointment be enough to induce you to give up on it? Good options shouldn't be penalized too strongly for being imperfect. WSLS doesn't have any notion of the interval over which you are optimizing. 
> Richard Bellman's trick is to start backwards, imagine the final pull, then turn to the second-to-last opportunity.. all the way back to the start.

Multi-armed bandit problems stayed unsolved.