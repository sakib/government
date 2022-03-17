# government

Musings of a Systems Reliability Engineer on what a modern government could look like. 

Based on principles of fault tolerance, distributed systems, continuous integration, basic statistics, and historically-relevant core principles.


## Problem Statement

How do we know our current system is broken? By example:
- 2020: Uneducated orange baboon elected to highest office in the U.S.
- 2015: Jim Inhofe (R. Oklahoma) drops snowball on Senate floor to dispute climate change. [Yes really](https://www.washingtonpost.com/news/the-fix/wp/2015/02/26/jim-inhofes-snowball-has-disproven-climate-change-once-and-for-all/).
- ????: Hundreds of millions of oil/gas money goes to people who don't understand basic science... [:(](https://www.opensecrets.org/industries/summary.php?ind=E01&cycle=All&recipdetail=S&mem=Y)
- We have to wait for old racist idiots to die off before having a chance to really change things, but by then, we will have one foot out the door.

We hold this truth to be self-evident that a modern government needs to be guided by core principles relevant to the modern age in perpetuity.


## Core Principles

- Zero tolerance for anti-science nonsense
- No money in politics
- Maximize equity (no racism)
- Design for local sovereignty


## Structure

This structure describes an interaction between two layers of government: local and federal. But this can easily be extended by chaining.

- lightly-educated citizenry self-determine laws and representatives in local governments. You want trial by combat? You got it!
- local representatives propose laws in federal government
- federal "Supreme Court", cycling highly-educated citizenry, audits whether proposed laws violate core principles
- cronjob propagates audited laws to lightly-educated citizenry for popular vote
- local laws override federal laws (opt-out model)


## Risks

- federal "Supreme Court" is a SPOF for power and may not be representative of the population. Therefore, its constituency should be independently and randomly selected, face reasonable term limits, and represent a large (100+) sample size relative to the population.
- whoever controls the standard of education determines who can propose, audit, and vote on laws. Therefore, this responsibility should be relegated to a higher power, perhaps an international standard.
- implementation of a secure identity/voting system. One citizen should have one vote and have one clear "I have education level E". This does not take into account criminal history because that adds unnecessary complexity to the issue of suffrage.
- the system should be self-righting. If it is determined that a core principle is missing, a process should exist to add it. Perhaps it is sufficient to follow the normal propose-a-law process for this.
- education is not the same as wisdom. but wisdom is relative and much harder to measure, and knowledge (NOT AGE) is a relatively effective proxy.


## Simulation

Hypothetically a well-established simulation with a proper heuristic loss_function could converge to an optimal solution and its corresponding parameter set, if such a convergence exists. If no such convergence exists, we could prove the problem intractable and be the fuck done with it.

My *Hypothesis* is that *Local optima exist*:
- Whatever the U.S. has right now is clearly better than Medieval Europe (Crusades, Black Plague, [Habsburgs](https://en.wikipedia.org/wiki/House_of_Habsburg), ...) :) 
- I am an optimist

A generic simulation would only need a diverse set of heuristics to lead to independent solution sets. For example:
- Heuristic A wants to maximize Citizen Happiness and its convergence looks like the society in the Giver, even though such a society is more or less stagnant w.r.t. technological and civic progress.
- Government X decides to buy fully into utilitarianism - well, we have a heuristic and corresponding solution for that!
- Government Y wants communism? Here's the optimal parameter set to maximize living conditions for the poor!
