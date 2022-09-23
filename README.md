# Nim language syntax highlighting for mcedit

  - put `nim.syntax` file into `/usr/share/mc/syntax` directory
  - add following lines to `/usr/share/mc/syntax/Syntax`
  ```
  file .\*\\.(nim)$ zig\sProgram
  include nim.syntax
  ```
  right before these lines (they are in the very end)
  ```
  file .\* unknown
  include unknown.syntax
  ```
