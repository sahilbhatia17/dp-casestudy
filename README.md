###Instructions
Run the following command to start the interface
```
python snuba_interface.py
```
Currently, the interface supports two labeling modes:```random batch select``` and ```active sampling```(default = active sampling). The mode can be changed by setting the ```selection_method``` variable in ```snuba_interface.py``` (loc 28).