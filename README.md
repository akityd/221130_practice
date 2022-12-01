# 221130_practice

my_name = "Aki"
my_number = 9
math_stuff = 80 + 10 - 58

my_list = ["Good", 3, "Bad", "Great",4]

print(87)
print(my_name)
print(my_list)

card_suits = ["Diamonds", "Heart", "Clubs", "Spades"]
print(card_suits)

import random
print(card_suits)
random_suit = random.choice(card_suits)
print(random_suit)

def pick_a_card():
  card_suits = ["Diamonds", "Heart", "Clubs", "Spades"]
  random_suit = random.choice(card_suits)
  print(random_suit)

pick_a_card()

def pick_a_card():
  card_ranks = [2,3,4,5,6,7,8,9,10, "J", "Q", "K", "A"]
  random_rank = random.choice(card_ranks)
  print(random_rank)
  print(f"The card is the {random_rank} of {random_suit}")

pick_a_card()
