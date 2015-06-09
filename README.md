# legislation-builder
This is a web application that builds legislation for high school forensics (NSDA Congressional Debate and NCFL Student Congress).

The public interface is written mostly in HTML5 and Javascript/jQuery and makes use of client-side session storage to hold the draft legislation. PHP is used for a bit of templating but mostly to produce the final legislation in Microsoft Word (Office Open XML) format.