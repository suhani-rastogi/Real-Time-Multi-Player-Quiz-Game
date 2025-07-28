This project introduces a comprehensive multiplayer quiz game developed using Python.

It utilizes a client-server model with real-time communication established through socket programming.

The client interface is built using Tkinter, offering a user-friendly GUI for login, topic selection, and answering questions.

Users must log in with credentials, validated through a flat file (Credentials.txt) authentication system.

Upon successful login, users select from various quiz genres such as General Knowledge, Science, Mathematics, English, Logical Reasoning, etc.

Questions are sourced dynamically from a structured Excel file (Questions.xlsx), where each sheet represents a topic.

Each question session is timed, with a countdown timer of 60 seconds integrated into the GUI to encourage quick thinking.

The server handles multiple clients concurrently, delivers questions, receives answers, and calculates the score in real time.

The quiz features both multiple-choice and typed-answer questions, offering a flexible testing format.

Score tracking is implemented on the server side, and future enhancements can include a result page, score breakdown, or leaderboard.

Python libraries used include socket, threading, pandas, openpyxl, and tkinter.

The project is ideal for educational environments and can be extended to support a web-based version, persistent database storage, or encrypted login systems.

It demonstrates core concepts such as networking, GUI development, file handling, user authentication, and real-time event handling.

Overall, the application offers a well-rounded and interactive multiplayer quiz experience, suitable for both learning and competition.
