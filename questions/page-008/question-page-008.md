# Page 8 Question Answer

Question where three different regular expressions shall be understood.

## a)

Assume the regular expression:

`^cat$`

The initial caret is used as a metacharacter to match start of a line. Then follows the literal word cat, this will match the exact world cat. Finally there is a dollar that is a metacharacter to match the end of a line.

Effectively this means that to have a match there should be a line with a start and an end, and the exact word cat shall be part of the line. Or in short a line with the single word cat.

## b)

Assume the regular expression:

`^$`

As in part a) the caret is used as a metacharacter for start of a line and the dollar indicates the end of a line. There is this time nothing at all in between the start and end metacharacters indicating no content.

Effectively this means that to match there needs to be a completely empty line.

## c)

Assume the regular expression:

`^`

This time there is just one single metacharacter indicating start of line.

Effectively this means that the to match there needs to be a line, any line with any content, including empty lines.

This regular expression is not very useful.
