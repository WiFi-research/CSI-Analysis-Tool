#  CSI-Analysis-Tool

Made in Taiwan

Ming Chuan University

Department of Electronic Engineering

CHANGRLOG:

Version 6(20180924)

    data_loader add Create_New_Database_CSI_phase,Create_New_Database_RSSI

Version 5(20180614)

    Fix Muilt Bug

Version 4(20180512)

    Fix Muilt Bug
    
    Add "Not found" (return 1)

    Add Analysis_Hugo (fast,but use more memory)

Version 3(20180506)

    Add plot_CSI_six_animation(Packet_range,Speed)

    Add plot_CSI_six(Packet)

    Example in Analysis.py

Version 2(20180504)

    Add Muilt_data

    Add ckeck empty packet

    Add plot example:

![image](https://i.imgur.com/3eraYJf.png)


First Version(20180503)

    Analysis CSI Packet(dat file)

    Include Bfee_count Perm Nrx Ntx Noise RSSI CSI Complete_Format

    Example file: python main.py (Need to add dat file's path into python source code)

Using:  

Complier: make

Create h5py database: example in data_loader.py

Analysis dat packet: at Analysis.py

python version: python 3
