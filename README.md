# CS-Math
[![Green Tea Licence Badge](https://img.shields.io/badge/LICENCE-Green%20Tea-brightgreen.svg?link=https://github.com/DragonStuff/GreenTeaLicence&link=https://github.com/DragonStuff/GreenTeaLicence)](https://github.com/DragonStuff/GreenTeaLicence)

## Logic

### Logical Connectives
___

The purpose of logical connectives is to form statements.

~P == !P == NOT P    
P v Q == (P && Q) == P OR Q    
P ^ Q == (P & Q) == P AND Q
P => Q == 


### Statements
___

A statement/proposition is a sentence that is true or false, but not both.

E.g: "2+3 = 5" IS TRUE. "There are 6 people in this room" IS EITHER TRUE OR FALSE.

__Showing that a statement is either TRUE or FALSE.__    
_If x² = 9, then x = 1 or x = -1._

_If x = 1 then x² - 1 = 0 x² = 1_    
_If x = -1 then x² - 1 = 0 x² = 1_

  x = [1, -1];
  for (n in x) {
    if (x*x = 9) {
      print("This will never be true.");
      return true;
    } else {
      return false;
    }
  }
  return 0;
  

__The statement is false.__


