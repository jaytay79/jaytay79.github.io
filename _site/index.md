## RDEFINE SITE RACF.GURU

I really only bought this domain for the email but figured I may as well put _some_ content up alongside it. More content may follow but this will do for now.  

### ADDSD 'JIM.TOOLS' UACC(READ)  
[z/OS tools](https://github.com/jaytay79/zos) - SETRRCVT and some other bits and pieces  
[IRRXUTIL samples](https://github.com/jaytay79/IRRXUTIL) - Samples of IRRXUTIL  
[ENUM](https://github.com/mainframed/Enumeration) - Enumeration Rexx in collaboration with SoF & Ayoul3  
[Probable Wordlists](https://github.com/jaytay79/Probable-Wordlists/tree/RACF/Real-Passwords) - Passwords edited to conform to UPPERCASE and 8 character max standards  

### RACLINK ID(JIM) LIST  
[Bigendian Smalls](https://bigendiansmalls.com)  
[Soldier of FORTRAN](https://mainframed767.tumblr.com)  
[Henri Kuiper](https://zdevops.com)  
[/r/mainframe](https://reddit.com/r/mainframe/)  
[Nigel Pentland's Utilities](https://www.nigelpentland.co.uk/utilities/)  


### LISTUSER JIM
[LinkedIn](https://www.linkedin.com/in/jim-r-taylor/)  
[email](mailto:contact@racf.guru)  

### PERMIT 'JIM.BLOG.STUFF' ID(*) ACCESS(READ)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>