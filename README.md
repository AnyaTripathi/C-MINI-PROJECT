# Faculty Timetable Generator

A C-based timetable management system that automates faculty scheduling while preventing timetable conflicts between faculty and batches.

## Features

- Prevents faculty scheduling clashes
- Prevents batch conflicts
- Stores data using CSV files
- Displays slot status:
  - FREE
  - OCCUPIED
  - BLOCKED
- Modular code structure
- Real-time timetable updates

## Technologies Used

- C Programming
- GCC Compiler
- File Handling (CSV)
- Structures
- Arrays
- Modular Programming

## Project Structure

```bash
├── main.c
├── fileio.c
├── timetable.c
├── ui.c
└── data files (.csv)
```

## How It Works

1. Enter faculty and subject details
2. Select a batch
3. View available slots
4. System checks for conflicts
5. Save timetable automatically

## Future Improvements

- Student priority voting system
- GUI implementation
- Database integration
