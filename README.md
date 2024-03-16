###CHANGELOG


#29/02/2024 - Week 5: Basic skeleton [Complete]
- Created new project
- Created mainActivity with provided code
- Created java class with provided code
- Deleted activity_main xml file
- Successfully ran project to see blue screen with score and life counter
- spaceGameView.java became display code
-  Added comments to explain barebones code


#03/03/2024 - Week 6: Images and directions [Complete]
- Notes:
  - What needs to be included in the spaceShip class
    - Spaceship images for each direction
    - Value required for each direction 
      - 1. Left, 2. Right, 3. Up, 4. Down
    - Set a variable to signify current direction
      - Current direction = left; OR
      - Current direction ) 1;
    - Need to know height and width of image
    - Need to know x, y coords of top left of the image
    - Need to know ship speed
      - Relative to other game objs and speed of movement
      - Must be calculated based on the speed the device will render the obj
      - Movement of objects based on device fps
- Added images
- Added getter and setter for bitmap background (faff!)
- Ran app successfully


#7/03/2024 - Week 7: Movement [Complete]
- Added skeleton code provided for movement
- Updated directional controls as they were a little off and made movement difficult and buggy
- Fixed an issue wherein the spaceship would get stuck at exactly (0.5x, 0.5y) due to an issue with the movement


#16/03/2024 - Week 8: Bullets [Complete]
- Added the skeleton code provided for bullet class
- Found better images for using in the game
    - Added new background
    - Updated friendly spaceship
    - Added images for enemy spaceship and bullet image
    - Also added an image for multiple firings, not sure how to implement this though
        - Should I fire three individual bullets?
        - Or should the ship fire the one bullet with the multiple fire image but with triple damage?
