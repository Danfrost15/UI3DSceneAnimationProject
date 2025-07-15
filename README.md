# UI3DSceneAnimationProject
## 🎨 Description
This project features a simple UI and 3D animation setup:
- The Main Menu uses a smooth **fade-out transition** when moving to the game scene.
- The Play Button grows slightly larger when hovered over or tapped, giving visual feedback to the player.

## 🕹️ How to Trigger Animations

### 🔹 PC Controls
- Main Menu:Hover over the Play Button to trigger the scale-up animation.
- Game Scene:Press R to trigger the in-game animation.

### 🔹 Android Controls
- Main Menu:Tap the Play Button to start and play the animation.
- Game Scene:Tap anywhere on the screen to trigger the animation.

## ⚙️ Special Considerations
- Make sure your scene contains an EventSystem, Canvas ,and properly set up Animator Controllers.
- On Android, ensure **touch input** is enabled and properly handled in the scripts.
- Audio or visual delay might vary slightly depending on the device performance—test on target devices where possible.
