Step 1: Create Trigger
Add the trigger “When chat message received.”
This trigger activates whenever a user sends a chat message to the system.

Step 2: Add AI Agent Module
Click the + icon after the trigger.
Select AI Agent.
Connect the trigger output to the AI Agent input.

Step 3: Select Chat Model
Under the AI Agent settings, choose Chat Model.
Select Google Gemini Chat Model (or any available AI model).
Connect the model to the Chat Model port of the AI Agent.

Step 4: Configure Memory (Optional)
If conversation history is required, click Memory (+).
Add a memory component so the AI remembers previous chats.

Step 5: Add Tools (Optional)
Click Tool (+) to connect tools such as Gmail, database, or API.
This allows the AI agent to perform actions based on the message.

Step 6: Save and Test
Save the workflow.
Send a test chat message.
The trigger activates → AI Agent processes the message using Gemini → Response is generated automatically.

![1000091726](https://github.com/user-attachments/assets/c2996b42-4d54-41f5-a719-8a487a7e9a1e)
