# Echo-League-Website-Testing
A repo to track testing and feedback for the EchoLeague website

-----

# QA & Bug Reporting

## Doing Quality Assurance 

Quality Assurance is a really simple to execute job, but is absolutely invaluable to make sure that EchoLeague.gg runs as  well as it possibly can.  All you really need to do to run QA for us is just go through various flows of the website and report any bugs or abnormalities that you find as you go along.  That's it!  

In addition to basic flows, you can also purposely try to use methods or techniques that you think might intentionally break the site, so that we know where vulnerabilites are.  Move fast, break as much as you can, then report what you broke so it can be fixed.

### Dev Tools and Advanced QA Techniques

In addition to simply poking around the site, you can use the Developer Tools in Chrome, Firefox, or Edge to help further stress the site or better identify issues.  They can typically be accessed by going to your browser's menu and choosing the developer tools or 'web inspect' tools.  They will let you access network panels, see a debugger console, and live-edit the HTML and CSS structure of the page.

Testing with dev tools can help stress for cases where a user might try to "bypass" or "hack" parts of the site to get where they shouldn't belong.

In addition, most dev tools now offer emulators which allow you to use your desktop browser to simulate the website running on a phone or tablet, which are important use-cases for us to test

## Reporting Bugs

If you find a bug, the best thing to do is report it on the [issues page of the repository](https://github.com/EchoLeague/Echo-League-Website-Testing/issues).  Make sure when you log the issue, you apply a label that appropriately designates its severity:

* **Minor**: Small visual or interaction bugs that are apparent, but don't really effect usability in any way (*e.g. An element not lined up correctly, text that clips off an element, buttons not showing the right color, etc*)

* **Major**: Bugs which impact usability of the site in some significant way (*e.g. A button registering misclicks, data not rendering properly on a page, elements blocking other on the page from being used*)

* **Critical**: Bugs which render parts of the site completely unusable, or severely threaten the security or structure of the website (*e.g. Users being able to access another user's data or private views, someone being able to submit false or malicious data via calls or inputs*)

### Report Structure

All reports are useful, but to make sure there is no ambiguity and that we can easily address the issue, try to stick to the following format when logging a bug (example using markdown format, which you [can read up on here](https://blog.ghost.org/markdown/))


```
**Browser:** (Chrome/Firefox/Edge) (Version)

**User State:** (Logged In/Logged Out/Any)

**Environment:** (Test Server/Local Server/Other)

**Version or Branch:** (v1.2.4/MR#6)

**Description:** (Short description of the issue)

**Steps to Reproduce:**

1. Step One
2. Step Two
3. Step Three

**Screenshots:** (Link to Screenshots/Uploaded Screenshots)

**Add'l Info:** (Anything not covered by the above that's relevant)

```

Feel free to include things like debugger logs too if you're able to generate them with the issue.  More is always better!

-----

### Resetting your Registration Data
If you need to reset your registration data so you can attempt to use the registration flow again, ping @here in the #beta-test channel to see who is available to help

### Suggestions and Feature Requests
If while using the site you think of some features or even small quality of life features, please go and make a ticket for them too!  Just use the **Feature Request** or **Style Request** labels instead of the bug labels. 
