# Multi-language machine code comparison

 

### Result

| Language   | ext   | Interpreter Only | Freezing Tool | Execution time (AVG) | Disk size |
| ---------- | ----- | :---------: | :---------- | :---------: | ----------: |
| C          | .c    |             |   gcc   |   0.025 s   |   53 KB   |
| C++        | .cpp  |  | g++ | 0.031 s | 55 KB |
| Dart       | .dart |  | dart SDK | 0.041 s | 4,237 KB |
| Go         | .go   |                    | go SDK                        |       0.034 s        |      2,046 KB |
| JavaScript | .js   | :heavy_check_mark: | pkg (npm repository) | 0.083 s | **30,352 KB** |
| Python     | .py   | :heavy_check_mark: | pyinstaller (PyPI repository) | **0.7 s** | 5,439 KB |
| Rust       | .rs   |  | cargo | 0.028 s | 145 KB |



### Run test

> Windows x64 only: `ptime.exe {language_folder}\hello.exe`



