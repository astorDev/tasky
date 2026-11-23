# Tasky Messenger

The module investigates organizing tasky as a messenger:

- A task becomes a chat.
- A chat gets an assistant bot.
- Messages both from you and from the assistant bot move the chat in the master view.
- Unsnoozing and reminders become a reminder message from an assistant bot.
- "Active" status becomes periodic "you haven't done anything in a while" from an assistant bot. 
- Subtasks become messages in a chat.
- Attachments and descriptions become messages in a chat.
- Completion becomes silence from the bot, which moves chats down. Optionally it could also have a visual identification.

## AI Assistance

Assistant bot is a fundamental building block of the system. At the foundation, however, it does not really need to be AI - reminders are a perfect case for deterministic services. However, adding AI capabilities would allow users to:

- Deal with [Frogs](../frogs/README.md)
  - Instead of thinking "I need to check ..." (painful) a user can say "Assistant, go check" (cool)
  - Instead of thinking "I need to write an e-mail" (painful) a user can say "Assistant, go write an e-mail" (easy)
  - Instead of thinking "Oh god, how do I do that?" (painful) a user can say "Assistant, create a plan"
- Access AI capabilities inline (without switching apps) and give AI context for a problem from chat messages.