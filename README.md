# CyberWeek7
1. Vulnerability Name or ID: Authenticated Stored Cross-Site Scripting
  Cross-site scripting vulnerability in the text editor box in pages and writing/editing posts.
  Vulnerability types: XSS
 
  If the attacker types /* <a href="[caption code=">]</a><a title=" onmouseover=alert('test')  ">link</a>. */
  Then WP will become test
  Gif: http://g.recordit.co/AkE1Bui54v.gif

