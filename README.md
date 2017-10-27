# WEEK-8-CODEPATH
This Is Week 8 Codepath PENTESTING
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: sql injection
The find a salesman had the id in the URL and you can input the SLEEP command to prove a database SQL injection.
https://github.com/mcp352/WEEK-8-CODEPATH/blob/master/865CFBB6-42B0-459A-B862-66AD2C2750F5.GIF
Vulnerability #2: Session Hijacking/Fixation
Using the change session id tool you can take a loged in php session id and use it to log into the site.
https://github.com/mcp352/WEEK-8-CODEPATH/blob/master/86E040E2-5977-4896-B1E4-184065C265FF.GIF



## Green

Vulnerability #1: User Enumeration
When you log in to the green site with a real username and an incorrect password the "log in was unsuccessful" is bold but when you try to log in with a fake username and fake password you can see that the "log in was unsuccessful" is not bold.


Vulnerability #2: __________________


## Red

Vulnerability #1: __________________

Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
