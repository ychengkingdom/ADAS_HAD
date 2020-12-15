Carla0.9.9 Installa from prebuild version

Requirements:

Intel i7 gen 9th - 11th / Intel i9 gen 9th - 11th / AMD ryzen 7 / AMD ryzen 9
+16 GB RAM memory
NVIDIA RTX 2070 / NVIDIA RTX 2080 / NVIDIA RTX 3070, NVIDIA RTX 3080
Ubuntu 18.04

System Setup:

Good Network connection.
1. Ubuntu 18.04 install completely with third party software.
2. Install the Nvidia official recommended driver for RTX2080TI/3090TI.
	
3. Update the default python3.6 to python 3.7
4. Dowload the prebuild Carla0.9.9 version.
5. Unzip the carla-0.9.9-py3.7-linux-x86_64.egg in the path:
	Carla/PythonAPI/carla/dist
   and enter the Carla/PythonAPI/carla/dist/carla-0.9.9-py3.7-linux-x86_64
   and create setup.py with code as below:

	from distutils.core import setup
	setup(name='carla',
	        version='0.9.9',
	        py_modules=['carla'],
	        )

