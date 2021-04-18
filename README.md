# LioranBoard: Alternate Chat Connection
Extension for people who have a second Twitch account connected to LioranBoard. Sets up a chat connection for the alternate account, which can be useful for broadcaster-only commands such as .mod and .vip. Includes an example deck and two extension commands:

* ***Alternate Chat Connection*** - Sets up the initial connection. Use with Extension trigger !transmitteralways.
* ***Alternate Chat Message*** - Sends a message to chat. Identical to the "Twitch: Chat Message" command.

> **NOTE:** Any double quotes in the chat message should be escaped (`Mary said "hello"` should be written as `Mary said \"hello\"`). Use the default "String: Escape" command to automate this in case the message varies.

## Installation
1. Go to [Releases](https://github.com/Melonax/LB-Alternate-Chat-Connection/releases) and download `Alternate Chat Connection.lbe`
2. Click "Install Extension" in the LioranBoard Receiver window
3. Select `Alternate Chat Connection.lbe` and click Open
4. Select the transmitter you're using (default is `tsl_transmitter.html`) and click Save
5. The extension should work once the transmitter has reconnected
