# Alpha Hack Program

## Introduction

The aim of this document is to outline an alternative approach to learn and explore through hacking and tinkering without limits but with certain focus.

## The Idea

The idea behind this project is to let us go above and beyond the usual cases we see normally and learn new things in a fun and collaborative way.
The SSAs team has good command of several areas as a team, meaning we cover a lot of ground where we are specialists. Nevertheless these days we don’t spend much time together and although we still share those things we consider important we don’t gather together with a purpose (even if the purpose is not having a purpose but progressing in a certain direction).
This project wants to fix this to some extent proposing this program based on a unit of work, the **Hacking Sprint**. 

## The Hacking Sprint

In short, a **Hacking Sprint** or **Sprint** is a collaborative hacking action that takes place in a short period of time with a bold goal to achieve that makes the team go above and beyond the usual.
But before going deeper with the unit of work. Let’s explain the basics of the program.

## The Principles

1. Learn while having fun as a team.
2. Crazy ideas are welcome. Boring stuff is not.
3.  Stretching our capacity to reach bold targets.
4. Align technical goals with current needs if they match the first two items.

## The Approach
Hacking sprints of variable duration. Depending on the complexity of the goal the sprint duration will range between one day/three hours to several days/1 hour a day.

- Each hacking sprint has a sole goal.
- The goal should be crazy and bold but somehow achievable in a reasonable amount of time. It HAS to be defined in a sentence (of reasonable length).
- Frugality is a must but bold targets cannot be ruled out only because of budget.
- Focus, we push together to achieve the goal.
- There should be a tangible output.

> **“IT SHOULD NOT BE PERFECT NOR PERFECTLY DEFINED IT’S BETTER FUN THAN SOLID”** we gather to explore, to break, to tinker...

## The Benefits

1. Gathering together crazy people to do crazy stuff to learn something new is by itself a (the main?) benefit.
2. Collecting results in a git repo is a must, crazy people tend to forget and scatter ;-)
3. Happier people with stronger relationships.
4. Prepare the team for unpredictable obstacles.
5. Bugs found, enhancement proposals.

## Examples of Hacking Sprints

These are just a starting point… take timing with a grain of salt.


<table>
    <tr>
        <td><b>Title:</b></td>
        <td>Local Copilot.</td>
    </tr>
    <tr>
        <td><b>Goal:</b></td>
        <td>Take an LLM model crafting around coding (leaderboard here). Connect it with our Visual Studio Code or other IDE.</td>
    </tr>
    <tr>
        <td><b>Output:</b></td>
        <td>Learn about the process of integrating IDEs and local coding relating LLMs.</td>
    </tr>
    <tr>
        <td><b>Timing:</b></td>
        <td>4h 1 day</td>
    </tr>
</table>

<table>
    <tr>
        <td><b>Title:</b></td>
        <td>Local Copilot tuned for migration.</td>
    </tr>
    <tr>
        <td><b>Goal:</b></td>
        <td>Take a code base, examples of migration from A to B and a vector database to enhance our local copilot. Demonstrate how better it performs with/without local examples.</td>
    </tr>
    <tr>
        <td><b>Output:</b></td>
        <td>Learn about the process of integrating IDEs and local coding relating LLMs.</td>
    </tr>
    <tr>
        <td><b>Timing:</b></td>
        <td>4h 1 day</td>
    </tr>
</table>


## Implementation

### Where? How?

This is an activity to be run remotely using RHPDS whenever suitable, in some cases we will need setups in cloud or bare metal environments. Additionally some hardware and soldering could be involved.
Glue, cardboard, paper, a computer, … the usual... and a soldering iron for the bravest.

### Before running the Hacking Sprint itself

After finishing the sprint we should have a short (30 mins max) wrap-up meeting where we review what we have achieved and define the next sprint from the list of potential sprints to choose from.
The list of sprints should be in a git repository, in fact this very document (in a different format) should all be in that git repository.

### Gathering results

As we said before, crazy people tend to be forgetful and scatter but we all love repos so the first thing to do when we define the next Hacking Sprint should be to create a git repo in the git organization set for this program.
In the repo, no wonder, there should be:

- A README file with the goal and a brief description (if necessary) of the Hacking Sprint
- Sources
- Scripts to set the environment up (or other elements)

## Index

- [Synapse:](https://github.com/alpha-hack-program/synapse) Hacking Sprint consisting on connecting clusters in different geos using different technologies (Skupper and _Submariner_) and exploring different application patterns that fit in this scenario.
- [VPA Adventure:](https://github.com/alpha-hack-program/vpa-adventure) Having fun with the Vertical Pod Autoscaler
