# LioranBoard: Alternate Chat Connection
Extension for people who have a second Twitch account connected to LioranBoard. Sets up a chat connection for the alternate account, which can be useful for broadcaster-only commands such as .mod and .vip. Includes an example deck and two extension commands:

* ***Alternate Chat Connection*** - Sets up the initial connection.
* ***Alternate Chat Message*** - Sends a message to chat. Identical to the "Twitch: Chat Message" command.

![Example](https://user-images.githubusercontent.com/55620774/115151337-be9ffc00-a06c-11eb-8320-81bd5bf3a49d.gif)

> **NOTE:** Any double quotes in the chat message should be escaped (`Mary said "hello"` should be written as `Mary said \"hello\"`). Use the default "String: Escape" command to automate this in case the message varies.

# Installation

## LioranBoard 2
1. Go to [Releases](https://github.com/Melonax/LB-Alternate-Chat-Connection/releases) and download `AlternateChatConnection.lb2` (make sure you get the LB2 release)
2. Click "Transmitter" in the LioranBoard 2 Receiver window
3. Click "Install an Extension"
4. Select `AlternateChatConnection.lb2` and click Open
5. The extension should work once the transmitter has reconnected

## LioranBoard 1
1. Go to [Releases](https://github.com/Melonax/LB-Alternate-Chat-Connection/releases) and download `AlternateChatConnection.lbe` (make sure you get the LB1 release)
2. Click "Install Extension" in the LioranBoard Receiver window
3. Select `AlternateChatConnection.lbe` and click Open
4. Select the transmitter you're using (default is `tsl_transmitter.html`) and click Save
5. The extension should work once the transmitter has reconnected
