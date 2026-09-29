# GitHub-Explorer

GitHub Explorer is a simple web application that allows users to search for GitHub users and view their profile information and repositories using the **GitHub REST API**.

## 🚀 Features

* 🔎 Search GitHub users by username
* 👤 Display GitHub profile information
* 📦 View the user's repositories
* ⭐ Display repository stars
* 🍴 Display repository forks
* 💻 Display programming languages
* 🔗 Open GitHub profiles and repositories directly
* ⚠️ Handle invalid or empty usernames
* 📱 Responsive and user-friendly interface

## 🛠️ Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and responsive design
* **JavaScript (ES6+)** – Application logic and API integration
* **GitHub REST API** – Fetching GitHub user and repository data
* **Fetch API** – Making HTTP requests

## 📂 Project Structure

```text
GitHub-Explorer/
│
├── index.html      # Application structure
├── styles.css      # Application styling
├── script.js       # JavaScript logic and API calls
└── README.md       # Project documentation
```

## 🔗 GitHub API

This project uses the GitHub REST API to retrieve user information.

For example:

```text
https://api.github.com/users/{username}
```

The application sends a username to the API and uses the returned JSON data to display the user's GitHub profile.

## ⚙️ How It Works

1. Enter a GitHub username in the search box.
2. The application sends a request to the GitHub API.
3. The API returns the user's profile information.
4. The application displays the profile.
5. Repository information can then be displayed using the user's repository data.
6. Invalid usernames are handled with an appropriate error message.

### Example

Searching for:

```text
octocat
```

will request:

```text
https://api.github.com/users/octocat
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Sagar-Kumar3099/GitHub-Explorer.git
```

### 2. Open the project

```bash
cd GitHub-Explorer
```

### 3. Run the project

Since this is a frontend project, you can open `index.html` using a local development server.

For example, using VS Code:

```text
Right click index.html
        ↓
Open with Live Server
```

Then open the URL provided by Live Server in your browser.

## 📸 Project Preview

The application provides a simple interface where users can enter a GitHub username and retrieve information from the GitHub API.

## ⚠️ API Rate Limits

GitHub applies rate limits to API requests. Unauthenticated requests have a lower rate limit than authenticated requests.

For learning and small-scale usage, the public API is generally sufficient.

## 📚 What I Learned

Through this project, I practiced:

* Working with REST APIs
* Using `fetch()`
* Understanding `async/await`
* Handling API responses
* Working with JSON data
* DOM manipulation
* Handling errors
* Working with user input
* Rendering dynamic content
* Using Git and GitHub
* Creating branches and Pull Requests

## 🔮 Future Improvements

Possible improvements include:

* Repository pagination
* Search suggestions
* Repository filtering and sorting
* GitHub followers/following information
* Repository language statistics
* Better loading states
* Dark/light theme
* GitHub API authentication

## 👨‍💻 Author

**Sagar Kumar**

GitHub: [Sagar-Kumar3099](https://github.com/Sagar-Kumar3099)

---

⭐ If you find this project useful, feel free to explore the repository and give it a star.
