# Computer Tipps

Q: I can't use some keybinding like \<Shift>\<Super>dollar, \<Shift>\<Super>parenleft, \<Shift>\<Super>parenright.\
A: Seems like this is an issue depending on the keyboard layout used. For me (US intl. with dead keys) it helped to use in dconf Editor slightly different names:\
  \<Shift>\<Super>dollar --> \<Shift>\<Super>4\
  \<Shift>\<Super>parenleft --> \<Shift>\<Super>9\
  \<Shift>\<Super>parenright --> \<Shift>\<Super>0
  
Q: How to include mailbox.org in Rambox and add auto-login?\
A: // Auto login\
document.getElementsByName("login-username-input")[0].value = "EMAIL-ADDRESS-HERE"; document.getElementsByName("login-password-input")[0].value = "PASSWORD-HERE"; document.getElementById("login-login-button").click();

Q: How to change Anki from Latex to MathJax?\
A: // Use "Find and Replace"\
Find: \\[\\$\\$\\] and Replace With: /( and Find: \\[/\\$\\$\\] and Replace With: /)\
don't forget to check "Treat input as regular expression"
