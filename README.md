# ESPhome projects

# Repo Structure
```
./               is my /esphome folder containing YAML config for my devices
/common         includes templates used by devices
/build-(name)   device build details like wiring diagrams and component references
```
There are two special devices:
* Blank is a minimal device that works with the tempalate. Copied into new devices.
* Proto is a dev board on my bench before starting a build