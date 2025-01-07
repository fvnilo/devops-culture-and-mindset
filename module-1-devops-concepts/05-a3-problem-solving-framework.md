# A3 Problem Solving Framework

A3 refers the European paper size equivalent to 11" x 17" used to outline templates for this framework.

## Steps

|A3 Steps|PDCA Steps|
|--------|----------|
|Background|Plan|
|Problem statement/current condition||
|Goal/Target condition||
|Analysis||
|Proposed countermeasures|Do|
|Implement plan|Check|
|Follow-up actions|Act|

Spend time on the _Plan_ phase (Step 1 to 4) and do not rush to the _Do_ Phase.

### Step 1: Set the Background

Include statement of how problem directly impact business outcomes.

_Example_: How quality issues were creating production incidents and impacting customers.

### Step 2: Current Condition and Problem Statement

Aligned with the improvement kata language. Current reality means where things stand today.

_Example_: Quantify the production incident created due to quality issues. Ideally, tie it with revenue loss or another business metric. The statement could be: Every web release we have 3 high severity incidents impacting our customers.

### Step 3: Develop the Goal

Target state we are trying to achieve and explain how the outcome will be measured.

_Example_: Having 0 high severity incidents following a release.

### Step 4: Performance Analysis

Also called _Root Cause Analysis_

Identify the root cause. There may be multiple contributing factors.

_Example_: The team documents multiple symptoms and contributing factors. This could be, in the case of a quality issue, automation of integration testing, unit test coverage and process related issues such as allowing exception late in the lifecycle.

### Step 5: Brainstorm

How do we intend to reach the target condition? Determing countermeasures.

_Example_: Establish a gate to reduce the number of exception and expect to lower the number of incidents by 2.

Decision criteria for countermeasures: effort vs. impact

_Example_: If it will take a month to implement integration test automation and the hypothesis is that it will reduce the incident count by 1, while changing the process is expected to reduce the count by 2 and is effective immediately, we propose the process change first.

### Step 6: Implementation Plan

- Enables to check results
- Confirms impact on current condition

Pick one of the countermeasure, document the actions needed to implement it, a timeline for implementation and the person(s) responsible

_Example_: Create 15 additional automated test scripts and assign to QA manager.

### Step 6: Update

Update "standard work" based on steps taken.

_Example_: Automated test scripts are checked in into a library and become part of the standard QA process
