# GSoC @ Arduino: Ideas List

## Libraries

[Libraries](https://www.arduino.cc/en/reference/libraries) are a fundamental component of Arduino. They allow users to enrich their applications with advanced functionality or to support shields, sensors, actuators connected to their Arduino board.
We now have more than 70 [official libraries](https://github.com/arduino-libraries), in addition to 2,400+ contributed libraries.

### Idea: write an analyzer for Arduino libraries

Assuring quality of the Arduino libraries is very important. This task is about writing a crawler combined with a C++ static analyzer that is able to check all the official and third-party libraries in order to detect some interesting things such as:

* whether they only use the Arduino API or they also perform lower-level operations (this behavior ties the library to a particular board and prevents its portability on other boards)
* whether they violate coding conventions
* whether they use deprecated API calls
* ...

This crawler should output a detailed summary of the findings.

* *Languages:* Go (crawler), C++ (static analyzer)
* *Difficulty:* Easy/Medium

### Idea: write examples for official libraries

Many of the [official libraries](https://github.com/arduino-libraries) need more examples in order to help users understand how they can be used. Examples are located in the same repository as the library itself under the `examples/` directory. If you find a library that has no examples, or insufficient to show its capabilities, that's a good candidate! Make sure you understand what the library does, and what projects it can be used for.

Bonus points to students who also plan to build hardware prototypes that show how the libraries can be used (and document them in [Project Hub](https://create.arduino.cc/projecthub)).

* *Languages:* C++
* *Difficulty:* Easy/Medium (according to the libraries complexity)
* *Note:* your application should contain a list of libraries which need examples and which you would like to work on.

## Portenta

The Portenta board is not available yet, but accepted students will be sent a free one. For now, since we're finalizing the first code repositories, it's not possible to send early contributions. You can still send some contributions to another Arduino repo even if you plan to work on a Portenta (see the [application guide](how-to-apply.md)).

### Idea: port FreeRTOS to Portenta

This task is about porting [FreeRTOS](https://www.freertos.org) to the new [Portenta](https://www.arduino.cc/pro/hardware/product/portenta-h7) board.

* *Languages:* C++
* *Difficulty:* Advanced
* *Note:* accepted students will be sent a free Portenta board. Make sure your application contains proof of experience with the low level programming required for such task.

### Idea: write MicroPython examples and tools for Portenta

The new [Portenta](https://www.arduino.cc/pro/hardware/product/portenta-h7) board supports [MicroPython](https://micropython.org) in addition to Arduino code. This combination opens up many new opportunities. This task is about writing examples about using MicroPython on a Portenta board. Any example is welcome: for example, you might show how to use the hardware peripherals from Python, or you might want to port Arduino examples to Python.

Bonus points to students who also plan to build hardware prototypes around their examples (and document them in [Project Hub](https://create.arduino.cc/projecthub)).

* *Languages:* Python, C++
* *Difficulty:* Medium/Advanced
* *Note:* accepted students will be sent a free Portenta board.

### Idea: write JerryScript (JavaScript) examples and tools for Portenta

The new [Portenta](https://www.arduino.cc/pro/hardware/product/portenta-h7) board supports [JerryScript](https://jerryscript.net) in addition to Arduino code. This combination opens up many new opportunities. This task is about writing examples about using JerryScript (JavaScript) on a Portenta board. Any example is welcome: for example, you might show how to use the hardware peripherals from JavaScript, or you might want to port Arduino examples to JavaScript.

JerryScript can run on Portenta on top of mbed. See [this documentation](https://os.mbed.com/javascript-on-mbed/) for reference.

Bonus points to students who also plan to build hardware prototypes around their examples (and document them in [Project Hub](https://create.arduino.cc/projecthub)).

* *Languages:* JavaScript, C++
* *Difficulty:* Advanced
* *Note:* accepted students will be sent a free Portenta board.

## arduino-cli

### Idea: add network discovery support to arduino-cli

[arduino-cli](https://github.com/arduino/arduino-cli) is a command line tool for programming Arduino boards. This task is about implementing a functionality for discovering boards over network in addition to USB.
See more details in https://github.com/arduino/arduino-cli/issues/344

* *Languages:* Go
* *Difficulty:* Advanced

