# Kiko

Kiko stands for Keys-In-Keys-Out. It was designed specifically to handle animation curves data in a pipeline-friendly way, but it can do much more.
With Kiko you can define operators that can handle different kind of data per item or channel and can work automatically across different DCCs.

Currently Autodesk Maya and The Foundry Nuke are supported. 

Kiko was designed and implemented by Toolchefs LTD. We have decided to contribute to the 3D Industry making it open source.

Kiko is written completely in python.

### Current status of the project

Kiko has already been used on Maya 2016 onwards and on Nuke 11. 
We are looking for contributors who could help us making it work on others DCCs (i.e. Modo, Houdini) and writing new operators.

Few things are missing, like UIs for Nuke, cross app tests, etc.

## Getting started

### Installing
Installing in Maya it is quite easy.
```
- copy the entire folder in your maya scripts folder.
- you can launch the maya importer and exporter UIs by running the code under kiko/extras/maya.
```

## Running the tests
We use nose for our unit tests. Currently we only support windows and osx, but feel free to create a run_linux.py file if you want to test it in that environment.
Your MAYA_PLUG_IN_PATH and proper python paths must be set for the unit tests to succeed.

Once you environment is set up, you can run the run_win.py or run_osx.py files inside the kiko/unittests folder. Please note, you might have to edit these files to point to your maya and nuke executables.

## Wiki
If you are a developer and would like to know more, please have a read to the [wiki](https://github.com/danielefederico/kiko/wiki) and write to us at support@toolchefs.com in case you have any question.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under [the LPGP license](http://www.gnu.org/licenses/).

## Contact us

Please feel free to contact us at support@toolchefs.com in case you would like contribute or simply have questions.

The rig used in the unit tests is courtesy of Alex Puente.

### ENJOY!




