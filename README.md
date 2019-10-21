# ECE202A-Project: Safe Driving

## Abstract
Each year, hundreds of people fall victim to unsafe driving. In 2017 alone, distracted driving led to the deaths of 3166 people [1]. On the other hand, drowsy driving caused up to 800 deaths in a single year [2]. These statistics show an urgent need to improve driver safety. Although newer cars such as Teslas do have features to detect drowsiness using cameras and in-car sensors, this type of technology does not exist in older models, and as such is mostly inaccessible to the vast majority of the population, especially those that are financially unprivileged. Our solution is to use earables, a wearable wristband, and the user’s phone to cost effectively create safer driving practices in any car model. While driving, simple gestures such as shaking or tilting the head can be used to decline or accept calls, or to change songs on Spotify. These small changes can help to reduce distracted driving by keeping the driver focused on the road rather than on their phones. For drowsiness, the earables can be used to detect patterns of fatigue, while the wristband can keep track of their heart rate. If both inputs indicate drowsiness, the phone can then ask if the user wants to stop at a nearby coffee shop/rest area. The user can either accept or decline the new route by shaking his or her head. Hopefully, this solution will improve driver safety while being accessible to all drivers. 

## Past Work to Current Solution
There has been a lot of prior technology regarding distracted and drowsy driving. For distracted driving, there are several apps that can be used to block calls and incoming texts [3]. However, drivers might not want to use these apps in case the call is important. If drivers are still going to accept calls or change their songs while driving, the next best possible solution is to use a technology that can minimize these distractions. Earables can provide a solution to do so by allowing the driver to make these decisions without having to look directly at their phone or press a button. By using simple head gestures, the driver can perform these tasks with less risk. In the case of drowsy driving, many of these solutions require cameras or sensors integrated within the car. For example, one solution uses IR sensors embedded in the driver’s headrest to track their head position and determine if the driver is drowsy [4]. Other solutions for drowsy driving include using cameras to look at the driver’s blink rate or using the steering wheel to detect the driver’s movements [5]. This, however, would require expensive equipment and can be cumbersome to use. In one case, a research group from Hong Kong Baptist University uses the smartphone’s camera instead to look for signs of drowsiness. The only catch is that the smartphone’s camera must be in direct view of the driver’s face, which is usually inconvenient for the driver [6]. Our method will take advantage of analyzing a person’s head movements using the earables. Additionally, there have been several studies that show drowsiness is linked to changes in the heart rate [7][8]. Therefore, we will try to incorporate heart rate variability (HRV) as one of the inputs as well. This will be done using a wearable wristband to monitor the person’s heart rate. Furthermore, most past solutions use lights and sounds to notify the driver of their drowsy state. However, this might do little to get the driver off the road. With our solution, we hope to guide the driver to a safe location within a short amount of time. This will be done by providing the driver with the option to redirect their route to a nearby coffee shop. The choice is still up to the driver, but at least it provides a convenient option without the hassle of the driver having to do it themselves. 


## Project Timeline
* Week 5 - Learn how to use earables and wristband
* Week 6 - Implement gesture recognition for earables and heart rate sensing for wristband
* Week 7 - Get earables and wristband to interact with the phone, create midterm presentation
* Week 8 - Make the phone interact with apps such as Spotify and Google Maps
* Week 9 - Get the whole system working together
* Week 10 - Debug final project, work on final presentation

## Required Resources 
* Earables (two pairs just in case and if possible)
* Wearable wristband to detect heart rate (can be Hexiwear or the ones from the lab)
* Android phone (we only have one between the two of us)

## Sources
[1]  “Distracted Driving,” National Highway Traffic Safety Administration, April 2019.
<https://www.nhtsa.gov/risky-driving/distracted-driving>.

[2] “Drowsy Driving: Asleep at the Wheel,” Center for Disease Control and Prevention, November 2018. 
<https://www.cdc.gov/features/dsdrowsydriving/index.html>. 

[3]  Consumer Reports, “Technology That Can Reduce Driving Distractions and Their Dangers,” Consumer Reports, November 2017. 
<https://www.consumerreports.org/car-safety/technology-that-can-reduce-driving-distractions-dangers-car-safety-features/>.

[4] D. Lee, S. Oh, S. Heo and M. Hahn, "Drowsy Driving Detection Based on the Driver's Head Movement using Infrared Sensors," 2008 Second International Symposium on Universal Communication, Osaka, 2008, pp. 231-236.

[5] A. Sahayadhas, K. Sundaraj and M. Murugappan, “Detecting Driver Drowsiness Based on Sensors: A Review,” Sensors, 2012, pp. 16937-16953.

[6] Hong Kong Baptist University, "Smartphone app detects and alerts sleepy drivers." ScienceDaily, ScienceDaily, June 2017. 
<www.sciencedaily.com/releases/2017/06/170616121811.htm>.

[7] J. Vicente, P. Laguna, A. Bartra, and et al., “Drowsiness detection using heart rate variability,” Medical & Biological Engineering & Computing, 2016, vol. 54 pp. 927-927.

[8] S. Jo, J. Kim, and D. Kim, “Heart Rate Change While Drowsy Driving,” Journal of Korean Medical Science, 2019.



