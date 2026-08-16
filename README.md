# CP4 — Competitive Programming 4: Source Code

Code samples from the book *Competitive Programming 4* by Steven & Felix Halim. Covers a wide range of classical data structures and algorithms, with implementations in four languages:

- C++ (gnu++17)
- Java (Java 8)
- Python 3
- OCaml

Code is organized by chapter (`ch1/`, `ch2/`, etc.), mirroring the book's structure. Each chapter folder also has an `Exercise_*` subfolder with solutions to the in-book exercises.

## Usage

Feel free to copy, adapt, and use the code. If you use it in something published, please cite Steven & Felix Halim. License: [UPL](https://opensource.org/licenses/UPL).

## Running the samples

Each file is self-contained. For C++:
```bash
g++ -std=gnu++17 -o out file.cpp && ./out < input.txt
```

For Java:
```bash
javac File.java && java File < input.txt
```

For Python:
```bash
python3 file.py < input.txt
```

Input files (`.txt`) for each sample are included alongside the source.
