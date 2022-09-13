# LogitechSteerInputManager
This is a easy way to get inputs from a logitech steering wheel in unity.

Setup:

  -Download and unzip the repo

  -Import the folder into unity
  
  -Call WheelInputManager.Tick() in the update method
  
  -U can now get acces to different inputs from your wheel and paddles;
    Right Paddle: WheelInputManager.throtle
    Middle Paddle: WheelInputManager.brake
    Left Paddle: WheelInputManager.clutch
    
    Gear:
      Min Gear: WheelInputManager.minGear
      Max Gear: WheelInputManager.maxGear
      Current Gear: WheelInputManager.currentGear
  
