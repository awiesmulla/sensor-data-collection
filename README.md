# sensor-data-collection

Scripts to collect and plot raw IMU (Witmotion IMU) and GPS data in csv format

## Usage

Run the following command to install required python libraries

'''
pip3 install -r requirements.txt
'''

### IMU data

IMU_collect.py stores accelerometer values (along x and y axes) and gyrometer values (along z axis) //
To collect the IMU data run the following command

'''
python3 IMU_collect.py <name of the test run>
'''
### GPS data

gps_collect.py stores the x and y cartesian coordinates w.r.t. start pose //
Run the following to collect GPS data

