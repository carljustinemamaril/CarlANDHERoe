README.txt
===========



Classmates RPG Battle Simulator



members: Justine Saplan
	 Grecee Mae Soriano
	 Prince Jude Pitinez


-------------------------
👥 Character Descriptions
-------------------------
1. Justine_Fighter  
   A strong and fearless frontline warrior who specializes in melee combat. Justine deals consistent damage and has higher health, making him ideal for long battles.

2. Grecee_Marksman  
   A quick and agile ranged attacker. Grecee excels at dealing high damage from a distance but has lower health compared to others.

3. Prins_Assassin  
   A stealthy and deadly assassin. Prins deals burst damage and has a chance to critically strike, but sacrifices defense for offense.

-------------------------
🧠 OOP Concepts Applied
-------------------------

✅ Encapsulation  
- Each character’s health, damage, and actions are managed within their own class using methods like `Attack()` and `TakeDamage()`, hiding the internal logic from the main form.

✅ Inheritance  
- All character classes (e.g., `Justine_Fighter`, `Grecee_Marksman`, `Prins_Assassin`) inherit from a common base class `Character`, sharing core functionality while allowing customization.

✅ Polymorphism  
- The simulator uses the base `Character` type to handle all players, allowing different character subclasses to override the `Attack()` method and behave differently during battle.

✅ Abstraction  
- The form interacts with characters through simple method calls (`Attack`, `TakeDamage`) without needing to know their internal implementation details.

✅ Exception Handling  
- We use try-catch blocks to handle invalid inputs, missing images, and runtime errors, ensuring the program runs smoothly even when something goes wrong.

-------------------------
🚧 Challenges Faced
-------------------------

- Image Loading: Initially, only one character image was showing. The issue turned out to be incorrect file names or path mismatches.

- Polymorphism Issues: Making sure that the correct version of the `Attack()` method ran based on the selected character subclass required careful setup.

- Event Handling: Properly updating the character images and stats when a different character is selected in the dropdown took some debugging.

- File Management: Ensuring all image files were in the correct folder (`Images/`) with exact file names matching character class names (case-sensitive).

--------------------------------


