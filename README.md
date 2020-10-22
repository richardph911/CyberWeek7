# CyberWeek7
  # 1. Cross-site scripting 
  
  Vulnerability in the text editor box in pages and writing/editing posts.
   - Vulnerability types: XSS
   - Tested in v. 4.2
   - Fixed in v. 4.2.3
  - Step to recreate:
  + If the attacker types /* <a href="[caption code=]"></a><a title=" onmouseover=alert('test')  ">link</a>. */
  Then WP will become "test" hyperlink
  
  GIF Walkthrough: 
  http://g.recordit.co/AkE1Bui54v.gif

  # 1. User Enumeration
  
   - Vulnerability types: User Enumeration
   - Tested in v. 4.2
   - Fixed in v. 4.7.3
   - GIF Walkthrough
   http://g.recordit.co/8TqbMU0RRt.gif
   
   - Step to recreate:
   + Create a new user account
   + Enter admin as a username and an invalid password to log in such as 123
   + An error message is shown to tell attacker where the error comes from.
   + When you randomly input username and password, it shows the error which is invalid username
