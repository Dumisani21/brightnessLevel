# Brightness Light Controller

This is a simple brightness light controller that can be used on Linux operating systems. It was created for users who have tried recovering their brightness leveler tab but it does not work.

## Installation

1. Download the [brightness light controller](light).
2. Give the file executable permissions: `chmod +x light`
3. Move the file to the `/usr/bin` directory: `sudo mv light /usr/bin/`

## Usage

To use the brightness light controller, simply run the following command:

```bash
light <brightness level> # replace <brightness level> with float numbers
```

The brightness level should be a float between 0.0 and 0.9, where 0.0 is the lowest brightness level and 0.9 is the highest brightness level.

For example, to set the brightness level to 0.5, you would run the following command:
```bash
light 0.5
```
