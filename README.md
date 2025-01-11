# Outlook Support Request Automation Tool

This application streamlines the process of creating and sending support requests via the Microsoft Outlook client on Windows. It's designed to simplify and automate the composition of emails, reducing manual effort and ensuring consistency in support communications.

This tool originated from a specific project where I aimed to reduce the number of customer support calls by providing a user-friendly way to submit support requests via email. 

## Key Features

*   **Automated Email Generation:** Pre-fills email fields (To, Subject, Body) based on user input or pre-defined templates, minimizing manual typing.
*   **Simplified User Interface:** Provides a clean and intuitive graphical user interface (GUI) for easy data entry.
*   **Outlook Integration:** Seamlessly interacts with the Outlook client to compose and display (or send) emails directly.

## Technologies Used
*   **Go:** The application is written in Go
*   **Walk:** As the target audience are Windows-only clients, this project utilizes [Walk](https://github.com/tailscale/walk), a Windows-specific native GUI library for Go. Walk provides a native Windows look and feel, ensuring a familiar user experience.
*   **go-ole:** [go-ole](https://github.com/go-ole/go-ole) is used to interact with the Component Object Model (COM) on Windows. This allows the application to control the Outlook client programmatically.
