
# GitHub User Finder Project in React

## Introduction

The "GitHub User Finder" project is a web application built using React, a popular JavaScript library for building user interfaces. The main purpose of this project is to allow users to search for GitHub users and view their profiles. The app uses the GitHub API to fetch user data and displays relevant information about the searched users.



# Project Name : GitHub User Finder App ![Tech Stack Used](https://img.shields.io/badge/Technologies-ReactJS-magenta)

---

## Project Screenshot

>![image](https://github.com/DeeptiDaisy/githubuser-finder/assets/109961309/72e5256f-e4e8-41ae-8d7f-ff0d875bf623)


> ![image](https://github.com/DeeptiDaisy/githubuser-finder/assets/109961309/8b66a61c-8790-43d0-bc69-eff0c9934a08)


---

## You can Check it Live on Below Link :

> [![Live Link](https://img.shields.io/badge/DEPLOYED-LINK-green)](https://deeptisgithubuserfinderapp.netlify.app/)


---
 
## Features

1. **Search Bar:**
   - The app provides a search bar where users can enter the GitHub username they want to find.
   - When the user submits the search query, the app triggers the search for the entered username.

2. **User Profile Display:**
   - After the user submits the search query, the app fetches data from the GitHub API and displays the profile information of the searched user.
   - The user's profile may include details such as their avatar, username, bio, location, number of followers, repositories, etc.

3. **Error Handling:**
   - If the entered username does not exist or there is an error in fetching data from the GitHub API, the app should display an error message to inform the user.

4. **Loading State:**
   - While the data is being fetched, the app should show a loading state to indicate that it is still retrieving the user data.

## Components

1. **SearchBar Component:**
   - This component renders the search bar where users can input the GitHub username they want to find.
   - It captures user input and triggers the search when the form is submitted.

2. **UserProfile Component:**
   - This component displays the user's profile information once the data is fetched from the GitHub API.
   - It receives the user data as props and renders the relevant information.

3. **UserNotFound Component:**
   - If the entered username does not exist on GitHub, this component is rendered to show an error message indicating that the user was not found.

4. **LoadingSpinner Component:**
   - While the data is being fetched from the GitHub API, this component is displayed to show a loading animation to the user.

## API Integration

The GitHub User Finder app integrates with the GitHub API to fetch user data. When a user enters a GitHub username and submits the search, the app sends a request to the GitHub API and receives the user's profile information in response.

## Routing (Optional)

For better user experience and navigation, we can use React Router to implement routing. This allows users to directly visit a specific user's profile page using a unique URL, rather than relying solely on search.

## Styling

You can use CSS or a CSS preprocessor like SCSS to style the application and make it visually appealing. Consider using GitHub's official color scheme and design guidelines to maintain a consistent look and feel with the GitHub brand.

## State Management

In this simple project, we can manage the app's state using React's built-in `useState` hook. State will be used to store the search query, loading status, fetched user data, and error messages.

## Conclusion

The "GitHub User Finder" project in React is an excellent exercise to learn about React components, API integration, state management, and conditional rendering. It provides a real-world scenario of building an application that interacts with a public API to fetch and display user data. By working on this project, I have improved my React skills and created a practical tool for finding and viewing GitHub user profiles.

---

 
