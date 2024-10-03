# Project Title: CNC-Tools-Life-Prediciton
<H1>Project Details</H1>
Demo Video URL: https://drive.google.com/file/d/1UE3h-vcLFZ14PfVKZMTqyX_4QJzZDcnC/view?usp=drive_link
<br>Github Repository URL: https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton.git
<h2>Requirments</h2>
<h3>Software:</h3>
1) Google Collab<br>
2) Database - Excel CSV Datasheet (Data collected from CNC machine)<br>
3) Firebase Database (Download ServiceAccountKey.json from respective database)<br>
<h3>Language:</h3> 
Python<br>
</p>
<H1>Problem Definition</H1>
<p>1. To identify the working of CNC machine in different conditions:<br>
&ensp;&ensp;* Starting condition of Tools.<br>
&ensp;&ensp;* Tools working but not cutting.<br>
&ensp;&ensp;* Tools cutting and working fine.<br>
2. To identify Current range for each conditions mentioned above.<br>
3. To identify timestamp for each conditions.<br>
4. Life prediction of CNC machine.<br>
5. Sending data to Real-time Database.<br>
</p>
<H1>Project Description</H1>
<p>This project focuses on using data analysis for predictive maintenance in CNC machines to forecast the Remaining Useful Life (RUL) of motors. By analyzing data collected from these machines, it is possible to detect potential motor failures early, enabling proactive maintenance and reducing costly unplanned downtime. This approach helps optimize production efficiency, minimize breakdowns, and ensure timely component replacements. The project aims to improve the overall reliability and performance of CNC machines through data-driven maintenance strategies.</p>
<h2>Flow Chart</h2>

![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/flow%20chart.png)

<h4>Flow chart Explanation:</h4>
<p>Collect data(I current in Amp) from database (csv datasheet).<br>
1. Check conditions as per current range:<br>
&ensp;&ensp;* Initial condition of Tools.<br>
&ensp;&ensp;* Tools rotating but not in cutting condition.<br>
&ensp;&ensp;* Tools in cutting and working condition i.e. Ideal condition.<br>
2. Check time required for each condition and notify the system.<br>
3. Calculate the total time required for machine from start to end.<br>
4. Check the total time span declared by the manufacturer and alert the user/system about time (RUL-Remaining Useful Life) utilized till date.<br>
5. Send all this data to the Firebase Real-time database.<br>
</p>

<h2>Screenshots</h2>
<h3>Code and Output</h3>

![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture1.jpg)
![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture2.jpg)
![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture3.jpg)
![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture4.jpg)

<h3>Database Connection to Firebase Realtime Database</h3>

![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture5.jpg)
![Alt text](https://github.com/JagtapNikhil/CNC-Tools-Life-Prediciton/blob/a76d77c8a99a90257f437d482a50010c19837cac/Screenshot/Picture6.jpg)

<h2>Conclusion</h2>
<p>According to the design proposed in the report we come to a conclusion that we are able to predict the lifespan of CNC machine tools. Also, we are able to save this data in the database and notify total use of each tool in each condition mentioned above and identify the remaining time stamp for each tool.</p>




