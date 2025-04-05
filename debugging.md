The goal of the game is to deliver soups as fast as possible. Each soup requires placing up to 3 ingredients in a pot, waiting for the soup to cook, and then having an agent pick up the soup and delivering it. The agents should split up tasks on the fly and coordinate effectively in order to achieve high reward


installation: use python 3.10

# Adding a new feature (such as cutting board)

1) Use texture packer to generate a .json file to overcooked_ai_py/data/graphics
    - for each object, it looks different at different parts of the game depending on interaction, so frames {} contains paths to each of these diff pics (eg - a cut tomato vs a whole tomato)
2) Modify code in _render_objects in state_visualization.py to add logic to render new object

