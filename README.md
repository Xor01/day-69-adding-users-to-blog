<p align="center">
  <img src="https://img.icons8.com/?size=512&id=55494&format=png" width="20%" alt="BLOG-logo">
</p>
<p align="center">
    <h1 align="center">BLOG</h1>
</p>
<p align="center">
    <em>Empowering creativity, one post at a time.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Xor01/Blog?style=flat&logo=opensourceinitiative&logoColor=white&color=e2192e" alt="license">
	<img src="https://img.shields.io/github/last-commit/Xor01/Blog?style=flat&logo=git&logoColor=white&color=e2192e" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Xor01/Blog?style=flat&color=e2192e" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Xor01/Blog?style=flat&color=e2192e" alt="repo-language-count">
</p>
<p align="center">
		<em>Built with the tools and technologies:</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/Jinja-B41717.svg?style=flat&logo=Jinja&logoColor=white" alt="Jinja">
	<img src="https://img.shields.io/badge/Gunicorn-499848.svg?style=flat&logo=Gunicorn&logoColor=white" alt="Gunicorn">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/Flask-000000.svg?style=flat&logo=Flask&logoColor=white" alt="Flask">
</p>

<br>

#####  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
    - [ Prerequisites](#-prerequisites)
    - [ Installation](#-installation)
    - [ Usage](#-usage)
    - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

The open-source project, Xor01s Blog, is a Flask-based platform offering seamless user interactions, content creation, and authentication. Key functionalities include user registration, login, post creation, commenting, and contact page. Leveraging extensions like Flask-Bootstrap and Flask-CKEditor, it ensures a visually appealing interface and enhanced user experience. Xor01s Blog prioritizes security with features like password hashing and user authentication, fostering a secure environment for users to engage and share content. It stands out for its integration of WTForms for data validation, ensuring smooth data input and submission processes.

---

##  Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | Flask-based web application with various extensions for enhanced functionality such as Flask-Bootstrap, Flask-CKEditor, Flask-SQLAlchemy, Flask-Login, and Flask-Gravatar. Modular components like forms for post creation, user registration, login, and commenting. Secure user authentication and session management.  |
| 🔩 | **Code Quality**  | Clean and well-structured codebase with consistent style. Utilizes Flask best practices and design patterns. Follows PEP8 conventions for Python code. |
| 📄 | **Documentation** | Limited documentation available in the repository. Needs improvement in providing detailed explanations and usage instructions for contributors and users. |
| 🔌 | **Integrations**  | Integrates with various third-party dependencies such as Flask-Gravatar, WTForms, Flask-Bootstrap, Flask-SQLAlchemy, and more. Relies on external libraries for added functionality. |
| 🧩 | **Modularity**    | Modular design with separate components for different functionalities like forms, app initialization, and web processes. Encourages code reusability and maintainability. |
| 🧪 | **Testing**       | No specific information on testing frameworks or tools used. Testing coverage and strategies may need to be enhanced for ensuring code reliability. |
| ⚡️  | **Performance**   | Efficient resource usage with the help of Gunicorn for serving the Flask app. Could benefit from performance optimization techniques like caching for improved speed. |
| 🛡️ | **Security**      | Implements security measures such as password hashing, user authentication, and secure sessions. Follows best practices for data protection and access control. |
| 📦 | **Dependencies**  | Relies on a variety of external libraries and dependencies listed in the 'requirements.txt' file for Flask web application development. |

---

##  Repository Structure

```sh
└── Blog/
    ├── LICENSE
    ├── Procfile
    ├── README.md
    ├── app.py
    ├── forms.py
    ├── requirements.txt
    ├── run.py
    ├── static
    │   ├── css
    │   ├── img
    │   ├── js
    │   ├── scss
    │   └── vendor
    ├── template.env
    └── templates
        ├── about.html
        ├── contact.html
        ├── footer.html
        ├── header.html
        ├── index.html
        ├── login.html
        ├── make-post.html
        ├── post.html
        └── register.html
```

---

##  Modules

<details closed><summary>.</summary>

| File | Summary |
| --- | --- |
| [forms.py](https://github.com/Xor01/Blog/blob/main/forms.py) | Defines form classes for creating blog posts, user registration, login, and posting comments. Integrates WTForms for validation and Flask-CKEditor for content editing. Facilitates data input and submission within the Flask-based Blog repository. |
| [run.py](https://github.com/Xor01/Blog/blob/main/run.py) | Initializes the web application by creating and running the app instance using the `create_app` function from the app module. |
| [app.py](https://github.com/Xor01/Blog/blob/main/app.py) | The `app.py` file in this open-source repository is a crucial component responsible for running a Flask web application for a blogging platform. It leverages various Flask extensions like Flask-Bootstrap, Flask-CKEditor, Flask-SQLAlchemy, Flask-Login, and Flask-Gravatar for enhanced functionality. By utilizing forms for post creation, user registration, login, and commenting, it provides a seamless user experience. The integration of features such as password hashing, user authentication, and user sessions ensures secure interactions on the platform. Overall, this file plays a pivotal role in managing user interactions, content creation, and authentication within the blogging applications architecture. |
| [Procfile](https://github.com/Xor01/Blog/blob/main/Procfile) | Defines web process using Gunicorn to serve Flask app. Facilitates deployment on Heroku by specifying the web server command. Ensures efficient handling of web requests in the Blog application architecture. |
| [requirements.txt](https://github.com/Xor01/Blog/blob/main/requirements.txt) | Manages project dependencies for Flask web app, ensuring proper functionality and performance. Facilitates integration of essential libraries like SQLAlchemy, Flask-Login, and WTForms for seamless application development. |

</details>

<details closed><summary>templates</summary>

| File | Summary |
| --- | --- |
| [register.html](https://github.com/Xor01/Blog/blob/main/templates/register.html) | Displays a user registration interface within the Blog repository. Utilizes Bootstrap styling for a visually appealing form. Integrates Flask-WTF for form handling and messaging. Incorporated within the website structure for seamless user interaction. |
| [footer.html](https://github.com/Xor01/Blog/blob/main/templates/footer.html) | Implements the footer section of the website, providing social media links and copyright information dynamically. Loads essential Bootstrap and custom JavaScript for enhanced user experience and visual appeal. |
| [about.html](https://github.com/Xor01/Blog/blob/main/templates/about.html) | Illustrates a webpage layout featuring a header, content sections, and a footer. Emphasizes an About Me section with a background image. Includes standard elements like headings, paragraphs, and a container structure for consistent design across the website. |
| [post.html](https://github.com/Xor01/Blog/blob/main/templates/post.html) | Renders a detailed post view with an interactive comment section. Displays post title, author, date, and content with edit option. Supports comment submission, live preview, and user gravatar. Maintains a clean layout using included header and footer templates. |
| [login.html](https://github.com/Xor01/Blog/blob/main/templates/login.html) | Renders a login page with a welcoming header and a form for users to log in. Displays messages, validates input, and includes header and footer templates for consistency in the Blog repositorys UI architecture. |
| [make-post.html](https://github.com/Xor01/Blog/blob/main/templates/make-post.html) | Creates a dynamic blog post creation page with CKEditor integration and form submission handling. Renders a visually appealing interface, supporting both new post creation and post editing functionalities. Incorporated within the blogs wider layout architecture. |
| [index.html](https://github.com/Xor01/Blog/blob/main/templates/index.html) | Showcases blog posts with titles, author details, and creation dates. Allows users to view, create, and delete posts. Integrates header and footer templates for consistent styling. Enhances user experience with seamless navigation and post management functionality. |
| [header.html](https://github.com/Xor01/Blog/blob/main/templates/header.html) | Defines the header layout and navigation links for Xor01s Blog, including branding, menu toggling, and dynamic user authentication handling. It imports CSS styles, Bootstrap components, and custom fonts to enhance the blogs visual appeal and user experience. |
| [contact.html](https://github.com/Xor01/Blog/blob/main/templates/contact.html) | The `contact.html` file in the Blog repository serves as the template for the contact page of the blog website. It includes a header section with a background image and contact information. The main content of the page provides a form for users to contact the blog owner or ask questions. The layout is clean and user-friendly, encouraging engagement with visitors.This file contributes to the overall user experience of the blog site by providing a visually appealing and informative contact page that aligns with the design consistency of other template files in the repository. |

</details>

---

##  Getting Started

###  Prerequisites

**Python**: `version +3.7`

###  Installation

Build the project from source:

1. Clone the Blog repository:
```sh
❯ git clone https://github.com/Xor01/Blog
```

2. Navigate to the project directory:
```sh
❯ cd Blog
```

3. Install the required dependencies:
```sh
❯ ❯ pip install -r requirements.txt
```

###  Usage

To run the project, execute the following command:

```sh
❯ ❯ python run.py
```

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/Xor01/Blog/issues)**: Submit bugs found or log feature requests for the `Blog` project.
- **[Submit Pull Requests](https://github.com/Xor01/Blog/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Xor01/Blog/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/Xor01/Blog
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/Xor01/Blog/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=Xor01/Blog">
   </a>
</p>
</details>

---

##  License

This project is protected under the GNU General Public License v3.0 License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/gpl-3.0/) file.

---



![image](https://github.com/Xor01/Blog/assets/111096981/4d0a1366-2be3-4bdc-b760-f39d798d752b)
#
![image](https://github.com/Xor01/Blog/assets/111096981/c2eb4ca9-1b0d-44ea-9e05-3c7bbea410f2)
