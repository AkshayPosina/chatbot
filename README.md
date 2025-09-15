# Akshay's AI Chatbot 🚀

![Vercel Deployment](https://img.shields.io/github/deployments/AkshayPosina/chatbot/production?label=Vercel&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/AkshayPosina/chatbot?style=for-the-badge)

A web-based chatbot built with Next.js and the Vercel AI SDK, powered by Google's Gemini model. This project serves as a demonstration of building a modern, streaming AI interface with a clean and responsive design.

![Chatbot Screenshot](https://user-images.githubusercontent.com/your-username/your-repo/your-screenshot.png) 
*<p align="center">A live demo is available at: [chatbot-djnu.vercel.app](https://chatbot-djnu.vercel.app/)</p>*

---

## ✨ Features

- **Real-time Streaming:** AI responses are streamed in real-time for a natural conversational flow.
- **Conversation History:** All chat threads are saved and can be revisited from the sidebar.
- **Responsive Design:** The user interface is fully responsive and works on both desktop and mobile devices.
- **Cloud Deployment:** Deployed on the Vercel Edge Network for high performance and availability.

---

## 🛠️ Tech Stack

| Category          | Technology                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------ |
| **Framework** | [Next.js](https://nextjs.org/) (React)                                                                 |
| **Language** | [TypeScript](https://www.typescriptlang.org/)                                                          |
| **AI / SDK** | [Vercel AI SDK](https://sdk.vercel.ai/docs), [Google Gemini](https://ai.google.dev/)                    |
| **UI Components** | [assistant-ui](https://github.com/Yonom/assistant-ui), [Radix UI](https://www.radix-ui.com/)             |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/)                                                               |
| **Deployment** | [Vercel](https://vercel.com/)                                                                          |

---

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js (v18 or later)
- pnpm (or your preferred package manager)

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/AkshayPosina/chatbot.git](https://github.com/AkshayPosina/chatbot.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd chatbot
    ```
3.  Install the dependencies:
    ```bash
    pnpm install
    ```
4.  Create a `.env.local` file in the root of your project and add your API key:
    ```
    GOOGLE_GENERATIVE_AI_API_KEY=your_api_key_here
    ```
5.  Run the development server:
    ```bash
    pnpm dev
    ```
