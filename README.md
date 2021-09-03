# character_sheet_creator

## Background
    This application is a resource for Dungeons and Dragons Fifth Edition. D&D character creation is oftentimes one of the most overwhelming experiences for first time players. 
    There are so many options and possibilities to explore due to the fantasy nature and large world of DnD. This application will streamline the character creation process by providing the user with digestable amounts of information in a step by step process. 
    After creation, a modifiable character sheet will be generated for the new players for use as a reference on their first Dungeons and Dragons adventure!
 
 ## Functionality and MVPS
 With this application users will be able to:
  - Create a character through a guided process.
  - Generate a character sheet.
  - Add abilities and equipment to their characters.
  - Roll dice with proper modifiers and bonuses.

In addition, this application will include:
  - A character sheet that reacts to user edits and modifies itself.
  - A character sheet with clickable elements that returns information to the user.
  - A search feature for common equipment and spells.
  - A production README.

## Wireframes
![image](https://user-images.githubusercontent.com/86497399/131964592-d2ed364f-a1c5-4e82-a039-be7eab69ab24.png)
- Nav links will contain links to my Github, LinkedIn, and other DnD resources for first time players.
- Character sheet will be generated and interactable.
- Info box will display information requested from character sheet along with rolls generated from inputs through text.
- The character creation form will display options and a description will be displayed on the right based on the currently selected option.

## Technologies, Libraries, APIs
The application will be built using: 
  - npm to manage project dependencies.
  - [The D&D 5th edition API](http://www.dnd5eapi.co/)
  - 3JS for dice models.

## Implementation Timeline
  - Friday and weekend: Set up project, including webpack and postman to get comfortable with D&D 5E API. Make character creation form. Render multiple forms that create each other. Access the API to get information regarding selected character creation options. Create Character class that will take form info. 
  - Monday: Create a CharacterSheet class that extrapolates info from Character object. Use the CharacterSheet class to generate HTML elements for a character sheet object to be rendered. Create a search feature that utilizes D&D 5E API for equipment and spells. Results can be added to the character sheet.
  - Tuesday: Make an information display box. Make each character sheet element clickable and return a description to the display box. Refactor this to be used in character creation form. Create a dice roller that displays results in the info box.
  - Wednesday: Focus on styling.
  - Thursday: Deploy to GitHub pages