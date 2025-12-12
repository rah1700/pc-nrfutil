\## Regenerating dfu\_cc\_pb2.py



opy \\workspace\\ommo\_nrf\\nRF5\_SDK\_17.1.0\_ddde560\\components\\libraries\\bootloader\\dfu\\dfu-cc.proto nordicsemi\\dfu

protoc --proto\_path=nordicsemi\\dfu --python\_out=nordicsemi\\dfu nordicsemi\\dfu\\dfu-cc.proto



\## Running nrfutil



set PYTHONPATH=.

python nordicsemi ...



\## Packaging and installing to conda environment



rd /s /q build

python setup.py install



Examine the output for errors.  Evidence suggests the script is not good at check for errors or summarizing them.



