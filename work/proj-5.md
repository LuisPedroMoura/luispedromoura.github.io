---
title: Feedzai's Anti-Money Laudering Rules Test Template
---

![Feedzai Anti-Money Laudering Rules Test Template]({{ }}/assets/img/work/proj-5/img1.jpg)

The Rules Test Template was an initiative of making rules testing available for all teams in Feedzai using the AML Solution, especially the Customer Success teams.

Previously, rules were tested by injecting events with huge payloads in the system using Postman and performing specific actions in the system through API or RMI. Then it was necessary to access multiple systems to verify that the expected outcomes had propagated. These tests were very difficult to maintain and for most of the time executed manually by changing the values necessary for each test.

The Rules Test Template completely automates the process from end to end. Even a non-technical team member can now create a CSV with only the fields that are relevant to test the rule (usually 4 to 8 instead of hundreds) and specify in a builder pattern the expected results and intended validations. Because multiple systems and components are exercised throughout these tests, this has become the standard AML Solution System-tests Framework.

<!--<a href="https://github.com/LuisPedroMoura/The_BlueBerry_Project" class="btn btn-primary" role="button">Check this Project on GitHub!</a>-->

