# ICS3U_TextAdventure
Your job is to use the power of if statements to make a mini text-based adventure game.

This is one of my favourite ones: [Dreamhold](https://eblong.com/zarf/zweb/dreamhold/)
Now this is WAY more complex then what I'm expecting of you.

Your game should include some story and three choices that the user has to make, and different stories depending on the choices the user makes.
Get creative! Get funny! Make me laugh, or cry. Help me enjoy marking these as much as your adlibs :)

Note, if the user can make three choices, then the minimum number of ending senarios should be 8:


                                              *
                                             / \
                                            /   \   
                                           /     \   
                                          /       \             Choice 1
                                         /         \
                                        /           \
                                       *             *
                                      / \           / \
                                     /   \         /   \        Choice 2
                                    /     \       /     \
                                   *       *     *       *
                                  / \     / \   / \     / \     Choice 3
                                 *   *   *   * *   *   *   *


Here is a super small example of what I'm looking for (with one choice)

```
print("Welcome to Narnia.")
ans = input("Would you like to leave this place or go exploring?")
# Making everything lower case helps with input checking.
ans = ans.lower()

if ans == "leave" or ans == "leave this place":
  print("You feel a blow to your head as you get knocked out my an unknown force... everything goes black. You wake up in your bed")
  
  ans = input("Would you like to get up or keep lying down")
  ans = ans2.lower()
  if ans == "get up" or ans == "gu":
    print("Getting up... oh look! A toy")
    # ...
  else:
    pass
    # ...
else:
  print("You walk into the icy tundra and you see a lamppost with a flickering light. To your right you can hear footsteps coming your way")
  ans = input("Run away? (type yes or no)")
  if ans == "yes":
    pass
    # ...
  else:
    pass
    # ...
    
print("The end")
```






