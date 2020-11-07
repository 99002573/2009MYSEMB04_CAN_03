# Test plan 
|ID|    DESCRIPTION |  Precondition  | Expected Input | Expected Output | Actual output|
|---|---|---|---|---|---|
|T01_H_01|  When the Ignition is ON, the vehicle should start | Idle  | Start button is pressed | The vehicle functions turn on | As expected |
|T02_H_02|  When the gear trackbar is changed, it should be displayed in LCD | Ignition ON  | Varying Gear Trackbar | Gear LCD display | As expected |
|T01_H_03|  When the Accelerator trackbar is changed, it should be changed in Accelerator gauge | Ignition ON  | Varying Accelerator Trackbar | Accelerator Gauge changes | As expected |
|T01_H_04|  For the changes in Accelerator, the speedometer must change | Ignition ON  | Varying Accelerator Trackbar | Speedometer varying from 0 km/hr to 220 km/hr | As expected |
|T01_H_05|  Brake level changes | Ignition ON | Varying brake trackbar | 5 levels of brake varying from 0 to 5 | As expected |
|T01_H_06|  When the speed changes, the speed changes accordingly | Ignition ON and Engine running  | Varying Speed  | Fuel should decrease slowly when the ignition is On. when vehicle is moving Depending upon the speed fuel should decrease.  | As expected |
|T07_L_01|  When Gear is 1, the speed range is 0 – 20 kmph  | Ignition ON  | Varying Accelerator Trackbar | Speed: 0 – 20 kmph | As expected |
|T08_L_02|  When Gear is 2, the speed range is 0 – 50 kmph  | Ignition ON   | Varying Accelerator Trackbar | Speed: 0 – 20 kmph | As expected |
|T09_L_03|  When Gear is 1, the speed range is 0 – 80 kmph  | Ignition ON  | Varying Accelerator Trackbar | Speed: 0 – 80 kmph | As expected |
|T10_L_04|  When Gear is 1, the speed range is 0 – 140 kmph  | Ignition ON  | Varying Accelerator Trackbar | Speed: 0 – 140 kmph | As expected |
|T11_L_05|  When Gear is 1, the speed range is 0 – 220 kmph  | Ignition ON  | Varying Accelerator Trackbar | Speed: 0 – 220 kmph | As expected |
|T11_L_06|  Depending upon the brake level speed should decrease gradually.  | Ignition ON  | Varying speed | the brake level speed should decrease gradually | As expected |
|T11_L_07|  When School Zone button is pressed whatever maybe the speed, speed should limit to 40Km/hr and gear 3 till 500 meters | Ignition ON and TSI Feature ON  | School Zone Sign | Speed: 0 – 40 kmph for 2 km Gear: 3 | As expected |
|T11_L_08|  When speed limit 50 button is pressed speed should limit to 50Km/hr and gear 3 till 2 km | Ignition ON and TSI Feature ON  | Speed Limit 50 | Speed: 0 – 50 kmph for 2 km Gear: 3 | As expected |
|T11_L_09|  When speed limit 100 button is pressed speed should limit to 100Km/hr and gear 4 till 1.5km | Ignition ON and TSI Feature ON  | Speed Limit 100 | Speed: 0 – 100 kmph for 1.5 km Gear: 4 | As expected |
|T11_L_10|  When Gravel button is pressed speed should limit to 10Km/hr and gear 1 till 500m | Ignition ON and TSI Feature ON  | Gravel Sign | Speed: 0 – 10 kmph for 500m Gear: 1 | As expected |
|T11_L_11|  When Narrow Bridge button is pressed speed should limit to 30Km/hr and gear 2 till 1km | Ignition ON and TSI Feature ON  | Narrow Bridge Sign | Speed: 0 – 30 kmph for 1 km Gear: 2 | As expected |
|T11_L_12| When Turn left button is pressed left indicator should turn On and speed limit to 20Km/hr and gear 2 till 500 meters | Ignition ON and TSI Feature ON  | Turn Left Sign | Speed: 0 – 20 kmph for 500 m Gear: 2 | As expected |
|T11_L_13|  When turn right button is pressed right indicator should turn On and speed limit to 20Km/hr and gear 2 till 500 meters | Ignition ON and TSI Feature ON  | Turn Right Sign | Speed: 0 – 20 kmph for 500 m Gear: 2 | As expected |
|T11_L_14|  When animal crossing button is pressed speed limit should be limit to 10Km/hr and gear 2 till 1km | Ignition ON and TSI Feature ON  | Animal Crossing Sign | Speed: 0 – 10 kmph for 1 km Gear: 2 | As expected |
|T11_L_15|  When Traffic signal button is pressed speed should gradually decrease to 0Km/hr | Ignition ON and TSI Feature ON  | Traffic Signal Sign | Speed: 0 kmph Gear: 0 | As expected |
|T11_L_16|  When Fuel is in reserve and when filling station button is pressed vehicle should stop and fuel tank will be filled | Ignition ON and TSI Feature ON | Fuel Station Sign | Speed: 0 kmph Gear: 3 | As expected |
|T11_L_17|  When T-junction button is pressed speed should gradually decrease to 0 km/hr | Ignition ON and TSI Feature ON  | T-Junction Sign | Speed: 0 kmph 
Gear: 0 | As expected |
|T11_L_18|  When Slippery road button is pressed speed should limit to 50km/hr and gear 3 | Ignition ON and TSI Feature ON  | Slippery Road Sign | Speed: 0 – 50 kmph Gear: 3 | As expected |
|T11_L_19|  When Road Hump button is pressed speed should limit to 10km/hr and gear 1 | Ignition ON and TSI Feature ON  | Road Hump | Speed: 0 – 10 kmph 
Gear: 1 | As expected |
|T11_L_20|  When Y-junction button is pressed speed should gradually decrease to 0km/hr | Ignition ON and TSI Feature ON  | Y-Junction Sign | Speed: 0 kmph Gear: 0 | As expected |
