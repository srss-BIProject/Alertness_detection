# Alertness_detection

   ## **PROBLEM STATEMENT**
   In India, there are a lot of accidents taking place every day due to mishaps. The no. of cars and accidents are increased as    the population grows. Most of the accidents take place due to people  feeling sleepy,high speed,drunk and drive.
   So,we are going to implement an accident prevention system which deals with the problem of accidents happening due to people    getting dozed off or feeling sleepy. 
   
   ## **IDEA**
   A system that can automatically detect driver drowsiness in a real time video stream and then play an alarm if the driver      appears to be drowsy.
   
   ## **WORKING**
   Program shows how to find frontal human faces in an image and estimate their pose. 
   The pose takes the form of 68 landmarks.These are points on the face such as the corners of the mouth, on the eyes, and so forth.
   
   [Landmarks on human face](shape.PNG)
   
   When Either no face is detected or the calculated aspect ratio is less than or equal to the threshold value, Nothing would      be displayed.
   When Mouth Aspect Ratio is greater than Mouth Threshold Value, Notification for ‘Yawning’ would be displayed.
   When Eyes Aspect Ratio is greater than Eyes Threshold Value, Notification for ‘Sleeping’ would be displayed. 
   When Eyes Aspect Ratio and Mouth Aspect Ratio are greater than Eyes Threshold Value and Mouth Threshold Value respectively,    Notifications for ‘Sleeping and Yawning’ would be displayed.
   
   //gaur--eyes vala part from research paper-image and formula we are using
   
   ## **DATASET**
   //link
   
   SNAPSHOP OF A PART OF DATASET
   
   
   
   // gaur ye snapshot ki pic dal pae to daal dio..m copy paste krke krri thi bt ni hora...
   
   Training a custom dlib shape predictor
<<images>
  <image file='lfpw/trainset/image_0457.png'>
    <box top='78' left='74' width='138' height='140'>
      <part name='00' x='55' y='141'/>
      <part name='01' x='59' y='161'/>
      <part name='02' x='66' y='182'/>
      <part name='03' x='75' y='197'/>
      <part name='04' x='90' y='209'/>
      <part name='05' x='108' y='220'/>
      <part name='06' x='131' y='226'/>
      <part name='07' x='149' y='232'/>
      <part name='08' x='167' y='230'/>
      <part name='09' x='181' y='225'/>
      <part name='10' x='184' y='208'/>
      <part name='11' x='186' y='193'/>
      <part name='12' x='185' y='179'/>
      <part name='13' x='184' y='167'/>
      <part name='14' x='186' y='152'/>
      <part name='15' x='185' y='142'/>
      <part name='16' x='181' y='133'/>
      <part name='17' x='95' y='128'/>
      <part name='18' x='105' y='121'/>
      <part name='19' x='117' y='117'/>
      <part name='20' x='128' y='115'/>
      <part name='21' x='141' y='116'/>
      <part name='22' x='156' y='115'/>
      <part name='23' x='162' y='110'/>
      <part name='24' x='169' y='108'/>
      <part name='25' x='175' y='108'/>
      <part name='26' x='180' y='109'/>
      <part name='27' x='152' y='127'/>
      <part name='28' x='157' y='136'/>
      <part name='29' x='162' y='145'/>
      <part name='30' x='168' y='154'/>
      <part name='31' x='152' y='166'/>
      <part name='32' x='158' y='166'/>
      <part name='33' x='163' y='168'/>
      <part name='34' x='167' y='166'/>
      <part name='35' x='171' y='164'/>
      <part name='36' x='111' y='134'/>
      <part name='37' x='116' y='130'/>
      <part name='38' x='124' y='128'/>
      <part name='39' x='129' y='130'/>
      <part name='40' x='125' y='134'/>
      <part name='41' x='118' y='136'/>
      <part name='42' x='161' y='127'/>
      <part name='43' x='166' y='123'/>
      <part name='44' x='173' y='122'/>
      <part name='45' x='176' y='125'/>
      <part name='46' x='173' y='129'/>
      <part name='47' x='167' y='129'/>
      <part name='48' x='139' y='194'/>
      <part name='49' x='151' y='186'/>
      <part name='50' x='159' y='180'/>
      <part name='51' x='163' y='182'/>
      <part name='52' x='168' y='180'/>
      <part name='53' x='173' y='183'/>
      <part name='54' x='176' y='189'/>
      <part name='55' x='174' y='193'/>
      <part name='56' x='170' y='197'/>
      <part name='57' x='165' y='199'/>
      <part name='58' x='160' y='199'/>
      <part name='59' x='152' y='198'/>
      <part name='60' x='143' y='194'/>
      <part name='61' x='159' y='186'/>
      <part name='62' x='163' y='187'/>
      <part name='63' x='168' y='186'/>
      <part name='64' x='174' y='189'/>
      <part name='65' x='168' y='191'/>
      <part name='66' x='164' y='192'/>
      <part name='67' x='160' y='192'/>
    </box>
  </image>

----------------------------------------------
   
