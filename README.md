This is a simple way to send encrypted messages over email, or direct messages.
It consists of a single, stand-alone html file that uses no dependencies, and doesn't access the internet.

HOW IT WORKS
Each party must have the secure-share.html file downloaded.
Open it up in your browser.

The receiver clicks a button to generate a private/public key pair.
The receiver emails or direct messages the public key to the sender.

The sender pastes the public key into the web page.
The sender enters a message in the web page.
The sender clicks a button to encyrpt the message using the sender's public key.
The sender emails or direct messages the encrypted message to the receiver.

The receiver pastes the encyrpted message into the web page.
The receiver click a button to decrypt the message.

USE CASES
A third party needs to send you credentials to use their API.
You need to send a new employee their email or server credentials, but don't have a BitWarden subscription, or don't trust it.
You need to send someone a code for your garage opener.
