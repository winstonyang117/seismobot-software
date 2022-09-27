# seismobot-firmware

**This is the BLUE one, so make sure you run hte program on the correct board.**
Raspberry Pi software for reading the serial data from the board, which was designed and produced by InterstitialTech. Seismobot geophone board](https://github.com/InterstitialTech/seismobot-hardware)

## Dependencies

* Raspberry Pi 3b
* python3
* python3-serial

## Usage

Plug the geophone board in via the Pi's 40-pin header. Then:

```
python3 src/seismoBridge.py
```
