# CE888_Assig2
In this repository, you will find all the files and notebooks used for the final assignment of CE888. We have a complete data science project; therefore, there are exploration and modeling files. All of those allows to achive the conclusions.
# How does it work?
You need the PDF report to guide you to surf from one notebook to other.
If you do not have the PDF the order to check the files is the following:\\

1.DataPREP.ipynb contains all data processing, there are many comments to understand the flow work and brief explanations about why doing one thing or other.
If you want to replicate que same result you need the file *RAW DATA* in your computer.
2. As a result of DataPREP.ipynb two excel file are exported, one respect the default label(merge30seg.xlsx) and the other where label is changed from 0 and 1 to 0,1,2,3. (you will find that excel here! do not worry) "merge30sec_NewLabels.xlsx".Finally, datasets contained in both files are used to train a random forest.
3. Then a LSTM is trained (LTSMGen+RFg.ipynb) for that some corrections are done over dataset contained in "merge30sec_NewLabels.xlsx" to standarize data for using a LSTM structure, as a result a new dataset is generated, it is contained in file named 'DataLSTM_levels.xlsx', therefore, to replicate the results you need to use that file.
