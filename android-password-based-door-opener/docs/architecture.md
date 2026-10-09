# Architecture and operation

This summary is based on the accompanying original final-year project report, particularly its abstract and Chapter 3.

## Data and control flow

1. An Android-based interface communicates with a Bluetooth receiver.
2. The receiver passes serial input to an 8051-family microcontroller.
3. The controller accepts password input and compares it with the value defined in the embedded C program.
4. Following successful validation, the controller accepts commands for opening or closing the door.
5. The controller drives L293D inputs to change the DC motor direction, then stops the motor after a programmed interval.
6. The LCD presents input and door-status messages.

## Documented hardware

- AT89S52/AT89C51-class 8051 microcontroller
- Bluetooth receiver/module
- L293D motor-driver IC
- DC motor
- LCD display
- Power supply and associated circuitry

## Source material in the report

- **Page 4 of the PDF:** project abstract
- **Page 30 of the PDF:** schematic diagram (Chapter 3, Figure 3.1)
- **Pages 31–34 of the PDF:** circuit description and operation
- **From page 36 of the PDF:** embedded C listing (Section 3.4)
- **Near the end of the PDF:** hardware testing and conclusion

Page references here are PDF viewer pages, which may differ from the report's printed page numbers.

## Scope and limitations

The original report documents an educational prototype. It does not establish production-grade authentication, secure Bluetooth pairing, or suitability for protecting a real entrance. The password is included as a fixed value in the firmware example; it should not be reused in a deployed access-control system.

The report contains general background sections about Android and embedded systems, in addition to project-specific implementation details. This repository does not assert that all background material represents custom-built functionality.
