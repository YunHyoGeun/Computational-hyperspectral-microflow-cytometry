![image](https://github.com/YunHyoGeun/Computational-hyperspectral-microflow-cytometry/assets/74758420/6c868d38-5b3f-455e-bf58-e3f5d69cb58c)# Yun et al. Nature Communications 2023_Computational-hyperspectral-microflow-cytometry
Spectral reconstruction &amp; Umixing matlab code 


Every code is run on "MATLAB R2022b"

01. Reconstruction
	- The main code is "Cell_profile_processing_ver10.2_edge4.2.mlx"
		runnnig with imges and other xls. mlx. files, contained in the folder
	- After running, the final result is "Data2", copy it to 02.Data2.xls in 02.Unmixing folder
		(row,column)=(2:end, 2:end)

02. Unmixing
	- The main code is "03.Unmixing_ver7.7.mlx"
		running with "01.mono_average_230423.xls", and "objectiveFcn41.mlx", contained in the folder
	- the final result is "Sol12"


Both codes produce the video and result array

please check the video and result array



also, we upload whole file in drive
https://drive.google.com/drive/folders/1gLVa2dFqKb78-F7tiF-z8mHuSJ5k4HYs?usp=drive_link
