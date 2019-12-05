

# wc_data_tools

This repo contains the data tools to support the data collection post processing activities for the autonomous wheelchair. 


# conversion

This directory contains the data collection post processing tools to convert from ROSBAG asynchronous data to CSV time-synchronized format.
The tool requires ROS Kinetic on Linux: 

   python wc_bagdump.py -i <input full path name directory> -o <output full path name directory>

Example: 
  cd ~/git/wc_data_tools/conversion

  python wc_bagdump.py -i '/media/nvidia/Seagate Backup Plus Drive/Data/WC/DATA_COLLECTION/BAG/TX2_IN/TEST-25-02-2019/' -o '/media/nvidia/Seagate Backup Plus Drive/Data/WC/DATA_COLLECTION/BAG/OUT_TX2_25-02-2019'


