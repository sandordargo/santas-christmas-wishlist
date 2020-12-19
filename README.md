Santa's Christmas Wishlist
===========================

Christmas is coming and every child deserves a gift, but Santa's resources are limited. We have make sure that children can choose their gifts both via mail or in person in Santa's Grotto and that they express their wish only once.

There is Santa's Big Book, with all the children's information in it. A child is identified by their:
- Name
- Address
- Date of Birth
- Unique ID

Due to the economic crisis, Santa cannot delivery anything the kids might ask for, so they have to choose among 4 options. This lets Santa both control what can children ask for and he can submit some batch orders to the elves thus he keeps production costs lower.

Children can decide whether they just want to send a mail to Santa with their choice or they can visit Santa's Grotto so they choose in person.

To support fast processing, they have to tick a checkbox on a paper with the 4 choices printed on it, it's called the Wish Sheet. Of course, enough space is left for some drawings and a personal message.

It's Santa's Wish Engine that is repsonsible for making sure that each child can only ask for a gift either by mail or in person.

Those who want to make their choice by mail, they have to register through Santa's Wich Engine by using their unique ID.

Otherwise, in person they can get their Wish Sheet either by providing their name/address/date of birth combination or by their UUID - then their Wish Sheet is also provided by Santa's Wish Engine.

Santa's Big Book is updated every year to make sure that newborns are added and adults are removed. Their might be some bugs and there are young adults who try to cheat the system, so Santa's Wish Engine also have to make sure that nobody above 18 can ask for a gift.

Santa's Wish Engine has to make sure that nobody else has the right create these sheets (nobody else can instantiate the corresponding objects) and that they cannot be copied. Yet, they can be filled in and sent back publicly.

At any point, Santa can ask for a summary how many of each gift he has to order.

1) Implement Santa's Big Book containing all the children. Each child is identified by their name, address, DOB and a UID
2) Create Santa's Wish Engine that can create the Wish Sheets. In-person and mail-in Wish Sheets are different from each other, but they share the API and data. Remember, a Wish Sheet can only be created by Santa's Wish Egnine and it cannot be copied.
3) Add the API to Santa's Wish Engine where you can ask for the Wish Sheets. 
4) Make sure that a Wish Sheet cannot be given to adults
5) Let Santa be able to get a summary whenever he'd like to so that he can see how many children asked for each gift
