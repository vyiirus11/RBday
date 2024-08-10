# ! Happy Birthday !

A lil project for you to mess around with

## Required
1. Github Desktop
2. Pycharm or VS Code(recommended)

## Running Locally
1. Fork the repository by interacting with the 'Fork' button at the top right of the page. This will copy the repository into your account.
2. Once you have forked the repository, go into this forked repository and click on the code button and copy the git url or clone it.
    -  install the pygame package by inputing into your terminal:
    ```
    pip install pygame
    ```
3. Once it's opened in your GitHub desktop, navigate to File>Options>Integrations to open it in VS Code or Pycharm 
    - navigate to the main file:
    ```
    Reese's Bday gift.py
    ```

## Characters
The class "Player" (line 159) allows you to play as any available character

- Character options:
  - Frog
  - Duck

To change your character names, go to line 161 
```
SPRITES = load_sprite_sheets("Characters", "Frog", 32, 32, True)
```
1. Where "Frog" is, you can change to the other available characters
    - make sure to have " " around the name

#
As long you have the pygame package installed successfully, you should now successfully have a running project to interact with.
