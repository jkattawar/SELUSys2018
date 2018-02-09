## Alignment Homework

### Some of these questions do not have a right answer.

Fill out this worksheet (it can be opened in a plain text editor, like TextEdit [Mac] or TextWrangler [Mac] or Notepad [Windows]. Commit and push it to your copy of the course repo. I will pull your copies Friday at 5, and try to have comments for you by next class period, when we will discuss them. 

Feel free to work in groups, and discuss the assignments as needed. However, I do expect you to turn in your own copy, with answers in your own words.

1. Some algorithms treat a gap as a single penalty value, regardless of how large the gap is.
 Others assess a gap opening penalty, then a smaller gap extension penalty.
 When (i.e. what kind of biological scenarios) might you think it might be better to use one algorithm over the other?

I believe that a gap extension penalty is less necessary when aligning sequences from taxa that are less closely related (above genus and species level).
 Assuming you have taxa that have sequences that are very different then penalizing them for having large gaps seems excessive and unnecessary.
 On the other hand, genus and species level taxa should be penalized more for larger gaps.
 Making phylogenetic inference requires a good alignment with an attempt to recognize homology which should also requires a good alignment; 
 therefore a more strict scoring method is necessary. 

2. Breaking problems into subproblems is a common way to attack a tough problem.
 In the case of iterative alignments, we break the tree into smaller pieces. Are there biological questions for which you expect this would not be helpful? 

When dealing with taxa that are deeply diverged on an evolutionary scale, breaking up the tree and realligning it would not be very helpful.
If the taxa are so much different it is unlikely that a new or better tree would be any better than the initial tree due to reallignments.

3. From the iterative alignment section: Which aslignment (pasta_script1, pasta_script2, pasta_script3) do you think is the "best"?
 By what criteria did you arrive at this decision? 
