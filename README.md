# AI Quiz Generator 🧠

A powerful and customizable AI-powered quiz generator built with the Gemini-Pro model. This tool allows users to create engaging and dynamic quizzes effortlessly. Backend functionality is powered by Cloudflare Workers, ensuring high performance and scalability.

## 🚀 Features

* **Gemini-Pro Model Integration**: Leverages the advanced Gemini-Pro model for generating quizzes with precision and creativity.
* **Customizable Quizzes**: Users can define topics, difficulty levels, and question types to tailor quizzes to their needs.
* **Seamless Deployment**: Built on Cloudflare Workers, providing a serverless, low-latency backend solution.
* **Scalable and Reliable**: Optimized for high performance and capable of handling large volumes of requests.
* **User-Centric Design**: Intuitive interface for creating and managing quizzes.

## 🛠️ Getting Started

### Step 1: Create Your Cloudflare Worker

1. **Sign Up/Log In to Cloudflare**: Create a free account at [Cloudflare](https://www.cloudflare.com/).
2. **Install Wrangler CLI**: Install the Wrangler CLI to manage your Cloudflare Workers.

   ```bash
   npm install -g wrangler
   ```

3. **Generate a Worker Project**: Use the following command to create your Worker:

   ```bash
   wrangler generate ai-quiz-generator
   cd ai-quiz-generator
   ```

4. **Install Dependencies**: Navigate to the project directory and install dependencies.

   ```bash
   npm install
   ```

5. **Configure the Worker**: Set up the Worker configuration file (`wrangler.toml`) to include your account and project details.

### Step 2: Set Up the Frontend

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/MeetThumar/ai-quiz-generator.git
   cd ai-quiz-generator
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Start the Frontend**:

   ```bash
   npm start
   ```

The frontend will be accessible at `http://localhost:5173`.

### Step 3: Deploy Your Cloudflare Worker

1. **Authenticate Wrangler**:

   ```bash
   wrangler login
   ```

2. **Deploy Your Worker**:

   ```bash
   wrangler publish
   ```

Your Cloudflare Worker will be live and ready to handle backend quiz generation!

## 📋 Usage

1. **Choose Your Preferences**: Select topics, difficulty levels, and question numbers in the site.
2. **Generate Quizzes**: The Gemini-Pro model creates high-quality, topic-specific quiz questions in real-time.
3. **Share and Evaluate**: Distribute quizzes easily and review results with in-built evaluation tools.

## 👤 Author

**Meet Thumar**

An innovative developer pushing the boundaries of AI and cloud-based technologies to deliver cutting-edge solutions.

---

Made with ❤️ by Meet Thumar
