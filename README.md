## Car_License_Plate_Detection
Used OpenCV to detect the License plates of a Car using the HaarCascade_russian_plate_number XMLfile

### Activities performed:
1. Import Required Libraries
2. Load the Image using the imreadfunction of OpenCV
3. Pre-process the Image

   a. Create a function to convert the image using cv2.Color(img, cv2.COLOR_BGR2RGB) function

   b. Display the image
4. Create a function for a classifier using the HaarCascade_russian_plate_number.xml file
5. Detect the Car License Platesusing the Classifier
6. Display the Results
