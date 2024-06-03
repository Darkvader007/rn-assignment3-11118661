# rn-assignment3-11118661
Sure, here’s a brief description of each component's usage within the provided `App.js` file:

### App.js
This is the main file that sets up the entire application layout, integrates various custom components, and includes all necessary styles and functionalities.

1. **Imports**
    - `React`: Import the React library to use its functionalities.
    - `View`, `Text`, `TextInput`, `StyleSheet`, `ScrollView`, `Image`, `FlatList`: Import these core components from `react-native` to construct the UI.

2. **Data Arrays**
    - `categories`: An array of category objects, each containing a name, task count, and icon URL.
    - `tasks`: An array of task descriptions.

3. **TaskCategories Component**
    - Purpose: Renders the list of task categories.
    - Structure: Uses a `View` to contain the category title and a set of category items.
    - Subcomponents:
        - `Image`: Displays the category icon.
        - `Text`: Shows the category name and task count.

4. **TaskList Component**
    - Purpose: Renders the list of ongoing tasks.
    - Structure: Uses a `View` to contain the task list title and a `FlatList` to render each task.
    - Subcomponents:
        - `Text`: Displays each task name in the list.

5. **App Component**
    - Purpose: The main component that combines all other components to create the complete UI.
    - Structure:
        - `ScrollView`: Allows the entire content to be scrollable.
        - `View`: Contains the header section with greeting text, task count, and avatar.
        - `TextInput`: Provides a search bar for user input.
        - `TaskCategories` and `TaskList`: Integrates the custom components for categories and tasks.

6. **Styles**
    - Defined using `StyleSheet.create` to organize the styling of the application.
    - `container`: Sets the main container style with padding and background color.
    - `header`: Styles the header section to align items horizontally.
    - `headerText`: Sets the style for the main greeting text.
    - `subHeaderText`: Styles the sub-header text showing the task count.
    - `avatar`: Styles the avatar image.
    - `searchBar`: Styles the search input field.
    - `categoriesContainer`: Styles the container holding the categories.
    - `categoriesTitle`: Styles the title for the categories section.
    - `categories`: Styles the container holding individual category items.
    - `category`: Styles each category item box.
    - `categoryIcon`: Styles the icon within each category item.
    - `categoryText`: Styles the text showing the category name.
    - `categoryTasks`: Styles the text showing the number of tasks in each category.
    - `tasksContainer`: Styles the container holding the task list.
    - `tasksTitle`: Styles the title for the task list section.
    - `task`: Styles each task item box.

By organizing the code in this manner, the application is modular, making it easier to manage and understand. Each component has a clear purpose and is styled appropriately to match the provided UI mockup.