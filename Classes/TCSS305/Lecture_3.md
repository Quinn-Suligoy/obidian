# Factory Method
- method that is responsible for instantiating and returning object to you
- Ex)
```
public static final Logger LOGGER = Logger.getLogger(...)
```
# Memory Model
- Call Stack
	- Spot of continuous memory working up
	- Stores all variables defined in each method in stack frame stored on stack
		-  Including references to objects
		- Return pointer that points to where code execution will return to
	- Static Space
- Heap Space
	- Actual objects store here
	- Continuous memory space working down, under stack
	- Dynamic space