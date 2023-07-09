# Gmail Auto-Responder

Gmail Auto-Responder is a Node.js application that automatically sends vacation response emails to incoming messages in your Gmail mailbox. It uses the Gmail API to authenticate, read emails, send replies, and manage labels.

## Prerequisites

Before running the application, make sure you have the following:

- Node.js installed on your machine
- Gmail API credentials (credentials.json) obtained from the Google Cloud Console
- OAuth client ID and client secret for desktop applications

## Installation

1. Clone the repository or download the source code:

   ```shell
   git clone <repository-url>
Install the dependencies:

shell
Copy code
cd gmail-auto-responder
npm install
Place your Gmail API credentials (credentials.json) in the project root directory.

Configuration
Open the index.js file in a text editor.

Set the desired scopes for accessing Gmail. Modify the SCOPE array according to your requirements.

Configure the label name for auto-replay. Replace the labelName variable with your desired label name.

Set the port number (optional). Modify the port variable to specify the desired port for running the application.

Usage
Start the application:

shell
Copy code
npm start
Open your web browser and navigate to http://localhost:<port>. The application will authenticate with your Gmail account and begin sending auto-responses to incoming emails.

The application will run continuously in the background, periodically checking for new emails and sending replies as necessary.