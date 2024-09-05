<h1 align="center">MatchMate WebApp</h1>
<h3 align="center">A Modern Dating Web Application</h3>

<p align="center">
    <img src="https://img.shields.io/badge/ASP.NET-%23FF6F61.svg?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Badge" />
    <img src="https://img.shields.io/badge/Angular-%23E23237.svg?style=for-the-badge&logo=angular&logoColor=white" alt="Angular Badge" />
    <img src="https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase Badge" />
</p>

<h2>Project Overview</h2>
<p><strong>MatchMate</strong> is a full-featured dating web application that enables users to create accounts, search for potential matches, and exchange messages in real-time. This project was developed using ASP.NET for the backend, Angular for the frontend, and Firebase for handling live messaging.</p>

<h2>Features</h2>
<ul>
    <li><strong>User Authentication:</strong> Secure user registration and login with account creation.</li>
    <li><strong>Match Search:</strong> Advanced search functionality to find compatible matches based on user preferences.</li>
    <li><strong>Real-Time Messaging:</strong> Live messaging hub implemented using Firebase, enabling real-time chat between users.</li>
    <li><strong>Profile Management:</strong> Users can create, update, and manage their profiles with personal information and photos.</li>
    <li><strong>RESTful API:</strong> The application provides a REST API for seamless client-server communication.</li>
    <li><strong>Responsive Design:</strong> Fully responsive and user-friendly interface built with Angular.</li>
</ul>

<h2>Technology Stack</h2>
<p><strong>Backend:</strong> ASP.NET, C#, Entity Framework Core</p>
<p><strong>Frontend:</strong> Angular</p>
<p><strong>Real-Time Messaging:</strong> Firebase</p>

## 📸 Project Screenshots

### Register User Page
![Matches Page](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/register-user.png)

### Home/Matches Page
![Matches Page](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/matches-page.png)

### Profile Update Page
![Profile Update](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/profile-update.png)

### User Details Page
![User Details Page](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/user-details.png)

### Live message With User
![Message Tab](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/message-tab.png)

### Messages Page
![Active Users](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/messages.png)

### Gender Filter Page
![Filter by Gender](https://github.com/RamaniRavi/MatchMate_WebApp/blob/main/Demo/gender-filter.png)

<h2>Installation and Setup</h2>

<h3>Prerequisites</h3>
<ul>
    <li>.NET Core SDK</li>
    <li>Node.js and npm</li>
    <li>Angular CLI</li>
    <li>SQL Server (or any other supported database)</li>
    <li>Firebase Account</li>
</ul>

<h3>Clone the Repository</h3>
<pre><code>git clone https://github.com/YourUsername/MatchMate-WebApp.git
cd MatchMate-WebApp
</code></pre>

<h3>Backend Setup</h3>
<ol>
    <li>Navigate to the <code>backend</code> directory:
        <pre><code>cd Backend</code></pre>
    </li>
    <li>Restore the dependencies:
        <pre><code>dotnet restore</code></pre>
    </li>
    <li>Update the <code>appsettings.json</code> file with your database connection string.</li>
    <li>Run the migrations to set up the database:
        <pre><code>dotnet ef database update</code></pre>
    </li>
    <li>Start the backend server:
        <pre><code>dotnet run</code></pre>
    </li>
</ol>

<h3>Frontend Setup</h3>
<ol>
    <li>Navigate to the <code>frontend</code> directory:
        <pre><code>cd ../Frontend</code></pre>
    </li>
    <li>Install the dependencies:
        <pre><code>npm install</code></pre>
    </li>
    <li>Update the environment configuration files (<code>environment.ts</code>) with your Firebase configuration.</li>
    <li>Start the Angular development server:
        <pre><code>ng serve</code></pre>
    </li>
</ol>

<h3>Running the Application</h3>
<p>Open your browser and navigate to <a href="http://localhost:4200" target="_blank">http://localhost:4200</a> to access the application.</p>

<h2>Usage</h2>
<ul>
    <li><strong>Home Page:</strong> Browse the available features or log in to your account.</li>
    <li><strong>Account Management:</strong> Register a new account or log in with an existing one.</li>
    <li><strong>Match Search:</strong> Use the search functionality to find potential matches based on your preferences.</li>
    <li><strong>Messaging:</strong> Start a real-time chat with your matches using the live messaging feature.</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Please follow these steps:</p>
<ol>
    <li>Fork the repository.</li>
    <li>Create a new branch (<code>feature/your-feature-name</code>).</li>
    <li>Commit your changes.</li>
    <li>Push the branch to your fork.</li>
    <li>Create a Pull Request.</li>
</ol>
</body>
</html>
