# operating-platforms-portfolio
CS-230-J5952 Operating Platforms 21EW5

* Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was "The Gaming Room" - they wanted to extend their android application to multiple platforms (eg: iOS.)

* What did you do particularly well in developing this documentation?

Well we didn't write documentation in this course, we wrote design documents which are not the same thing. I'd like to think the suggestions I made would have better served The Gaming Room in terms of cost not only in terms of operation but also in maintenance of code even if it may or may not have been different from the original design.

* What about the process of working through a design document did you find helpful when developing the code?

Having a design document to refer back to could theoretically help reduce development cycles.

* If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

Well I guess I would figure out what the client actually wanted and adjust my specifications accordingly.

* How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the users needs as "We want our application to run on other platforms" and that was really all I had to go on besides contextual hints from the assignment templates and rubrics. What makes this particularly frustrating is that knowing the user's needs is vital to actually writing meaningful design specifications.

* How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached in a way that would make sense to me which was: why would you store all of your data in-memory (barring a redis analogous cache) instead of a database, and since we were tracking all data from all games even though only one was being played at a time (in a schrodinger's kind of way) it made no sense at all to me to do that. Much of the assignments involved reinventing the wheel and this doesn't make sense from an operational cost, performance, or development time perspective. Singleton instances are generally a code smell indicating a bad process design. In a real world scenario these things could be clarified over email or the initial meeting, and that's what I would do differently.
