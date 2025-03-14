# Spreadsheet Program

This project is a **basic spreadsheet application** developed in **C#** that supports mathematical calculations using **infix notation**. Future extensions will be implemented to enhance its capabilities.

## Features
- Supports **basic arithmetic operations** (addition, subtraction, multiplication, division).
- Parses and evaluates expressions in **infix notation**.
- Modular structure to allow for future enhancements such as functions, cell references, and more complex operations.

## Installation & Setup
### Prerequisites
- .NET SDK installed on your system.
- Visual Studio or another C# development environment.

### Clone the Repository
```sh
git clone https://github.com/yourusername/spreadsheet.git
cd spreadsheet
```

### Build & Run
#### Using Visual Studio:
1. Open the project in **Visual Studio**.
2. Restore NuGet packages if needed.
3. Click **Build** → **Run** to start the spreadsheet application.

#### Using .NET CLI:
```sh
cd Spreadsheet
dotnet build
```

To run the program:
```sh
dotnet run
```

## How to Use
1. **Enter a mathematical expression** into a cell.
2. The program will **evaluate the expression** and display the result.
3. Supports operations such as:
   - `5 + 3 * 2`
   - `(10 / 2) + 4`
   - `8 - 3 + 2`

## Code Structure
```
Spreadsheet/
│── src/
│   ├── Program.cs        # Entry point
│   ├── Spreadsheet.cs    # Core logic for spreadsheet functionality
│   ├── Parser.cs         # Expression parsing and evaluation
│── tests/                # Unit tests for functions
│── README.md             # Project documentation
│── Spreadsheet.sln       # Visual Studio solution file
```

## Future Enhancements
- Implement **cell references** (e.g., `A1 + B2`).
- Support for **more advanced functions** (e.g., `SUM(A1:A5)`, `AVG(B1:B5)`).
- Add **undo/redo functionality**.
- GUI improvements for better usability.

## License
This project is not allow academic misconduct.

## Author
Created by **Phuc Hoang** and **Chanphone Visathip**. Contributions are welcome!

