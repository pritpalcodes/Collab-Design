Build this project step by step with our detailed tutorial on JavaScript Mastery YouTube. Join the JSM family!
📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🕸️ Snippets
🔗 Links
🚀 More
🚨 Tutorial
This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, JavaScript Mastery.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!



🤖 Introduction
A minimalistic Figma clone to show how to add real-world features like live collaboration with cursor chat, comments, reactions, and drawing designs (shapes, image upload) on the canvas using fabric.js.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 27k+ members. It's a place where people help each other out.



⚙️ Tech Stack
Next.js
TypeScript
Liveblocks
Fabric.js
Shadcn
Tailwind CSS
🔋 Features
👉 Multi Cursors, Cursor Chat, and Reactions: Allows multiple users to collaborate simultaneously by showing individual cursors, enabling real-time chat, and reactions for interactive communication.

👉 Active Users: Displays a list of currently active users in the collaborative environment, providing visibility into who is currently engaged.

👉 Comment Bubbles: Enables users to attach comments to specific elements on the canvas, fostering communication and feedback on design components.

👉 Creating Different Shapes: Provides tools for users to generate a variety of shapes on the canvas, allowing for diverse design elements

👉 Uploading Images: Import images onto the canvas, expanding the range of visual content in the design

👉 Customization: Allows users to adjust the properties of design elements, offering flexibility in customizing and fine-tuning visual components

👉 Freeform Drawing: Enables users to draw freely on the canvas, promoting artistic expression and creative design.

👉 Undo/Redo: Provides the ability to reverse (undo) or restore (redo) previous actions, offering flexibility in design decision-making

👉 Keyboard Actions: Allows users to utilize keyboard shortcuts for various actions, including copying, pasting, deleting, and triggering shortcuts for features like opening cursor chat, reactions, and more, enhancing efficiency and accessibility.

👉 History: Review the chronological history of actions and changes made on the canvas, aiding in project management and version control.

👉 Deleting, Scaling, Moving, Clearing, Exporting Canvas: Offers a range of functions for managing design elements, including deletion, scaling, moving, clearing the canvas, and exporting the final design for external use.

and many more, including code architecture, advanced react hooks, and reusability

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/JavaScript-Mastery-Pro/figma-ts.git
cd figma-ts
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
Replace the placeholder values with your actual Liveblocks credentials. You can obtain these credentials by signing up on the Liveblocks website.

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.

🕸️ Snippets
Styles
tailwind.config.ts
app/globals.css
Overlay Comments
NewThread
PinnedComposer
NewThreadCursor
CommentsOverlay
PinnedThread
🔗 Links
Assets
Components
🚀 More
