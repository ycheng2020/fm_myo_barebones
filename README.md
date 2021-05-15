# Electromyogaphy-based Mouse Pointer Control with Python

## Abstract
*A brief description of the context of your project, your approach and your results. About 150 words.*

## Requirements
### Software packages
Always required in the documentation.
* __OS__: Operation System(s) the project can run on;
* __Languages__: programming languages used in the project;
* __Dependancies__: packages, libraries, data required for the project but defined outside of it (examples: *numpy*, *matplotlib*, *rosserial*)

### Hardware
Required only if any specific hardware, other than a regular PC, is used in the project.
* __Computer model__: if running on a specific type of computer (examples: *Raspberry Pi*, *NVIDIA Jetson*, ...);
* __Core__: microcontroller or evaluation board  model (examples: *Arduino Nano*, *ATMEGA328p*, *PIC16f877a*, ...);
* __Components__: other hardware pieces (examples: *Temperature sensor TMP36*, *Webcam*, ...), may require a separate specification and schematics;
* __Other evaluation and development systems__: examples: *Turtlebot Kobuki base*).

## Installation and setup
*A guide on how to install the code and setup the hardware to be able to run it.*

## Architecture
*Notes and schematics on the architecture of the project.*
*You may use relative links to point at specific files in your repository, for example [see README](README.md).*

## Examples
*This is your guide on how to run basic use cases of your project, with the description of expected outputs.*
*You may cite the code in your text using backticks: \'import numpy\` => `import numpy`*
*You may cite blocks of code using enclosing them by triple backticks ( \`\`\` ): and also specify the language:

\`\`\`python
import pyserial

def connect_serial(port = '/dev/ttyUSB0'):
&nbsp;&nbsp;&nbsp;&nbsp; try:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ser = serial.Serial(port)
&nbsp;&nbsp;&nbsp;&nbsp;  except serial.SerialException as e:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    print('Please specify a valid port from the list:')
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    print(serial.tools.list_ports)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    raise e
&nbsp;&nbsp;&nbsp;&nbsp;  return ser
\`\`\`

*will become:*

```python
import pyserial
def connect_serial(port = '/dev/ttyUSB0'):
  try:
    ser = serial.Serial(port)
  except serial.SerialException as e:
    print('Please specify a valid port from the list:')
    print(serial.tools.list_ports)
    raise e
    return None
  return ser
```
