<h1>CodeVerse</h1>

<h2>Overview</h2>
<p>CodeVerse is a dynamic platform designed to revolutionize collaborative coding by offering a seamless, real-time environment for developers to create, edit, and share code. It tackles the challenges of team-based programming by providing a robust set of tools for real-time collaboration, code execution, and AI-powered assistance. With support for multiple programming languages and a user-friendly interface, CodeVerse is perfect for both solo coders and teams working on complex projects.</p>

<h2>Features</h2>
<ul>
  <li><strong>Real-Time Collaboration:</strong> Edit code across multiple files simultaneously with instant synchronization.</li>
  <li><strong>File Management:</strong> Create, open, edit, save, delete, and organize files and folders within the platform.</li>
  <li><strong>Codebase Download:</strong> Export the entire codebase as a zip file for easy sharing and backups.</li>
  <li><strong>Unique Room Generation:</strong> Generate unique room IDs for secure, collaborative coding sessions.</li>
  <li><strong>Comprehensive Language Support:</strong> Supports a wide range of programming languages with auto-detection.</li>
  <li><strong>Syntax Highlighting:</strong> Dynamic syntax highlighting for various file types with automatic language detection.</li>
  <li><strong>Code Execution:</strong> Execute code directly within the collaboration environment for instant results.</li>
  <li><strong>Instant Updates:</strong> Real-time synchronization of code changes across all files and folders.</li>
  <li><strong>User Notifications:</strong> Receive alerts for user join and leave events during collaborative sessions.</li>
  <li><strong>User Presence List:</strong> View online/offline status indicators for all participants in the room.</li>
  <li><strong>Group Chat:</strong> Real-time chat functionality for team communication during coding sessions.</li>
  <li><strong>Editing Tooltip:</strong> Displays real-time tooltips showing users currently editing specific sections.</li>
  <li><strong>Auto Suggestions:</strong> Language-specific code suggestions to enhance productivity.</li>
  <li><strong>Customizable Interface:</strong> Adjust font size, font family, and choose from multiple themes for a personalized experience.</li>
  <li><strong>Collaborative Drawing:</strong> Sketch and draw collaboratively in real-time to visualize ideas.</li>
  <li><strong>Copilot AI:</strong> AI-powered assistant for generating, inserting, copying, or replacing code seamlessly.</li>
  <li><strong>Live Preview:</strong> View real-time previews of your project as you code.</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li>React</li>
  <li>TypeScript</li>
  <li>React Router</li>
  <li>Tailwind CSS</li>
  <li>Node.js</li>
  <li>Express.js</li>
  <li>Socket.io</li>
  <li>Git</li>
  <li>GitHub</li>
  <li>Vercel</li>
  <li>Docker</li>
</ul>

<h2>Installation</h2>
<p><strong>Method 1: Manual Installation</strong></p>
<p>Fork this repository: Click the Fork button located in the top-right corner of the GitHub page.</p>
<p>Clone the repository:</p>
<pre><code>git clone https://github.com/&lt;your-username&gt;/CodeVerse.git</code></pre>
<p>Create .env files:</p>
<p>Inside the <code>client</code> and <code>server</code> directories, create .env files and set:</p>
<p><strong>Frontend:</strong></p>
<pre><code>VITE_BACKEND_URL=&lt;your_server_url&gt;</code></pre>
<p><strong>Backend:</strong></p>
<pre><code>PORT=3000</code></pre>
<p>Install dependencies:</p>
<pre><code>npm install     # Run in both client and server directories</code></pre>
<p>Start the servers:</p>
<p><strong>Frontend:</strong></p>
<pre><code>cd client
npm run dev</code></pre>
<p><strong>Backend:</strong></p>
<pre><code>cd server
npm run dev</code></pre>
<p>Access the application:</p>
<p>Visit <a href="http://localhost:5173">http://localhost:5173</a> to access the CodeVerse platform.</p>

<h2>Usage</h2>
<p>After starting the frontend and backend servers, navigate to <a href="http://localhost:5173">http://localhost:5173</a> to start using CodeVerse. Create or join a room using a unique room ID to collaborate with others in real-time.</p>

<h2>Future Improvements</h2>
<ul>
  <li>Add support for additional programming languages and frameworks.</li>
  <li>Enhance Copilot AI with advanced code refactoring and debugging capabilities.</li>
  <li>Integrate version control directly within the platform for seamless project management.</li>
</ul>

<h2>Contributing</h2>
<p>If you want to contribute to this project, feel free to open issues or submit pull requests. Make sure to follow the contribution guidelines.</p>
