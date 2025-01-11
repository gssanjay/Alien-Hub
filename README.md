METI-Cord Chat Application

A simple, interactive web-based chat application with features like message sending, emoji selection, theme switching, and message persistence using local storage.
Features

    Real-Time Messaging: Send and view messages with a clean, responsive interface.
    Emoji Picker: Add emojis to your messages with a convenient emoji picker.
    Dark/Light Theme: Toggle between dark and light themes for better usability and aesthetic appeal.
    Message Deletion: Remove unwanted messages with a delete button.
    Message Persistence: Messages are saved locally and persist after page reloads.
    Mobile-Friendly: A responsive layout ensures the application works well on all devices.

Usage Instructions
Getting Started

    Clone or download the repository.
    Open the index.html file in any modern web browser.

How to Use

    Sending a Message:
        Type a message in the input field.
        Press the "Send" button or hit the Enter key to send the message.
    Adding Emojis:
        Click on the emoji button (😀) to open the emoji picker.
        Select an emoji to insert it into the message input.
    Switching Themes:
        Click the "Switch Theme" button in the header to toggle between dark and light themes.
    Deleting Messages:
        Click the "X" button next to a message to delete it.
    Persistent Messages:
        Messages are automatically saved in local storage and will reappear when the page is reloaded.

File Structure

    index.html: Contains the main HTML structure and inline CSS styles.
    styles.css: (Optional) External CSS file for additional styling (link included in HTML).
    script.js: Contains the JavaScript for the chat application’s functionality.

Technologies Used

    HTML5: For structure and layout.
    CSS3: For styling and theming.
    JavaScript (ES6): For interactive functionality and local storage integration.

Customization

    Adding Emojis:
        Open the #emoji-picker <div> in the HTML and add new <span> elements with the desired emoji characters.
    Changing Colors:
        Update CSS variables or specific class properties in the <style> section or styles.css.
    Modifying Themes:
        Edit the .dark-theme styles in the CSS section for a custom dark theme look.

Future Enhancements

    Multi-User Support: Enable real-time messaging across different users using WebSockets or Firebase.
    Attachments: Add support for sending files and images.
    Notifications: Notify users of new messages in real time.
    Database Integration: Replace local storage with a backend database for scalable message storage.

License

This project is licensed under the MIT License. Feel free to modify and distribute it.
