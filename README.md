Project Overview

This project is a command-line diary application that lets users write, read, and manage diary entries.
Each entry is saved as a separate text file with a timestamp in the filename.
I used LocalDateTime and DateTimeFormatter to create unique filenames.

Core Features

Write Mode: Users can enter text and save it as a new diary entry.

Read Mode: Users can list all entries and read any chosen file.

Search: Users can search entries by keywords to find specific content.

Menu System: A simple text menu allows easy navigation.

Technical Details

File operations use BufferedReader and BufferedWriter.

File management uses java.nio.file.Files API.

All I/O exceptions are handled gracefully.

Entries are stored in the entries/ folder.

Advanced Features (Optional)

Serialization: Saves app configuration using object serialization (diary_config.ser).

Backup: Can create a ZIP archive of all diary entries for safekeeping.

Key Concepts Learned

File I/O and directory management in Java

Working with LocalDateTime and formatting timestamps

Exception handling for robust applications

Object serialization and backup using ZIP
