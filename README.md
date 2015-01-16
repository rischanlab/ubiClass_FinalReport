# ubiClass_FinalReport

Rischan - Final Report for Ubiquitous Class

In Ubiquitous Class, My Professor want me to manage that class. Please see project in https://github.com/rischanlab/ubiquitousClass

In that project, I asked all of students to collect their personal data such as gait data when they run, stand, walk, etc, earshape, 
and etc. 

The aim of this class is to implement previouse works from our lab with different dataset. 

This project is my final report for this class.

The content of this project can be seen directly in this project and you can access the source code in directory source code. 

All of work in this project coded by using R language. 

If you need some reference just follow this link http://rischanlab.github.io/

#Content

In this project, I implement gait pattern for user identification. I use only walking data and based on those data, I extracted features. 

Before extracting features, I tried to segmenting the gait signals. I defined the True peaks from the gait signals (only using Z value | you can see our presentation for the details).  After segmenting the gait signals, I extracted the features from each gait cycles. 

Features that I used are in the time domain (min, avg, max acceleration value from each signal, etc) and in the frequency domain (transfrom time domain to frequency domain using FFT). 

I applied SVM as our classification method. The result can be seen in this project. 

Thank you, 
