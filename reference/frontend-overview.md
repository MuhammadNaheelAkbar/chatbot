## pages

1. main page (chating)
2. priceing page

Components(main)



### **`/components` Directory Structure**

* **`layout/`** (The application shell)
* **`Sidebar.tsx`**: Main navigation container for history and user profile.
* **`TopBar.tsx`**: Header showing the active model and global actions.
* **`MainContent.tsx`**: The central wrapper for the chat interface.


* **`sidebar/`** (Navigation elements)
* **`NewChatButton.tsx`**: Action to clear state and start a fresh session.
* **`ChatHistoryList.tsx`**: Scrollable container for previous conversations.
* **`HistoryItem.tsx`**: Individual chat link with rename/delete functionality.
* **`UserProfile.tsx`**: Bottom section for account settings and plan status.


* **`chat/`** (The core interaction engine)
* **`ChatContainer.tsx`**: Manages the message list and auto-scrolling logic.
* **`EmptyState.tsx`**: The "Ready when you are" landing view for new chats.
* **`MessageList.tsx`**: Maps through the array of messages to render bubbles.
* **`MessageBubble.tsx`**: The wrapper for individual AI or User responses.
* **`StreamingCursor.tsx`**: Visual indicator shown while the AI is "typing".


* **`input/`** (User command center)
* **`ChatInput.tsx`**: The auto-expanding textarea for sending messages.
* **`AttachmentButton.tsx`**: Handles file and image uploads.
* **`VoiceToggle.tsx`**: Interface for speech-to-text input.
* **`SendButton.tsx`**: Trigger for submitting the prompt to the FastAPI backend.


* **`ui/`** (Reusable primitive components)
* **`MarkdownRenderer.tsx`**: Converts AI text into formatted HTML.
* **`CodeBlock.tsx`**: Syntax highlighting container with a "Copy" button.
* **`Tooltip.tsx`**: Small hover labels for icon buttons.



