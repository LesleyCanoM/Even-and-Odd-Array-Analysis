<h1>Even and Odd Array Analysis - C++ Project</h1> 

<h2>Description</h2> 
This C++ program reads a series of integers from a file, separates them into even and odd groups, and analyzes each group independently. It calculates key statistics such as the highest and lowest values, the average, and lists numbers that are higher than the average. The results are outputted to three files: one for even numbers, one for odd numbers, and one summary file. This project demonstrates the use of arrays, functions, file I/O, and basic data analysis techniques.

<h2>Languages and Utilities Used</h2>
<b>C++</b><br/>
<b>Standard Library (iostream, fstream, iomanip)</b>

<h2>Environments Used</h2>
<b>Replit</b><br/>

<h2>Program Walk-through:</h2>

<p align="center">
<b>Step 1: Read data and separate into even and odd arrays</b><br/>
The program reads from an input file and stores even and odd numbers into separate arrays.<br/>
<img src="https://imgur.com/aYCPD9S.png" height="80%" width="80%" alt="Reading and Separating Data"/><br/><br/>

<b>Step 2: Calculate statistics</b><br/>
Each array is analyzed to find the highest, lowest, and average values.<br/>
<img src="https://imgur.com/eFb7cXT.png" height="80%" width="80%" alt="Statistics Calculation"/><br/><br/>

<b>Step 3: Output higher-than-average numbers</b><br/>
The program filters numbers greater than the average and outputs them to their respective files.<br/>
<img src="https://imgur.com/9Usqdlp.png" height="80%" width="80%" alt="Above Average Output"/><br/><br/>

<b>Step 4: Write summary of both sets</b><br/>
A final file includes summarized statistics for both even and odd numbers.<br/>
<img src="https://imgur.com/0GqP4Rp.png" height="80%" width="80%" alt="Summary Output"/>
</p>

<h2>Example Output</h2>

<b>Even Numbers File Output:</b><br/>
<pre>
Even numbers: 46 30 82 90 56 16 48 26 4 58 0 78 92 60 12 90 14 52 16 80 102 34 10 92 88 66 64 92 66 64 
Even Highest: 102
Even Lowest: 0
Even Average: 54.27
Higher than average: 82 90 56 58 78 92 60 90 80 102 92 88 66 64 92 66 64
</pre>

<b>Odd Numbers File Output:</b><br/>
<pre>
Odd numbers: 17 95 21 63 47 19 41 85 -9 71 79 51 95 79 95 61 89 63 39 5 
Odd Highest: 95
Odd Lowest: -9
Odd Average: 55.30
Higher than average: 95 63 85 71 79 95 79 95 61 89 63 
</pre>

<b>Summary Output:</b><br/>
<pre>
Even Numbers... High: 102, Low: 0, Average: 54.27
Odd Numbers... High: 95, Low: -9, Average: 55.30
</pre>
