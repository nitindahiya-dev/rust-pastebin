<h2># 📋 Actix Web Pastebin</h2>

<p>Welcome to the **Actix Web Pastebin** project! This modern and minimalistic web application allows you to create, store, and share text pastes with unique tokens. Built with Rust and Actix Web, it ensures performance and reliability.</p>

<p>## ✨ Features</p>

<li> 📝 **Paste Creation:** Easily submit text content which is stored with a unique token.</li>
<li> 🔍 **Paste Retrieval:** Access stored pastes via a unique URL.</li>
<li> 🎨 **Static File Serving:** Serve static files like CSS for styling.</li>
<br>
<p>## 🛠️ Prerequisites</p>

<li> **Rust:** Make sure you have Rust installed. Get it from [rust-lang.org](https://www.rust-lang.org/).</li>
<li> **SQLite:** This project uses SQLite as the database.</li>
<br>
<p>## 📁 Project Structure</p>

<li> **main.rs:** The main entry point of the application.</li>
<li> **AppState:** Struct to hold the database connection.</li>
<li> **index:** Handler for serving the main page.</li>
<li> **submit:** Handler for submitting new pastes.</li>
<li> **get_paste:** Handler for retrieving pastes by token.</li>
<br>
## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/actix-web-pastebin.git
   cd actix-web-pastebin
   ```

2. **Build the project:**
   ```sh
   cargo build
   ```
3. **run the project:**
   ```sh
   cargo build
   ```
