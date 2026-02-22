# JuiceConverter
Command Line utility for converting .juice files to .txt and back

## Usage:

1. Drag and drop .juice file (or folder) onto the executable file/folder to convert to .txt
2. Make your modifications to the .txt file(s)
3. Drag and drop the .txt file (or folder) onto the executable to convert back to .juice
4. Place the modified .juice file into the correct path
5. Launch Game

Supported Juice files: .juice, .rejuice, .mreward, .mtalent, .mtalentrules

## Notes:

- Additional lines CAN NOT be added to the '.txt' at the moment. You can only modify what is there already. (Related to binjuice number)
- DO NOT modify the binjuice {number} value at the top of the file.
- The binjuice number appears to be the compiled size of the file that the engine parses at runtime, if the value is incorrect; the game will crash.
