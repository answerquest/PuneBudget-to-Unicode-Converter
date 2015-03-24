# PuneBudget <==> यूनिकोड परिवर्तित्र (unicode converter)

Aim: Reliably converting Marathi or Hindi language text from a legacy font used in Pune Municipal Corporation's Budget Book and some other documents.. to Marathi language Unicode text.

Status : Successfully done for simple paragraph text.

The basic HTML file (PuneBudget_to_Unicode_Converter.html) has an input textbox and an output one. We copy-paste text from the PDF to here. It can be anything from a word to a paragraph.. but all in simple text; no formatting apart from newlines.

Click the Convert button,

And the output text box is populated with the same text in Unicode format. The user can compare this with the original PDF to check for accuracy.

In case of any inaccuracies found, please write to nikhil.js [at] gmail.com . Or fork, fix and pull request!

This code isn't my creation : It has been adapted from other such converters listed here: https://sites.google.com/site/technicalhindi/home/converters, and people in that community helped get me started on this.

The excel file here has the mapping information in an easier-to-understand format, by listing out the full ASCII charset.

## What's Next / Help Wanted
Need to make this happen for excel sheets. Meaning at most basic level, how the same function operating on the textboc here can operate iteratively on every cell in a certain excel sheet. Maybe a macro function or an executable script? 

At the very least, need to make this CSV-compatible. Which means handling enclosing quotes etc carefully. Presently double-quotes maps to single-quote in the font conversion, and comma's are commonly used in the text.