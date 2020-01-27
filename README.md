# sendmo-live
sendmo-live Assignment

To install locally:

git clone https://github.com/me4153fmkhan/sendmo-live

cd sendmo-live

pip3 install --user -r requirements.txt

If everything goes well, access it at http://127.0.0.1:5080 


Sendmo Live Testing Scenario

Sendmo Live is a handy app written in python and Flask to share messages between users of a startup. Here’s the cast of characters:

1. Tim - is the Sr. developer 
2. Elliot - is a junior developer
3. Admin - is the system and security administrator

Mr. Tim has burned the midnight oil for a whole weekend to crank out this application. He’s pretty busy though but wants to do the right thing when it comes to security. Tim instructed Elliot to catchup with the admin and apprise him of any important issues. 

The admin of course is also busy. She hasn’t had an opportunity to thoroughly review this app but she mentioned to Elliot something called the OWASP Top-10. Elliot has never heard of it before and unfortunately forgot to mention it when he debriefed with Tim. 

Needless to say, a couple of issues have already crept up.

1. Elliot reported that some users were leaving creepy messages with weird looking characters and symbols. Tim quickly reacted and instructed Elliot to enable the CSP header to block these attempts. Elliot did his best to enable the directives he thought were necessary to resolve the issue but not completely block script execution just in case it broke something.
2. The create user page and CSP pages were visible to all users. They have been moved to only allow admin users to view them now.
3. Three
4. Four
5. Five
6. Six

Here’s your’s challenge should you care to accept it. Help the Admin and this scrappy startup to review the webapp for security related issues. The Admin has been notified of this security project but she only had a rough idea about the timeframe and nature of this testing. Assume that the webapp is live and other users might be able to view or respond to your attempts.  Our advice to you, as someone very wise put it, “speak softly, but carry a big stick”.

Lastly, in order to make a lasting impression, try to report your issues in an easily relatable but standard format (maybe the OWASP Top 10 thing might come in handy). At a minimum, please include the description of the issue, risk it might pose, the exact steps to replicate it and any screenshots (if applicable). You might want to consider adding your recommendations on how to fix the issue as well using specific examples or code snippets whenever possible.

Good luck!

Sendmo Live Benefactors.
