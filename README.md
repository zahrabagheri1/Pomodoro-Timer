# 🍅 Pomodoro Timer — Project Description (Python)

The Pomodoro Timer is a productivity-focused Python application designed to help users manage their study or work sessions using the Pomodoro Technique — a time-management method that breaks work into focused intervals separated by short breaks. This project provides a simple and effective timer that runs in the command line and keeps track of completed work sessions.

The program consists of a main function along with several helper functions responsible for managing the timer, validating user input, and recording completed Pomodoro cycles. The timer follows the classical Pomodoro pattern:

- 25-minute work session

- 5-minute short break

- (Optional) 15-minute long break after several cycles

Users can choose how many Pomodoro cycles they want to complete, and the program will automatically run through the work/break sequence.

The project also includes a small persistent history system. After each completed session, the result is saved into a JSON file so users can track their progress across different days. Unit tests (via pytest) verify the correctness of key functions such as time calculations, cycle generation, and history saving.

## This project demonstrates the use of:
- Functions and modular design
- Loops and timer countdown logic
- File handling with JSON
- Basic input validation
- Writing and running tests with pytest

### The Pomodoro Timer is simple to extend—features such as notifications, sound alerts, or customizable session lengths can easily be added.