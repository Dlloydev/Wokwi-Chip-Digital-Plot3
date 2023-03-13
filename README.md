# Wokwi-Chip-Digital-Plot3

## Description

Plot up to 3 Digital Signals.

- Plotter `Sample Time μs` range is 10µs to 10000 ms (default 100 µs).
-  Width of plot is 250 samples.
- `D0 Trigger` modes are Off (`0`) Rising (default) ⬆ and Falling ⬇
- Displays peak volts`Vmax`, and minimum volts `Vmin`
- Displays  Sample Time `us` and Capture Time `ms`



![image](https://user-images.githubusercontent.com/63488701/224606843-e65ecaab-c9bc-456d-bfee-e0ffe66ae27a.png)

## ![image](https://user-images.githubusercontent.com/63488701/224565532-a949f62d-dfe1-478e-97dd-6c274d61cade.png)

| Name | Description                                       |
| ---- | ------------------------------------------------- |
| D0   | Input  configured as INPUT, also the trigger pin. |
| D1   | Input  configured as INPUT.                       |
| D2   | Input  configured as INPUT.                       |

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-digital-plot3": "github:Dlloydev/Wokwi-Chip-Digital-Plot3@1.0.1"
  }
```

Then, add the chip to your circuit by adding a `chip-digital-plot3` item to the `parts` section of `diagram.json`:

```json
  "parts": {
    ...,
    { "type": "chip-digital-plot3", "id": "chip-digital-plot3-1" }
  },
```

The actual source code for the chip lives in [src/main.c](https://github.com/Dlloydev/Wokwi-Chip-Digital-Plot3/blob/main/src/main.c), and the pins are described in [chip.json](https://github.com/Dlloydev/Wokwi-Chip-Digital-Plot3/blob/main/chip.json).

## Example

[![Wokwi_badge](https://user-images.githubusercontent.com/63488701/212449119-a8510897-c860-4545-8c1a-794169547ba1.svg)](https://wokwi.com/projects/359020190499937281) Plot Digital Signals Example

## License

This project is licensed under the MIT license. See the [LICENSE](https://github.com/Dlloydev/Wokwi-Chip-Digital-Plot3/blob/main/LICENSE) file for more details.
