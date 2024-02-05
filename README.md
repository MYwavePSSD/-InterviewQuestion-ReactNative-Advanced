## MYWave Senior Mobile Developer Inteview Question
In this interview, you will be tasked with developing a React Native application using Expo. The project involves integrating the [PokéAPI](https://pokeapi.co/) to fetch and display Pokémon data. The candidate is expected to implement state management using Redux and handle asynchronous actions with Redux Thunk. Additional functionalities include search and sort features. The candidate will need to optimize performance, handle errors gracefully, and write unit tests. Finally, they are required to push the project to a GitHub repository, providing comprehensive instructions in the README. This question assesses the candidate's proficiency in React Native, state management, API integration, and overall application development skills.

### Expo Project Setup:
1. Initialize a new Expo project using `expo init PokeAPIApp`.
2. Choose the "blank" template or any template that suits your needs.
3. Set up the basic project structure and ensure it runs successfully using `expo start`.

### Install Dependencies:
4. Install necessary dependencies such as `axios` for making API requests, `react-redux` for state management, `redux-thunk` for handling asynchronous actions, and any additional packages for search and sort functionality.

### PokéAPI Integration:
5. Create a service file to handle PokéAPI requests using Axios.
6. Implement functions to fetch Pokémon data from the PokéAPI.
7. Test the API calls and handle loading, success, and error states.

### Redux Setup:
8. Install Redux and set up the Redux store, actions, and reducers.
9. Define actions for fetching Pokémon data and update the Redux store accordingly.
10. Integrate Redux with the Expo React Native application.

### Redux Thunk for Async Actions:
11. Install `redux-thunk` middleware to handle asynchronous actions.
12. Implement Redux thunk for making asynchronous API calls to PokéAPI.

### Search Functionality:
13. Implement a search bar component that allows users to search for specific Pokémon by name or other relevant criteria.
14. Connect the search functionality to the Redux store to filter and display the matching Pokémon.

### Sort Functionality:
15. Implement sorting options (e.g., by name, type, or ID) for the list of Pokémon.
16. Allow users to toggle between ascending and descending order.
17. Update the Redux store accordingly to reflect the sorted order.

### Component Integration:
18. Update existing or create new React Native components to display Pokémon data.
19. Integrate the search and sort functionality into the components.

### Error Handling:
20. Enhance error handling for API calls, search, and sort actions.
21. Ensure the UI responds appropriately to loading, success, and error states.

### Optimizing Performance:
22. Optimize performance by memoizing components, using PureComponent, and implementing shouldComponentUpdate where necessary.
23. Consider using FlatList for efficient rendering of lists.

### Testing:
24. Write unit tests for Redux actions, reducers, and components, including tests for search and sort functionality.
25. Ensure that the tests cover different scenarios, including success, error, and various search/sort criteria.

### GitHub Repository:
26. Create a new GitHub repository for the Expo project.
27. Initialize a git repository locally and connect it to the GitHub repository.
28. Commit the initial project files and subsequent changes.
29. Push the code to the GitHub repository. Please ensure your repository is not private and share back the repository to [pssd_management@mywave.biz](mailto:pssd_management@mywave.biz)

Make sure to update the README with instructions on how to use the search and sort features and any additional information related to these functionalities.
