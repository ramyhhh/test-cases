## **Test Scenario: A Mysterious Castle**

**Description**: You're a 3rd person character exploring an old, haunted castle. As you step on a special stone on the floor, the walls of the castle change color, indicating that a special power has been activated. Suddenly, the control switches to first person and you find a ghost coming towards you. You need to escape the ghost to get out of the castle.

**Tasks**:

1. **Setup**: Using Unreal Engine's 3rd person character template, create a basic level representing the inside of an old castle. This doesn't need to be intricate - a single large room with walls, floor, and ceiling will suffice. Use appropriate material for the walls to give a "castle" feel.

2. **Trigger & Material Change**: Create a special stone tile on the floor (this can be a separate actor with a specific material) which acts as a trigger when the player steps on it. Use a box collision to detect when the player's character enters the stone's area. When the player steps on this stone, dynamically change the material of the castle's walls to a different one (this could be a slightly glowing version of the original wall mat     erial, for example) using Blueprints or C++.

3. **Character Control Switching**: As soon as the material change occurs, switch the game's character control from 3rd person to 1st person. This can be achieved by swapping out the character's camera or altering the camera's perspective and position. Create a transition effect if desired.

4. **Adding the Ghost and Escape Mechanic**: Spawn a ghost character (you can use the default mannequin as the ghost) after the control switches to first person. Make the ghost move towards the player's current position. The player's task is to avoid the ghost and reach the exit door. If the ghost touches the player, the game ends, or you can implement a simple health system, it's up to you.

5. **Optimization and Cleanup**: Ensure that the final submitted project does not include any unused assets. Delete all unnecessary default assets provided by the 3rd person template that were not used in your project, such as unused materials, meshes, blueprints, or scripts. Be careful about dependencies.

**Submission**: Zip your entire Unreal Engine Project and submit it. It should be possible to open the project and hit play in the editor to see everything in action. The game should restart when the player wins or loses.

**Evaluation Criteria**: The task will be evaluated on the basis of how well the candidate has followed the instructions and how well the game mechanics have been implemented. Efficiency of the code/blueprints, use of Unreal's features, and asset management will also be taken into consideration. Extra points for good commenting and code readability. 

**Timeframe**: You have 48 hours to complete and submit this task.

Remember, the aim of this task is not just to test your knowledge of Unreal Engine and C++, but also your creativity and problem-solving skills. Good luck!