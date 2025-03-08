# README

## Description
This program converts a Bitmap (.bmp) image to a TIFF (.tiff) image using a command-line interface.

## Build Instructions

### Method 1 (Direct Build & Run)

```sh
# Create the executable
make my_project

# Execute the program
./my_project <source_image> <destination_image>

# Example:
./my_project input.bmp output.tiff

# Clean up generated files
make clean
```

### Method 2 (Manual object file creation)

```sh
# Generate object files from source files
make source_file.o

# Use the object files to create the executable
make my_project

# Run the executable
./my_project <source_image> <destination_image>

# Example:
./my_project input.bmp output.tiff


# Clean up generated files
make clean
```

