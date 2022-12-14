# Notes For Reference

## --- When You Start The Program, It Will: ---
    1. Welcome the user
    2. Show menu
    3. Ask the user what they want to purchase

## --- Depending On User Input, These Are The Scenarios That Could Occur: ---

#### * FIRST OPTION: User chooses to buy a specific drink:
    1. Ask the user for preferred size & whether they want extra cream or more sugar.
    2. Prints the price of the drink 
    3. Ask them whether they want cash or card
    4. if card --> "Processing order..." immediately
    5. if cash --> Ask what they have on them --> return the least change possible with their money --> "Processing order..."
    6. Finish order and give the user their drink.
    7. Return to initial ask.

#### * SECOND OPTION: User don't know the drink:
    1. Give the user a suggestion, then ask them if they like the drink
    2. if yes --> return FIRST OPTION and start implementing.
    3. if no --> return to step one.

#### * THIRD OPTION: Accessing administrative controls:
    1. Using "mode.admin" (this can be changed in the config) will prompt the user to authenticate.
    2. Two Factor Authentication: initial password + OTP sent through SMS.
    3. All options regarding admin controls can be found in the config file.

#### * FOUR OPTION: EXIT THE CAFE:
    1. Simply exit the application.


## --- What You Can Do In Admin Mode: ---

    1. Ask for a report of remaining resources & refill them if necessary
    2. Add/remove items on menu, or change their prices
    3. Change password/OTP SMS destination (can also be changed directly in config)






