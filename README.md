# bluetooth-max6675

A Bluetooth temperature service reading from a MAX6675 device

## Usage

Simply call ``startMax6675Service`` with the pin where the MAX6675 is connected
to start a service that beams the temperature every second.

```blocks
bluetooth.startMax6675Service(DigitalPin.P0);
```

## License

MIT

## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)

```package
bluetooth
bluetooth-temperature-sensor
bluetooth-max6675
```