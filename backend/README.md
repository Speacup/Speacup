
# Chatter's Backend with Golang

Using web socket to connect the conversation.

## Architecture

1. User
  The user of the app, it's about the user's detail. The username is unique, it will appear as @username on the app. it also contain user personification (gender, attracted to)

2. Chat
  The message format and details

3. Session
  The session is created when 2 User is connected/matched.

4. Chat Histories
  Inside `Session` it store the chat histories (idk maybe we will need it)
