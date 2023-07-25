## **Test Scenario: The Magic Forest**

**Description**: You start as a 3rd person character, a curious explorer who wanders into a magic forest. There are 3 monoliths in the forest, each tied to a specific element - Fire, Water, and Earth. When the player interacts with a monolith, the character and the environment around the monolith dynamically change to reflect the element. The character control switches to first person to allow a closer examination of the changed environment. 

**Tasks**:

1. **Setup**: Use Unreal Engine's 3rd person character template and create a forest level with trees and 3 distinct monoliths placed throughout the forest. The forest doesn't need to be extensive - a small clearing with the 3 monoliths is sufficient. Use different materials for the monoliths to distinguish them.

2. **Interaction, Triggers & Material Change**: Each monolith should have a trigger area around it, when the player enters this area, they should be able to interact with the monolith (you could use an on-screen prompt to signal that interaction is possible). Upon interaction, the monolith should change the material of the player character and the immediate environment (trees, ground etc.) to reflect the corresponding element. 

   For example, the Fire monolith could change the character to look charred and the trees to appear burnt. The Water monolith could give the character and the environment a wet, shimmering look. The Earth monolith could change the character and the environment to have a mossy, green texture. You can use the particle system in Unreal Engine to enhance these effects.

3. **Character Control Switching**: After each transformation, switch the control from 3rd person to 1st person. This should allow the player to look at their character's body (now in the first person view) and the immediate environment to appreciate the changes in the material up close.

4. **Return Mechanic**: Allow the character to return to their normal form by interacting with the monolith again. The character control should switch back to 3rd person after this interaction.

5. **Optimization and Cleanup**: As with the previous task, ensure that no unused assets are present in the final submitted project. Remove all superfluous default assets from the template that were not used in your task.

**Submission**: Package your Unreal Engine Project and submit it. The packaged project should run smoothly, presenting the character in a 3rd person perspective with the ability to interact with each monolith and trigger the environmental changes.

**Evaluation Criteria**: This task will be evaluated on how effectively the candidate has implemented the given requirements, the efficiency of the code/blueprints, the effective use of Unreal's features, and asset management. Good commenting and code readability will also be taken into account.

**Timeframe**: You have 48 hours to complete and submit this task.

Remember, the goal is not only to test your Unreal Engine and C++ skills, but also your creativity and problem-solving abilities. Good luck!