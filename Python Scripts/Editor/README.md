# {insert fileformat} Editor

- File starts with 128 bytes of metadata
    - 64 character song title
    - 32 character artist name
    - 10 character date str (MM/DD/YYYY)
    - 1 bytes of settings
        - first bit chooses trigger (0) vs toggle (1) mode
    - 11 padding bytes