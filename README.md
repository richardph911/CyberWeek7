# CyberWeek7
  # 1. Cross-site scripting 
  
  Vulnerability in the text editor box in pages and writing/editing posts.
   - Vulnerability types: XSS
   - Tested in v. 4.2
   - Fixed in v. 4.2.3
 
  If the attacker types /* <a href="[caption code=]"></a><a title=" onmouseover=alert('test')  ">link</a>. */
  Then WP will become test
  
  GIF Walkthrough: 
  http://g.recordit.co/AkE1Bui54v.gif

