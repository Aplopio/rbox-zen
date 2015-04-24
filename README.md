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

5. Do you consider this scenario to be an antipattern (or against a best practise)
	- What best practices does Recruiterbox encourage?
		- Hiring Collaboration should be easy
		- Decisions / Rejections / feedback should be qualified
		- Don't make me login / register unless required


Whatever decision you make about a scenario based on above questions, record it and reuse it in case the question arises again.

