Here're my fancy solutions to [Advent of Code 2022](https://adventofcode.com/2022)

![](https://img.shields.io/badge/days%20completed-0-red) ![](https://img.shields.io/badge/stars%20⭐-0-yellow)

# To Use
In order to download your input files, you will need to update the secrets for your project. 
[See this documentation](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/managing-secrets-for-your-repository-and-organization-for-github-codespaces#adding-secrets-for-a-repository)
to create a YEAR secret with the year being solved (AOC_YEAR=2023) and your 
session cookie (AOC_SESSION=5FC3BD23.....) 

[This picture shows the current steps to get your session cookie from the web inspector for adventofcode.com](https://github.com/PerryHighCS/AdventOfCode/blob/master/SessionCookie.png?raw=true)

Each DayXXSolution class has a main method which will run your solutions.
Solutions come in 3 parts:

1. prepare

    Each class has a prepare method that will receive your input file for the 
    day. This is where you should parse that input into a form you can use.
    
2. part1

    The part1 method should solve the first part of the problem for the day.
    It should return the solution as a String.
    
3. part2

    Once part1 is solved, part 2 should solve the second part of the problem.
    It should return the solution as a String.

If you want to try your solution against the sample input provided in the
problem description, you need to copy it into a file in a folder named
__input/sample/day*XX*/__ where *XX* is the day number with a leading 0 if necessary
(01 for Dec 1st). Name the file whatever you want, but put the name in the
__SAMPLE_INPUT_FILENAME__ String for the proper __Day*XX*Solution__ class.
