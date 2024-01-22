how to use the software:
the code for arduino can be found in loading arduino arm


for code in computer :
requirement 
python 3.11 (willnot run in 3.12)
jupyter notebook 
virtual env 

then do-
	activate the virtual env
	pip install (all required packages like cvzone ,numpy and Serial)

then run the code named  "handgesture.ipnyb" 

you need to press q for quiting the camera interface any other will not work 

the camera screen will hang if any of code produces error ,if hangs execute 
this command :
```
cap.release()
cv.destroyAllWindows()
```
for testing complexgesture.ipnyb and handgesture.ipnyb can be used ,to use on arduino you will use arduinogesture.ipnyb file

