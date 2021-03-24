# CryptocurrencyProgram
Program that shows data about cryptocurrencies values and related

The first thing I want to mention is that I am currently learning Python and this is one of my firts programs, so is probably that the code be inefficient or have some errors.

The first version (the one called Programa_v1) was created as a weekend project for a friend, who needed it ASAP, so I tried to get it work
and I didn't worry a lot about appearance or efficiency. The main problem is that it uses entries (Entry() class/method/instance (d.k.) of tkinter) for displaying the data. 
But it has an interesting feature, it colored the fields to get a quicker view of what is happening, making easier the understanding.

The second version (Programa_v2) incorporates two main changes. Replace the Entries for Labels and uses StringVar() class. Further, a search directory was added so you can change where the data is stored.

## Using the program
The folders have the .exe program. You can unzip it and create a direct access for execute it, or simply open that file.
Once opened, the procedure is as follows:

  You can load the data pressing "Actualizar valores" button. It will take a while (around 20 secs) and then it will display all the values.
  
  Only after loading the data at least one time, you can save these numbers into an Excel file (.xlsx)
  
  If you don't change anything, the default directory where the file is saved is the same where the program is.
  
  If you change the directory, you must create the excel file where you want to save the data. This is important because the program don't create the file,
  only edits it.
  
## Features
  The program shows the date and time in which the data was actualized.
  
  It uses data from Yahoo.com
  
  The Gosth Pivot is calculated as follows: GP=(Actual value + Day min value + Day max value)/3 (Average)
  
  The Pivot is calculated as P=((GP-Actual value)/GP)*100
  
  Lower the value, better chances of getting rewards :D
  
  Version 1 of the program shows the Pivot value in a range of colors from green to red. Lower pivot values, darker red. Higher the pivot value, darker the green.
  In the folders you can also access to an existing Excel file which contains a template of the program. Feel free to modify it.
  
## Considerations
  For version 2 it will be interesting add the color indicator to the labels that displays the Pivot value. Either changing the text color or the background of the label. 
  If you know how to do this, please tell me how or do it if you have the time :) I will really apreciate that.
  
  Any modifications, suggestions or comments about the program are helpful and welcome.
  
## Screenshots of the program running
Program_v1 (version 1) 

![image1](https://user-images.githubusercontent.com/65863634/112239640-9831a100-8c25-11eb-9614-35c612951d44.png)

Program_v2 (version 2)

![image2](https://user-images.githubusercontent.com/65863634/112239642-9962ce00-8c25-11eb-80ee-ac3364bdb5b4.png)

