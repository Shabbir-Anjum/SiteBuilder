# SiteBuilder - Your Ultimate Web Development Companion 🚀

**SiteBuilder** is a powerful web application built for web developers, especially those who frequently participate in hackathons. It leverages AI to generate and display code snippets instantly using the Together AI LLaMA API and HELICONE API. The application also includes a sandbox feature that allows users to easily transfer code into a live editor, saving valuable time during development.

## Why SiteBuilder? 🦸‍♂️

As a developer who has participated in numerous hackathons, I’ve experienced firsthand how challenging and time-consuming it can be to set up components from scratch. The pressure to deliver high-quality code within tight deadlines can be overwhelming. **SiteBuilder** was born out of this need to streamline the coding process, allowing developers to focus more on building and less on setup.

By integrating LLaMA's code generation capabilities and providing a seamless transition to a live sandbox environment, I feel like I’m doing my job like Superman—empowering developers to move fast and break limits.

## Features ✨

- **AI-Powered Code Generation**: Uses Together AI's LLaMA model via HELICONE API to generate code based on user input.
- **Instant Preview & Sandbox Integration**: With a click of a button, shift the generated code into a sandbox environment for live editing, testing, and further development.
- **Time-Saving Development**: Say goodbye to repetitive component setup and hello to more efficient project development.
- **Tailored for Hackathons**: Perfectly suited for fast-paced environments like hackathons, where every second counts.

## Tech Stack 💻

- **Frontend**: Next.js, Tailwind CSS for UI components
- **Backend**: Together AI API (Llama), HELICONE API for code generation and display
- **Integration**: Sandpack for live coding environment

## How It Works ⚙️

1. **Generate Code**: Enter your desired code prompt into the input field, and let the power of AI do the heavy lifting.
2. **Display Output**: The generated code is displayed instantly for your review and use.
3. **Send to Sandbox**: Click the "Sandbox" button to transfer the generated code to a live editor. This enables you to further edit, test, and refine your code in real-time—saving you hours of setup.
4. **Share Your Code**: When you're ready, share your app directly from the editor to your desired platform.

## Installation & Setup 🛠️

To get started with **SiteBuilder** locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Shabbir-Anjum/SiteBuilder.git
    cd sitebuilder
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Set up environment variables:
   - `TOGETHER_API_KEY`: Your Together AI API key.
   - `HELICONE_API_KEY`: Your Helicone API key.

   Create a `.env` file in the root directory and add your API keys:
    ```env
    TOGETHER_API_KEY=your-together-api-key
    HELICONE_API_KEY=your-helicone-api-key
    ```
4. Run the application:
    ```bash
    npm run dev
    ```
5. Open your browser and navigate to `http://localhost:3000` to start using **SiteBuilder**.

## Contributions 🤝

I welcome contributions from the community! Whether it’s bug fixes, new features, or improvements, your contributions are always appreciated. Please follow the guidelines in the `CONTRIBUTING.md` file to get started.

## Roadmap 🛣️

- Add more AI models for code generation.
- Implement additional live coding environments for different languages.
- Improve UX/UI with more dynamic components.
- Create tutorials and documentation for beginners.

Happy coding! 🚀
