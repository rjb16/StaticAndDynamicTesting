### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame


  def checkforAce(card) # naming convention should be snake case to fit other functions
    if card.value = 1 # operator = is for assignment, should be == to check for equality
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2) # dif should be def and there is a missing comma between the two arguments
  if card1.value > card2.value #indent this block
    return card # there is no variable called card, it should be card1
  else
    return card2
  end
end # should be indented so that it matches the start of the function
end # this closes the class so it should come after the following function which references the class as "self"

def self.cards_total(cards)
  total # need to assign a starting value to this variable
  for card in cards
    total += card.value
    return "You have a total of" + total # this should be placed outside of the for block. It will return after the first loop which is not intended, it also needs to have an extra space after of. It also should use string interpolation for total variable as + operator will not work 
  end
end
```
