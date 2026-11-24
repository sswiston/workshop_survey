# Variable descriptions

These descriptions are summaries of the variables in the datasets; for exact survey questions, see associated survey files & manuscript.

* `verbatim_yn_pre` Whether the participants agree for their pre-workshop written responses to be quoted in publication
* `preworkshop_survey_timestamp` When the participant completed the pre-workshop survey; used to associate participants with each workshop

* Pre-Workshop Survey Question 1: Participant's career stage (multiple choice -- pick one)
    * `pre1a`
        * 1: Undergraduate student
        * 2: Master's student
        * 3: Ph.D. student
        * 4: Postdoctoral researcher
        * 5: Faculty
        * 6: Non-faculty professional
        * 7: Other (specify)
    * `pre1b` write-in responses for other career stages
* Pre-Workshop Survey Question 2: Participant's goals (checklist -- check all that apply)
    * Question 2a (0 = no, 1 = yes)
        * `pre2a___1` Learn about questions
        * `pre2a___2` Learn about models
        * `pre2a___3` Learn about software
        * `pre2a___4` Try out coding
        * `pre2a___5` Decide about research
        * `pre2a___6` Discuss research ideas
        * `pre2a___7` Network
        * `pre2a___8` Resume/CV
        * `pre2a___9` No goals
        * `pre2a___10` Other (specify)
    * `pre2b` write-in responses for other goals
* Pre-Workshop Survey Question 3: Participant's experience with topics (1 = unfamiliar, 2 = somewhat familiar, 3 = competent, 4 = highly competent, 5 = expert)
    * `pre3a` Probability and statistics
    * `pre3b` Molecular phylogenetics
    * `pre3c` Divergence time estimation
    * `pre3d` Biogeographic models
    * `pre3e` Bayesian models
    * `pre3f` Markov chain Monte Carlo
    * `pre3g` Unix command line
    * `pre3h` RevBayes
* Pre-Workshop Survey Question 4: How often research-related events occur (1 = never, 2 = rarely, 3 = sometimes, 4 = often, 5 = very often)
    * `pre4a` Stopped due to software
    * `pre4b` Continued despite software
    * `pre4c` Stopped due to programming
    * `pre4d` Continued despite programming
    * `pre4e` Stopped due to statistics
    * `pre4f` Continued despite statistics
    * `pre4g` Stopped due to model
    * `pre4h` Continued despite model
* Pre-Workshop Survey Question 5: Participant's research plans
    * `pre5a` Do you plan to use methods (1 = yes, 2 = no, 3 = unsure)
    * `pre5b` When do you plan to start (1 = already using, 2 = within 3 months, 3 = 3–6 months, 4 = 6–12 months, 5 = after 1 year)
    * `pre5c` How you plan to apply the methods (written response)

* `verbatim_yn_post` Whether the participants agree for their post-workshop written responses to be quoted in publication
* `postworkshop_survey_timestamp` When the participant completed the post-workshop survey; used to associate participants with each workshop

* Post-Workshop Survey Question 1: Did the workshop meet your expectations & why
    * `post1` Written response
* Post-Workshop Survey Question 2: How participant's confidence changed regarding topics (1 = much less confident, 2 = less confident, 3 = about the same, 4 = more confident, 5 = much more confident)
    * `post2a` Probability and statistics
    * `post2b` Molecular phylogenetics
    * `post2c` Divergence time estimation
    * `post2d` Biogeographic models
    * `post2e` Bayesian models
    * `post2f` Markov chain Monte Carlo
    * `post2g` Unix command line
    * `post2h` RevBayes
* Post-Workshop Survey Question 3: What is one thing you could implement easily
    * `post3` Written response
* Post-Workshop Survey Question 4: How likely are you to use tools & why
    * `post4a` Rating likeliness (1 = very unlikely, 2 = unlikely, 3 = neutral, 4 = likely, 5 = very likely)
    * `post4b` Why (written response)
* Post-Workshop Survey Question 5: Which skills or tools do you plan to use
    * `post5` Written response
* Post-Workshop Survey Question 6: More or less likely to use models & why
    * `post6a` Rating likeliness (1 = much less likely, 2 = less likely, 3 = about the same, 4 = more likely, 5 = much more likely)
    * `post6b` Why (written response)
* Post-Workshop Survey Question 7: Helpfulness of activities (1 = very unhelpful, 2 = unhelpful, 3 = neutral, 4 = helpful, 5 = very helpful, 6 = NA)
    * `post7a` Lecture-style presentations
    * `post7b` Group discussions
    * `post7c` Coding by yourself
    * `post7d` "Coding along" with the instructor
    * `post7e` Workshopping research ideas
* Post-Workshop Survey Question 8: Workshop challengs and how you handled them
    * `post8` Written response
* Post-Workshop Survey Question 9: Will participatory live coding make implementation easier
    * `post9` Rating easiness (1 = much less easy, 2 = less easy, 3 = about the same, 4 = more easy, 5 = much more easy)
* Post-Workshop Survey Question 10: Will participatory live coding make implementation likelier
    * `post10` Rating likeliness (1 = much less likely, 2 = less likely, 3 = about the same, 4 = more likely, 5 = much more likely)