
# GitHub User Avatar Finder Web App

## Objective

Develop a web application using React that allows users to input a GitHub username. Upon user input, the app should display the avatar of the user fetched from the GitHub API. The app should incorporate debouncing to enhance user experience and prevent excessive API calls.

## User Interface (UI)

Create a simple and user-friendly UI with a text input box and an image container. The user should be able to type in a GitHub username in the input box.

## GitHub API Integration

Utilize the GitHub API to fetch user information, specifically the user's avatar image. Handle API requests and responses effectively.

## Avatar Display

Upon successful API response, display the user's avatar image in the designated container.

## Debouncing

Implement debouncing to improve performance and prevent excessive API calls while the user is typing in the input box. Create a custom hook named useDebounce to manage the debouncing functionality.

### Custom Debounce Hook (useDebounce)

The useDebounce hook should take an input value and a delay time as arguments. Implement the debounce logic within the hook using setTimeout. Return the debounced value after the specified delay has passed.

## Project Setup

1. Clone the repository:

```bash
   git clone https://github.com/pratikgondkar/GitHub-User-Avatar-Finder-.git

```

2. Navigate to the project directory:

```bash
cd Finder
```

3. Install dependencies:

```bash
npm install

```

4. Run the development server:

```bash
npm run dev


```

Open your browser and visit http://localhost:5173/ to view the app.

![Screenshot 2024-04-16 202211](https://github.com/pratikgondkar/GitHub-User-Avatar-Finder-/assets/131374322/505e3fee-3d55-4b81-813e-639b6c927d04)


![Screenshot 2024-04-16 202841](https://github.com/pratikgondkar/GitHub-User-Avatar-Finder-/assets/131374322/b4df1caa-13b8-4e45-8321-127e12c36d5c)


