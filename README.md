# The zen of Recruiterbox Design

This is an attempt to ensure we have a consistent approach of making product, design and UX decisions. The hope is that a following a framework will help us make better decisions as a team

## Think User Scenarios
At Recruiterbox, we first and foremost think of what is the user trying to achieve in the real world. We call this a user scenario. A user scenarios is not feature or any other artifact of Recruiterbox. It is a problem the user wants to solve.

Often, users themselves are guilty of recommending features rather than the problem they wish to solve. It is our job to strip off the suggested solution and focus merely on the problem.

A good product team has a bank user scenarios it tries to solve (rather than a list of features). All customer feedback and internal ideas add to this bank. Now we pick each scenario and ask the following questions:

## Should we handle a given User scenario?

1. Does this scenario happen really occur (often enough) ?
	- Rarely will you find scenarios that users haven't already talked / asked about
	- You should find this scenario in your existing product usage, or support questions
	- For instance, to answer if people do salary negotations as a step, you will find interviews intv. feedback related to this inside rbox

2. Would handling this scenario introduce artifacts that other users don't care about?
 	- Most rich products start looking cluttered because they force users to see or choose things they don't care about. We should ideally avoid handling such scenarios

3. In order to truly handle this scenario, are there other scenarios that also need to be handled?
	- Ex: Making Interview rating optional might one way of handling Salary negotiation events. However, salary negotiation in itself might be an important enough scenario that needs independent handling

4. Is it in scope of the product?

5. Do you consider this scenario to be an antipattern (or against a best practise that Recruiterbox encourages)
	- What hiring best practices does Recruiterbox encourage?
		- Hiring is inherently collaborative
		- Companies can be data driven in their hiring 
		- Decisions (Rejections, advancement etc) should be objective (not qualititive / emotional)
		- Candidates shouldn't fall through cracks
		- Candidate's shouldn't be abused (email spam etc)

6. Are you handling this scenario for purely legacy / migration reasons?
	- Think of the end state you want to achieve, or imagine you were designing this fropm scratch. What decisions would you make?
	- Now find a migration / transition plan to this end state

## How to handle scenarios:
Lets say, you went through the questions in the previous section and decided to handle a scenario. This section will help you answer how to handle it

1) Given a scenario, pick one of the following ways to handle it
	(a) Create a specialized artifact (example: Application screening, reject state, hired state)
	(b) Extension of an existing artifact (ex: Mark a candidate conversation as private)
	(c) Expect the user to hack/workaround existing artifacts to handle it (ex: )
The choice depends on how important or frequent the scenario is. Use (a) if and only if users understand and use this artifact outside of Recruiterbox (in the real world) and it is very frequently used (example: Openings, Candidates, Interviews etc). Use (b) when an artifact may is less frequent. Use (c) to handle edge cases

2) Make a lean product
	- Find the least number of artifacts necessary to handle most scenarios

3) Specialize workflows for frequent scenarios
	- Certain scenarios are rich and frequent enough that it helps users if you handle them as specialized workflows. For example, rejecting a candidate requires recording a reject reason, sending a rejection letter, and removing the candidate from the pipleine together. This is best handled as a single workflow rather than a colelction of independent steps. Other examples are application screening workflow where reject/forward are the only decisions a user makes
	- Handle the most often activities with minimal clicks
	
### To conclude
Whatever decision you make about a scenario based on above questions, record it and reuse it in case the question arises again.

