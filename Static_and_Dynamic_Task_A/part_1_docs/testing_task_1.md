### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False

      # above, firstly there's no constructor statement, so self isn't necessary as a parameter. the if condition requires that equality, i.e. the value of an ace is 1, should use '==', so the test will throw an error. Else also missing ':'.
   

  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  
      # above, firstly there's no constructor statement, so self isn't necessary as a parameter. typo 'dif' prevents highest_card function from being created. There's an indentation issue of IF statement. Arguments 'card1' and 'card2' are also missing a separating comma. IF statement will produce error as it's attempting to return 'card' even though inputs are 'card1' and 'card2'


def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
      # above, firstly there's no constructor statement, so self isn't necessary as a parameter. variable 'total' has not been given an initial value. Also seems to be an indentation issue. return wants to concatenate in order to display the total, however we can only concatenate strings. will require f-string. Return indentation should also be inline with for.


```
