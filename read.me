import random

# Draws a card from the deck including face cards and Ace
def draw_card():
    cards = ['2', '3', '4', '5', '6', '7', '8', '9', '10', 'J', 'Q', 'K', 'A']
    return random.choice(cards)

# Calculates total hand value, treating Ace as 11 or 1
def calculate_total(cards):
    total = 0
    aces = 0

    for card in cards:
        if card in ['J', 'Q', 'K']:
            total += 10
        elif card == 'A':
            total += 11
            aces += 1
        else:
            total += int(card)

    # Adjust for aces if total is over 21
    while total > 21 and aces > 0:
        total -= 10
        aces -= 1

    return total

# Prompts for 'y' or 'n'
def ask_yes_no(prompt):
    while True:
        response = input(prompt).strip().lower()
        if response in ['y', 'n']:
            return response
        print("\nInvalid input. Please enter 'y' or 'n'.\n")

# Prompts for 'h' (hit) or 's' (stand)
def ask_hit_or_stand():
    while True:
        response = input("Hit or stand? (h/s): ").strip().lower()
        if response in ['h', 's']:
            return response
        print("\nInvalid input. Please enter 'h' to hit or 's' to stand.\n")

# Main game logic
def play_blackjack():
    print("\nWelcome to Blackjack.")
    print("------------------------------------------------------------------")

    while True:
        start = ask_yes_no("\nDo you wish to start a new game? (y/n): ")
        if start == 'n':
            print("\nOk, Goodbye!\n")
            break

        # Deal initial cards
        player_cards = [draw_card(), draw_card()]
        dealer_cards = [draw_card(), draw_card()]
        player_total = calculate_total(player_cards)

        print(f"\nYou draw a {player_cards[0]} and a {player_cards[1]}. Your total is {player_total}.\n")
        print(f"The dealer draws a {dealer_cards[0]} and a hidden card.\n")

        # Player's turn
        while player_total < 21:
            choice = ask_hit_or_stand()
            print()
            if choice == 's':
                print("You stand.\n")
                break
            new_card = draw_card()
            player_cards.append(new_card)
            player_total = calculate_total(player_cards)
            print(f"Hit! You draw a {new_card}. Your total is {player_total}.\n")
            if player_total > 21:
                print("You bust!\n")
                print("Dealer wins!\n")
                break
            elif player_total == 21:
                print("You reached 21. You stand.\n")
                break

        # Dealer's turn
        if player_total <= 21:
            dealer_total = calculate_total(dealer_cards)
            print(f"The dealer reveals the hidden card of {dealer_cards[1]} and has a total of {dealer_total}.\n")

            while dealer_total <= 16:
                new_card = draw_card()
                dealer_cards.append(new_card)
                dealer_total = calculate_total(dealer_cards)
                print(f"Hit! The dealer draws {new_card}. The dealer's total is {dealer_total}.\n")

            if dealer_total > 21:
                print("The dealer busts!")
                print("You win!\n")
            else:
                print("The dealer stands.\n")
                print(f"You have a total of {player_total} and the dealer has {dealer_total}.\n")
                if dealer_total >= player_total:
                    print("Dealer wins!\n")
                else:
                    print("You win!\n")

        print("------------------------------------------------------------------")

# Program entry
if __name__ == "__main__":
    play_blackjack()
















