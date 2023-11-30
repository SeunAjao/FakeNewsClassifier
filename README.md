# FakeNewsClassifier
Fake News Detection using AI Models

**Overview**
We shall be using the Pheme Rumor-Non-Rumor (RNR) Dataset (Zubiaga et al 2016) using a deep learning model, a version of a recurrent neural network (RNN) called Long-Short-Term to predict if any of the tweets about some five events were fake or real.


**Dataset Description**
The PHEME dataset from the below site in the raw JSON format: https://figshare.com/articles/PHEME_dataset_of_rumours_and_non-rumours/4010619 

o	It contains a total of over 5,000 instances and tweets about these 5 events:

1.	Ottawashooting: The mass shooting at Parliament Hill in Ottawa.
2.	Charliehebdo: Attacks on the satirical weekly newspaper Charlie Hebdo in Paris
3.	Ferguson: Killing of an 18-year-old boy by a police officer in Ferguson, Missouri.
4.	Sydneysiege: A siege on the Lindt Chocolate Café in Sydney.
5.	germanwings-crash: Crash of Germanwings Flight 9525 from Barcelona to Dusseldorf.

o To help with the task, five simplified versions of the dataset has been made available in the main GitHub branch
as follows: combined rumor-non-rumor, Ottawashooting, Charliehebdo, Ferguson, Sydneysiege, Germanwings


o	Each row of data is in the format: “text” <tab> “label”

o	Where labels are given as 1 for fake/rumor and 0 for real/non-rumor messages


**References**

Zubiaga, A., Liakata, M. and Procter, R., 2016. Learning reporting dynamics during breaking news for rumour detection in social media. arXiv preprint arXiv:1610.07363.

CBC News. 2014. "Ottawa shooting: A day of chaos leaves soldier, gunman dead." https://www.cbc.ca/news/politics/ottawa-shooting-a-day-of-chaos-leaves-soldier-gunman-dead-1.2808710

BBC. 2015. "Charlie Hebdo attack: A timeline of how the terror unfolded" https://www.bbc.com/news/world-europe-30708237

CNN. 2014. “What we know about Michael Brown’s Shooting” https://edition.cnn.com/2014/08/11/us/missouri-ferguson-michael-brown-what-we-know/index.html

BBC. 2014. “Three dead after commandos storm cafe” https://www.bbc.co.uk/news/world-australia-30485355

New York Times 2015. “Germanwings Crash in French Alps Kills 150; Cockpit Voice Recorder Is Found” https://www.nytimes.com/2015/03/25/world/europe/germanwings-crash.html?searchResultPosition=3
