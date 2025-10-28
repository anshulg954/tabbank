This file contains detailed description about each of the dataset

---
# Energy: 

## 1. `Mercedes-Benz-Greener-Manufacturing`
- **Description:** Mercedes-Benz Greener Manufacturing - Can you cut the time a Mercedes-Benz spends on the test bench?
- **Source:** <a href="">https://www.kaggle.com/competitions/mercedes-benz-greener-manufacturing</a>
- **Task:** Regression
- **#Rows:** 4209
- **#Features:** 385
- **Target:** `y`
- **#Views:**  (as of Month x, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:**
- **Additional Description:** To ensure the safety and reliability of each and every unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. But, optimizing the speed of their testing system for so many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler’s production lines.

In this competition, Daimler is challenging Kagglers to tackle the curse of dimensionality and reduce the time that cars spend on the test bench. Competitors will work with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing. Winning algorithms will contribute to speedier testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.
- **Features:** <br>

## 2. `High Storage System Data for Energy Optimization`
- **Description:** Different datasets from correct running optimized system and runs with anomalies
- **Source:** <a href="">https://www.kaggle.com/datasets/inIT-OWL/high-storage-system-data-for-energy-optimization/</a>
- **Task:** Classification
- **#Rows:** 
- **#Features:** 19
- **Target:** `Labels`
- **#Views:**  32.9K (as of October 28, 2025)
- **#Downloads:**  2266 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** The high storage system consists of 4 short conveyor belts (BLO, BHL, BHR, BRU) and 2 rails (HR, HL). The two conveyor belts in the middle (BHL, BHR) can be moved in the vertical by the rails, the other ones are fixed and they all have a size of 64cm x 8.5cm x 29.7cm. Each conveyor belt has three induction sensors. The first one is 3.6cm from the left edge, the second one 26.6 cm from the left edge and the last sensor is 3.6cm from the right edge.

It uses a SPS with Codesys V3, which corresponds to IEC61131-Standard.

The high storage system transports one package between two spots, as you can see in this Video. The first run is the non-optimized run. The two conveyor belts in the middle are only moving vertical when they do not move the package horizontal. The second run is the optimized run. While the two conveyor belts in the middle are moving the package horizontal, they move vertical as well.

The generated data is split in four files. HRSS_normal_standard.csv contains normal runs without failures and not optimized.

HRSS_normal_optimized.csv containes optimized runs without failures.

HRSS_anomalous_standard.csv contains runs with failures and not optimized.

And HRSS_anomalous_optimized.csv contains optimized runs with failures.

The Label column in each file marks the rows with anomalies. With these files you can test energy based optimization processes by using the normal non-optimized and normal optimized files.
Furthermore you can test anomaly detection with the normal and anomaly files.
- **Features:** <br>

## 3. `Appliances Energy Prediction`
- **Description:** Appliances Energy Prediction - Experimental data used to create regression models of appliances energy use in a low energy building.
- **Source:** <a href="">https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction</a>
- **Task:** Regression
- **#Rows:** 19735
- **#Features:** 28
- **Target:** `rv1 and rv2`
- **#Views:**  69184 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 1
- **Additional Description:** The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters).
- **Features:** <br>
| Variable Name | Role    | Type        | Description | Units  | Missing Values |
|----------------|---------|-------------|--------------|--------|----------------|
| date           | Feature | Date        |              |        | no             |
| Appliances     | Target  | Integer     |              | Wh     | no             |
| lights         | Feature | Integer     |              | Wh     | no             |
| T1             | Feature | Continuous  |              | °C     | no             |
| RH_1           | Feature | Continuous  |              | %      | no             |
| T2             | Feature | Continuous  |              | °C     | no             |
| RH_2           | Feature | Continuous  |              | %      | no             |
| T3             | Feature | Continuous  |              | °C     | no             |
| RH_3           | Feature | Continuous  |              | %      | no             |
| T4             | Feature | Continuous  |              | °C     | no             |
| RH_4           | Feature | Continuous  |              | %      | no             |
| T5             | Feature | Continuous  |              | °C     | no             |
| RH_5           | Feature | Continuous  |              | %      | no             |
| T6             | Feature | Continuous  |              | °C     | no             |
| RH_6           | Feature | Continuous  |              | %      | no             |
| T7             | Feature | Continuous  |              | °C     | no             |
| RH_7           | Feature | Continuous  |              | %      | no             |
| T8             | Feature | Continuous  |              | °C     | no             |
| RH_8           | Feature | Continuous  |              | %      | no             |
| T9             | Feature | Continuous  |              | °C     | no             |
| RH_9           | Feature | Continuous  |              | %      | no             |
| T_out          | Feature | Continuous  |              | °C     | no             |
| Press_mm_hg    | Feature | Continuous  |              | mm Hg  | no             |
| RH_out         | Feature | Continuous  |              | %      | no             |
| Windspeed      | Feature | Continuous  |              | m/s    | no             |
| Visibility     | Feature | Continuous  |              | km     | no             |
| Tdewpoint      | Feature | Continuous  |              | °C     | no             |
| rv1            | Feature | Continuous  |              |        | no             |
| rv2            | Feature | Continuous  |              |        | no             |


## 4. `Combined Cycle Power Plant`
- **Description:** The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the plant was set to work with full load.
- **Source:** <a href="">https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant</a>
- **Task:** Regression
- **#Rows:** 9568
- **#Features:** 4
- **Target:** `PE`
- **#Views:**  47974 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 1
- **Additional Description:** The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE)  of the plant.
- **Features:** <br>
T - Temperature
AP - Ambient Pressure
RH - Relative Humidity
V - Exhaust Vacuum
PE - net hourly electrical energy output

## 5. `Energy Efficiency`
- **Description:** This study looked into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.
- **Source:** <a href="">https://archive.ics.uci.edu/dataset/242/energy+efficiency</a>
- **Task:** Regression
- **#Rows:** 768
- **#Features:** 8
- **Target:** `Y1 and Y2`
- **#Views:**  94182 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 3
- **Additional Description:** We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.
- **Features:** <br>
| Variable Name | Role    | Type        | Description               | Units | Missing Values |
|----------------|---------|-------------|----------------------------|--------|----------------|
| X1             | Feature | Continuous  | Relative Compactness       |        | no             |
| X2             | Feature | Continuous  | Surface Area               |        | no             |
| X3             | Feature | Continuous  | Wall Area                  |        | no             |
| X4             | Feature | Continuous  | Roof Area                  |        | no             |
| X5             | Feature | Continuous  | Overall Height             |        | no             |
| X6             | Feature | Integer     | Orientation                |        | no             |
| X7             | Feature | Continuous  | Glazing Area               |        | no             |
| X8             | Feature | Integer     | Glazing Area Distribution  |        | no             |
| Y1             | Target  | Continuous  | Heating Load               |        | no             |
| Y2             | Target  | Continuous  | Cooling Load               |        | no             |


## 6. `Steel_industry_data`
- **Description:** Steel Industry Energy Consumption - The data is collected from a smart small-scale steel industry in South Korea.
- **Source:** <a href="">https://archive.ics.uci.edu/dataset/851/steel+industry+energy+consumption</a>
- **Task:** Regression
- **#Rows:** 35040
- **#Features:** 9
- **Target:** `Load_Type`
- **#Views:**  25544 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 1
- **Additional Description:** The information gathered is from the DAEWOO Steel Co. Ltd in Gwangyang, South Korea. It produces several types of coils, steel plates, and iron plates. The information on electricity consumption is held in a cloud-based system. The information on energy consumption of the industry is stored on the website of the Korea Electric Power Corporation (pccs.kepco.go.kr), and the perspectives on daily, monthly, and annual data are calculated and shown.
- **Features:** <br>
| Variable Name                          | Role   | Type         | Description                          | Units | Missing Values |
|----------------------------------------|--------|--------------|--------------------------------------|--------|----------------|
| date                                   | Other  | Date         |                                      |        | no             |
| Usage_kWh                              | Feature| Continuous   | Industry Energy Consumption          | kWh    | no             |
| Lagging_Current_Reactive.Power_kVarh   | Feature| Continuous   |                                      | kVarh  | no             |
| Leading_Current_Reactive_Power_kVarh   | Feature| Continuous   |                                      | kVarh  | no             |
| CO2(tCO2)                              | Feature| Continuous   |                                      | ppm    | no             |
| Lagging_Current_Power_Factor           | Feature| Continuous   |                                      | %      | no             |
| Leading_Current_Power_Factor           | Feature| Continuous   |                                      | %      | no             |
| NSM                                   | Feature| Integer      |                                      | s      | no             |
| WeekStatus                            | Feature| Categorical  | Weekend (0) or a Weekday (1)         |        | no             |
| Day_of_week                           | Feature| Categorical  | Sunday, Monday, ..., Saturday         |        | no             |
| Load_Type                             | Target | Categorical  | Light Load, Medium Load, Maximum Load |        | no             |


## 7. `Large-scale Wave Energy Farm`
- **Description:** The dataset includes 4 CSV files for 49 and 100 wave energy converters based on Perth and Sydney wave scenarios. The main goal is predicting the total power output of the wave farm based on the coordination of WECs (X1, Y1, X2, Y2,..., Xn, Yn). As the second plan, predicting the power output of each converter in the wave farm can be interesting. 
- **Source:** <a href="">https://archive.ics.uci.edu/dataset/882/large-scale+wave+energy+farm</a>
- **Task:** Regression
- **#Rows:** 63600
- **#Features:** 149
- **Target:** `Total_Power`
- **#Views:**  22056 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 1
- **Additional Description:** Wave energy is a rapidly advancing and promising renewable energy source that holds great potential for addressing the challenges of global warming and climate change. However, optimizing energy output in large wave farms presents a complex problem due to the expensive calculations required to account for hydrodynamic interactions between wave energy converters (WECs). Developing a fast and accurate surrogate model is crucial to overcome these challenges. In light of this, we have compiled an extensive WEC dataset that includes 54,000 and 9,600 configurations involving 49 and 100 WECs, coordination, power, q-factor, and total farm power output. The dataset was derived from a study published at the GECCO conference and received the prestigious Best Paper award. We want to acknowledge the support of the University of Adelaide Phoenix HPC service in conducting this research. For more details, please refer to the following link: https://dl.acm.org/doi/abs/10.1145/3377930.3390235.
- **Features:** <br>
| Variable Name | Role    | Type     | Description | Units | Missing Values |
|----------------|---------|----------|--------------|--------|----------------|
| X1             | Feature | Integer  |              |        | no             |
| Y1             | Feature | Integer  |              |        | no             |
| X2             | Feature | Integer  |              |        | no             |
| Y2             | Feature | Integer  |              |        | no             |
| X3             | Feature | Integer  |              |        | no             |
| Y3             | Feature | Integer  |              |        | no             |
| X4             | Feature | Integer  |              |        | no             |
| Y4             | Feature | Integer  |              |        | no             |
| X5             | Feature | Integer  |              |        | no             |
| Y5             | Feature | Integer  |              |        | no             |
| X6             | Feature | Integer  |              |        | no             |
| Y6             | Feature | Integer  |              |        | no             |
| X7             | Feature | Integer  |              |        | no             |
| Y7             | Feature | Integer  |              |        | no             |
| X8             | Feature | Integer  |              |        | no             |
| Y8             | Feature | Integer  |              |        | no             |
| X9             | Feature | Integer  |              |        | no             |
| Y9             | Feature | Integer  |              |        | no             |
| X10            | Feature | Integer  |              |        | no             |
| Y10            | Feature | Integer  |              |        | no             |
| X11            | Feature | Integer  |              |        | no             |
| Y11            | Feature | Integer  |              |        | no             |
| X12            | Feature | Integer  |              |        | no             |
| Y12            | Feature | Integer  |              |        | no             |
| X13            | Feature | Integer  |              |        | no             |
| Y13            | Feature | Integer  |              |        | no             |
| X14            | Feature | Integer  |              |        | no             |
| Y14            | Feature | Integer  |              |        | no             |
| X15            | Feature | Integer  |              |        | no             |
| Y15            | Feature | Integer  |              |        | no             |
| X16            | Feature | Integer  |              |        | no             |
| Y16            | Feature | Integer  |              |        | no             |
| X17            | Feature | Integer  |              |        | no             |
| Y17            | Feature | Integer  |              |        | no             |
| X18            | Feature | Integer  |              |        | no             |
| Y18            | Feature | Integer  |              |        | no             |
| X19            | Feature | Integer  |              |        | no             |
| Y19            | Feature | Integer  |              |        | no             |
| X20            | Feature | Integer  |              |        | no             |
| Y20            | Feature | Integer  |              |        | no             |
| X21            | Feature | Integer  |              |        | no             |
| Y21            | Feature | Integer  |              |        | no             |
| X22            | Feature | Integer  |              |        | no             |
| Y22            | Feature | Integer  |              |        | no             |
| X23            | Feature | Integer  |              |        | no             |
| Y23            | Feature | Integer  |              |        | no             |
| X24            | Feature | Integer  |              |        | no             |
| Y24            | Feature | Integer  |              |        | no             |
| X25            | Feature | Integer  |              |        | no             |
| Y25            | Feature | Integer  |              |        | no             |
| X26            | Feature | Integer  |              |        | no             |
| Y26            | Feature | Integer  |              |        | no             |
| X27            | Feature | Integer  |              |        | no             |
| Y27            | Feature | Integer  |              |        | no             |
| X28            | Feature | Integer  |              |        | no             |
| Y28            | Feature | Integer  |              |        | no             |
| X29            | Feature | Integer  |              |        | no             |
| Y29            | Feature | Integer  |              |        | no             |
| X30            | Feature | Integer  |              |        | no             |
| Y30            | Feature | Integer  |              |        | no             |
| X31            | Feature | Integer  |              |        | no             |
| Y31            | Feature | Integer  |              |        | no             |
| X32            | Feature | Integer  |              |        | no             |
| Y32            | Feature | Integer  |              |        | no             |
| X33            | Feature | Integer  |              |        | no             |
| Y33            | Feature | Integer  |              |        | no             |
| X34            | Feature | Integer  |              |        | no             |
| Y34            | Feature | Integer  |              |        | no             |
| X35            | Feature | Integer  |              |        | no             |
| Y35            | Feature | Integer  |              |        | no             |
| X36            | Feature | Integer  |              |        | no             |
| Y36            | Feature | Integer  |              |        | no             |
| X37            | Feature | Integer  |              |        | no             |
| Y37            | Feature | Integer  |              |        | no             |
| X38            | Feature | Integer  |              |        | no             |
| Y38            | Feature | Integer  |              |        | no             |
| X39            | Feature | Integer  |              |        | no             |
| Y39            | Feature | Integer  |              |        | no             |
| X40            | Feature | Integer  |              |        | no             |
| Y40            | Feature | Integer  |              |        | no             |
| X41            | Feature | Integer  |              |        | no             |
| Y41            | Feature | Integer  |              |        | no             |
| X42            | Feature | Integer  |              |        | no             |
| Y42            | Feature | Integer  |              |        | no             |
| X43            | Feature | Integer  |              |        | no             |
| Y43            | Feature | Integer  |              |        | no             |
| X44            | Feature | Integer  |              |        | no             |
| Y44            | Feature | Integer  |              |        | no             |
| X45            | Feature | Integer  |              |        | no             |
| Y45            | Feature | Integer  |              |        | no             |
| X46            | Feature | Integer  |              |        | no             |
| Y46            | Feature | Integer    |              |        | no             |
| X47            | Feature | Integer    |              |        | no             |
| Y47            | Feature | Integer    |              |        | no             |
| X48            | Feature | Integer    |              |        | no             |
| Y48            | Feature | Integer    |              |        | no             |
| X49            | Feature | Integer    |              |        | no             |
| Y49            | Feature | Integer    |              |        | no             |
| Power1         | Feature | Continuous |              |        | no             |
| Power2         | Feature | Continuous |              |        | no             |
| Power3         | Feature | Continuous |              |        | no             |
| Power4         | Feature | Continuous |              |        | no             |
| Power5         | Feature | Continuous |              |        | no             |
| Power6         | Feature | Continuous |              |        | no             |
| Power7         | Feature | Continuous |              |        | no             |
| Power8         | Feature | Continuous |              |        | no             |
| Power9         | Feature | Continuous |              |        | no             |
| Power10        | Feature | Continuous |              |        | no             |
| Power11        | Feature | Continuous |              |        | no             |
| Power12        | Feature | Continuous |              |        | no             |
| Power13        | Feature | Continuous |              |        | no             |
| Power14        | Feature | Continuous |              |        | no             |
| Power15        | Feature | Continuous |              |        | no             |
| Power16        | Feature | Continuous |              |        | no             |
| Power17        | Feature | Continuous |              |        | no             |
| Power18        | Feature | Continuous |              |        | no             |
| Power19        | Feature | Continuous |              |        | no             |
| Power20        | Feature | Continuous |              |        | no             |
| Power21        | Feature | Continuous |              |        | no             |
| Power22        | Feature | Continuous |              |        | no             |
| Power23        | Feature | Continuous |              |        | no             |
| Power24        | Feature | Continuous |              |        | no             |
| Power25        | Feature | Continuous |              |        | no             |
| Power26        | Feature | Continuous |              |        | no             |
| Power27        | Feature | Continuous |              |        | no             |
| Power28        | Feature | Continuous |              |        | no             |
| Power29        | Feature | Continuous |              |        | no             |
| Power30        | Feature | Continuous |              |        | no             |
| Power31        | Feature | Continuous |              |        | no             |
| Power32        | Feature | Continuous |              |        | no             |
| Power33        | Feature | Continuous |              |        | no             |
| Power34        | Feature | Continuous |              |        | no             |
| Power35        | Feature | Continuous |              |        | no             |
| Power36        | Feature | Continuous |              |        | no             |
| Power37        | Feature | Continuous |              |        | no             |
| Power38        | Feature | Continuous |              |        | no             |
| Power39        | Feature | Continuous |              |        | no             |
| Power40        | Feature | Continuous |              |        | no             |
| Power41        | Feature | Continuous |              |        | no             |
| Power42        | Feature | Continuous |              |        | no             |
| Power43        | Feature | Continuous |              |        | no             |
| Power44        | Feature | Continuous |              |        | no             |
| Power45        | Feature | Continuous |              |        | no             |
| Power46        | Feature | Integer    |              |        | no             |
| Power47        | Feature | Continuous |              |        | no             |
| Power48        | Feature | Continuous |              |        | no             |
| Power49        | Feature | Continuous |              |        | no             |
| qW             | Feature | Continuous |              |        | no             |
| Total_Power    | Target | Continuous |              |        | no             |



## 8. `pirvision_office_dataset1`
- **Description:** PIRvision_FoG_presence_detection - The PIRvision dataset contains occupancy detection data collected from a Synchronized Low-Energy Electronically-chopped Passive Infra-Red sensing node in residential and office environments. Each observation represents 4 seconds of recorded human activity within the sensor Field-of-View (FoV).
- **Source:** <a href=""></a>
- **Task:** Classification
- **#Rows:** 15302
- **#Features:** 59
- **Target:** ``
- **#Views:**  6986 (as of October 28, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:** 1
- **Additional Description:**
- **Features:** <br>
| Variable Name  | Role    | Type        | Description  | Units  | Missing Values |
|----------------|---------|------------ |--------------|--------|----------------|
| Date           | Feature | Categorical |              |        | no             |
| Time           | Feature | Categorical |              |        | no             |
| Label          | Target  | Binary      |              |        | no             |
| Temperature_F  | Feature | Integer     |              |        | no             |
| PIR_1          | Feature | Integer     |              |        | no             |
| PIR_2          | Feature | Integer     |              |        | no             |
| PIR_3          | Feature | Integer     |              |        | no             |
| PIR_4          | Feature | Integer     |              |        | no             |
| PIR_5          | Feature | Integer     |              |        | no             |
| PIR_6          | Feature | Integer     |              |        | no             |
| PIR_7          | Feature | Integer     |              |        | no             |
| PIR_8          | Feature | Integer     |              |        | no             |
| PIR_9          | Feature | Integer     |              |        | no             |
| PIR_10         | Feature | Integer     |              |        | no             |
| PIR_11         | Feature | Integer     |              |        | no             |
| PIR_12         | Feature | Integer     |              |        | no             |
| PIR_13         | Feature | Integer     |              |        | no             |
| PIR_14         | Feature | Integer     |              |        | no             |
| PIR_15         | Feature | Integer     |              |        | no             |
| PIR_16         | Feature | Integer     |              |        | no             |
| PIR_17         | Feature | Integer     |              |        | no             |
| PIR_18         | Feature | Integer     |              |        | no             |
| PIR_19         | Feature | Integer     |              |        | no             |
| PIR_20         | Feature | Integer     |              |        | no             |
| PIR_21         | Feature | Integer     |              |        | no             |
| PIR_22         | Feature | Integer     |              |        | no             |
| PIR_23         | Feature | Integer     |              |        | no             |
| PIR_24         | Feature | Integer     |              |        | no             |
| PIR_25         | Feature | Integer     |              |        | no             |
| PIR_26         | Feature | Integer     |              |        | no             |
| PIR_27         | Feature | Integer     |              |        | no             |
| PIR_28         | Feature | Integer     |              |        | no             |
| PIR_29         | Feature | Integer     |              |        | no             |
| PIR_30         | Feature | Integer     |              |        | no             |
| PIR_31         | Feature | Integer     |              |        | no             |
| PIR_32         | Feature | Integer     |              |        | no             |
| PIR_33         | Feature | Integer     |              |        | no             |
| PIR_34         | Feature | Integer     |              |        | no             |
| PIR_35         | Feature | Integer     |              |        | no             |
| PIR_36         | Feature | Integer     |              |        | no             |
| PIR_37         | Feature | Integer     |              |        | no             |
| PIR_38         | Feature | Integer     |              |        | no             |
| PIR_39         | Feature | Integer     |              |        | no             |
| PIR_40         | Feature | Integer     |              |        | no             |
| PIR_41         | Feature | Integer     |              |        | no             |
| PIR_42         | Feature | Integer     |              |        | no             |
| PIR_43         | Feature | Integer     |              |        | no             |
| PIR_44         | Feature | Integer     |              |        | no             |
| PIR_45         | Feature | Integer     |              |        | no             |
| PIR_46         | Feature | Integer     |              |        | no             |
| PIR_47         | Feature | Integer     |              |        | no             |
| PIR_48         | Feature | Integer     |              |        | no             |
| PIR_49         | Feature | Integer     |              |        | no             |
| PIR_50         | Feature | Integer     |              |        | no             |
| PIR_51         | Feature | Integer     |              |        | no             |
| PIR_52         | Feature | Integer     |              |        | no             |
| PIR_53         | Feature | Integer     |              |        | no             |
| PIR_54         | Feature | Integer     |              |        | no             |
| PIR_55         | Feature | Integer     |              |        | no             |

## 9. `energy_data`
- **Description:** Energy Consumption Dataset - Linear Regression - Energy Consumption Prediction Dataset with Building Features and Environmental Features
- **Source:** <a href="">https://www.kaggle.com/datasets/govindaramsriram/energy-consumption-dataset-linear-regression</a>
- **Task:** Regression
- **#Rows:** 1000
- **#Features:** 6 
- **Target:** `Energy Consumption`
- **#Views:**  27.2K (as of October 28, 2025)
- **#Downloads:** 7987 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is designed for predicting energy consumption based on various building features and environmental factors. It contains data for multiple building types, square footage, the number of occupants, appliances used, average temperature, and the day of the week. The goal is to build a predictive model to estimate energy consumption using these attributes.

The dataset can be used for training machine learning models such as linear regression to forecast energy needs based on the building's characteristics. This is useful for understanding energy demand patterns and optimizing energy consumption in different building types and environmental conditions.
- **Features:** <br>
Building Type - Categorical feature representing the type of building.
Square Footage - Numeric feature representing the total square footage of the building.
Number of Occupants - Numeric feature indicating the number of people occupying the building.
Appliances Used - Numeric feature representing the number of appliances used in the building.
Average Temperature - Numeric feature representing the average temperature of the building or climate area (in Celsius).
Day of Week - Categorical feature representing whether the data point corresponds to a weekday or weekend.
Energy Consumption - Numeric target variable representing the energy consumption of the building in kWh (kilowatt-hours).

## 10. `Dataset of Distribution Transformers at Cauca Department (Colombia)`
- **Description:** Dataset contains 16.000 electric power distribution transformers from Cauca Department (Colombia).
They are distributed in rural and urban areas of 42 municipalities. The information covers
2019 and 2020 years, has 6 categorical variables and 5 continuous variables. First ones correspond to:
location, self-protected, removable connector, criticality according to ceraunic level, client and
installation type. Second ones are transformer power, burn rate, users number, unsupplied electricity
and secondary lines length.
- **Source:** <a href="">https://data.mendeley.com/datasets/yzyj46xpmy/4</a>
- **Task:** Classification
- **#Rows:** 
- **#Features:** 15
- **Target:** `Burned transformers 2019` and `Burned transformers 2020`
- **#Views:**  2727 (as of October 28, 2025)
- **#Downloads:**  808 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:**
- **Features:** <br>

## 11. `Wind Turbine Scada Dataset`
- **Description:** Wind Turbine Scada Dataset - 2018 Scada Data of a Wind Turbine in Turkey
- **Source:** <a href="">https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset</a>
- **Task:** Regression
- **#Rows:** 50530
- **#Features:** 4
- **Target:** `LV ActivePower (kW)`
- **#Views:**  188K (as of October 28, 2025)
- **#Downloads:**  21.4K (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** In Wind Turbines, Scada Systems measure and save data's like wind speed, wind direction, generated power etc. for 10 minutes intervals. This file was taken from a wind turbine's scada system that is working and generating power in Turkey.
- **Features:** <br>
Date/Time: (for 10 minutes intervals)
LV ActivePower (kW): The power generated by the turbine for that moment
Wind Speed (m/s): The wind speed at the hub height of the turbine (the wind speed that turbine use for electricity generation)
Theoretical_Power_Curve (KWh): The theoretical power values that the turbine generates with that wind speed which is given by the turbine manufacturer
Wind Direction (°): The wind direction at the hub height of the turbine (wind turbines turn to this direction automaticly)

## 12. `energy_efficiency_data`
- **Description:** Energy Efficiency Data Set - Assessing the energy efficiency as a function of building parameters.
- **Source:** <a href="">https://www.kaggle.com/datasets/ujjwalchowdhury/energy-efficiency-data-set</a>
- **Task:** Regression
- **#Rows:** 768
- **#Features:** 8
- **Target:** `Heating_Load` and `Cooling_Load`
- **#Views:**  50.3K (as of October 28, 2025)
- **#Downloads:**  7877 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** Abstract: This study looked into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.

We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.
- **Features:** <br>
Features:
-Relative_Compactness
-Surface_Area
-Wall_Area
-Roof_Area
-Overall_Height
-Orientation
-Glazing_Area
-Glazing_Area_Distribution
Predict:
Heating_Load
Cooling_Load

## 13. `Energy_consumption`
- **Description:** Energy-consumption-prediction - Predict the Energy Consumption
- **Source:** <a href="">https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction</a>
- **Task:** Regression
- **#Rows:** 1000
- **#Features:** 10
- **Target:** `EnergyConsumption`
- **#Views:**  31.8K (as of Month x, 2025)
- **#Downloads:**  6873 (as of Month x, 2025)
- **#Citations:**
- **Additional Description:** This dataset encapsulates a diverse array of features, including temperature, humidity, occupancy, HVAC and lighting usage, renewable energy contributions, and more. Each timestamp provides a snapshot of a hypothetical environment, allowing for in-depth analysis and modeling of energy consumption behaviors. Dive into the nuances of this synthetic dataset, designed to emulate real-world scenarios, and unravel the complexities that influence energy usage. Whether you are delving into predictive modeling or honing your data analysis skills, this dataset offers a dynamic playground for experimentation and discovery.
- **Features:** <br>
Timestamp - The chronological record of each data point, providing a time-based context.
Temperature - Randomly generated values representing ambient temperatures in degrees Celsius.
Humidity - Randomly generated values reflecting the humidity level as a percentage.
SquareFootage - Simulated values representing the size of the environment in square footage.
Occupancy - Randomly generated integer values indicating the number of occupants.
HVACUsage - Categorical variable denoting the HVAC system's operational state ('On' or 'Off').
LightingUsage - Categorical variable indicating the lighting system's operational state ('On' or 'Off').
RenewableEnergy - Randomly generated values representing the contribution of renewable energy sources as a percentage.
DayOfWeek - Categorical variable indicating the day of the week.
Holiday - Categorical variable denoting whether the day is a holiday ('Yes' or 'No')
EnergyConsumption - Simulated values representing energy consumption, calculated based on a simplified formula incorporating

## 14. `energy_dataset`
- **Description:** Hourly energy demand generation - Electrical demand, generation by type and prices in Spain.
- **Source:** <a href="">https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather</a>
- **Task:** Regression
- **#Rows:** 35064
- **#Features:** 24
- **Target:** `forecast solar day ahead`, `forecast wind offshore eday ahead`, `forecast wind onshore day ahead`, `total load forecast`, `price day ahead`
- **#Views:**  220K (as of October 28, 2025)
- **#Downloads:**  37.7K (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset contains 4 years of electrical consumption, generation, pricing, and weather data for Spain. Consumption and generation data was retrieved from ENTSOE a public portal for Transmission Service Operator (TSO) data. Settlement prices were obtained from the Spanish TSO Red Electric España. 
- **Features:** <br>
Time - Datetime index localized to CET
generation biomass - biomass generation in MW
generation fossil brown coal/lignite - coal/lignite generation in MW
generation fossil coal-derived gas - coal gas generation in MW
generation fossil gas - gas generation in MW
generation fossil hard coal - coal generation in MW
generation fossil oil - oil generation in MW
generation fossil oil sale - sale oil generation in MW
generation fossil peat - peat generation in MW
generation geothermal - geothermal generation in MW
generation hydro pumped storage aggregated - hydro1 generation in MW
generation hydro pumped storage consumption - hydro2 generation in MW
generation hydro run-of-river and poundage - hydro3 generation in MW
generation hydro water reservoir - hydro4 generation in MW
generation marine - sea generation in MW
generation nuclear - nuclear generation in MW
generation other - other generation in MW
generation other renewable - other renewable generation in MW
generation solar - solar generation in MW
generation waste - waste generation in MW
generation wind offshore - wind offshore generation in MW
generation wind onshore - wind onshore generation in MW
forecast solar day ahead - forecasted solar generation
forecast wind offshore eday ahead - forecasted offshore wind generation
forecast wind onshore day ahead - forecasted onshore wind generation
total load forecast - forecasted electrical demand
total load actual - actual electrical demand
price day ahead - forecasted price EUR/MWh
price actual - price in EUR/MWh

## 15. `global-data-on-sustainable-energy`
- **Description:** Global Data on Sustainable Energy (2000-2020) - Explore 20-year Insights on Sustainable Energy
- **Source:** <a href="">https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy</a>
- **Task:** Regression
- **#Rows:** 3650
- **#Features:** 20
- **Target:** `Value_co2_emissions`
- **#Views:**  124K (as of October 28, 2025)
- **#Downloads:**  25.4K (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** Uncover this dataset showcasing sustainable energy indicators and other useful factors across all countries from 2000 to 2020. Dive into vital aspects such as electricity access, renewable energy, carbon emissions, energy intensity, Financial flows, and economic growth. Compare nations, track progress towards Sustainable Development Goal 7, and gain profound insights into global energy consumption patterns over time.
- **Features:** <br>
Entity: The name of the country or region for which the data is reported.
Year: The year for which the data is reported, ranging from 2000 to 2020.
Access to electricity (% of population): The percentage of population with access to electricity.
Access to clean fuels for cooking (% of population): The percentage of the population with primary reliance on clean fuels.
Renewable-electricity-generating-capacity-per-capita: Installed Renewable energy capacity per person
Financial flows to developing countries (US $): Aid and assistance from developed countries for clean energy projects.
Renewable energy share in total final energy consumption (%): Percentage of renewable energy in final energy consumption.
Electricity from fossil fuels (TWh): Electricity generated from fossil fuels (coal, oil, gas) in terawatt-hours.
Electricity from nuclear (TWh): Electricity generated from nuclear power in terawatt-hours.
Electricity from renewables (TWh): Electricity generated from renewable sources (hydro, solar, wind, etc.) in terawatt-hours.
Low-carbon electricity (% electricity): Percentage of electricity from low-carbon sources (nuclear and renewables).
Primary energy consumption per capita (kWh/person): Energy consumption per person in kilowatt-hours.
Energy intensity level of primary energy (MJ/$2011 PPP GDP): Energy use per unit of GDP at purchasing power parity.
Value_co2_emissions (metric tons per capita): Carbon dioxide emissions per person in metric tons.
Renewables (% equivalent primary energy): Equivalent primary energy that is derived from renewable sources.
GDP growth (annual %): Annual GDP growth rate based on constant local currency.
GDP per capita: Gross domestic product per person.
Density (P/Km2): Population density in persons per square kilometer.
Land Area (Km2): Total land area in square kilometers.
Latitude: Latitude of the country's centroid in decimal degrees.
Longitude: Longitude of the country's centroid in decimal degrees.

## 16. `smart_meter_data`
- **Description:** Smart Meter Electricity Consumption Dataset - Includes weather conditions, historical consumption, and anomaly labels.
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/smart-meter-electricity-consumption-dataset</a>
- **Task:** Classification
- **#Rows:** 5000
- **#Features:** 6
- **Target:** `Anomaly Label`
- **#Views:**  5099 (as of October 28, 2025)
- **#Downloads:**  877 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset contains smart meter electricity consumption data enriched with weather conditions, historical consumption statistics, and anomaly labels for detecting unusual electricity usage patterns. It is designed for anomaly detection, predictive modeling, and energy consumption analysis using advanced machine learning techniques.
- **Features:** <br>
Timestamp: 30-minute interval electricity consumption records.
Electricity Consumed (kWh): Power usage per time interval.
Temperature (°C): External temperature affecting consumption.
Humidity (%): Air humidity levels.
Wind Speed (km/h): Wind conditions influencing energy needs.
Avg Past Consumption (kWh): Rolling average of past power usage.
Anomaly Label: Normal or abnormal usage, detected using Isolation Forest.

## 17. `powerdemand_5min_2021_to_2024_with weather`
- **Description:** Delhi 5-Minute Electricity Demand for Forecasting - 5-Minute Interval Data for Electricity Demand Forecasting in Delhi
- **Source:** <a href="">https://www.kaggle.com/datasets/yug201/delhi-5-minute-electricity-demand-for-forecasting</a>
- **Task:** Regression
- **#Rows:** 393440
- **#Features:** 14
- **Target:** `Power demand`
- **#Views:**  1566 (as of October 28, 2025)
- **#Downloads:**  358 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset provides a comprehensive record of electricity demand in Delhi, India, at 5-minute intervals, alongside key weather parameters. Covering the period from January 2021 to December 2024, the dataset is designed to facilitate forecasting models and analysis of energy demand patterns influenced by weather conditions.
- **Features:** <br>
datetime: Timestamp of the observation in YYYY-MM-DD HH:mm:ss format.
Power demand: Electricity demand (in kW) recorded every 5 minutes.
temp: Temperature (°C).
dwpt: Dew point temperature (°C).
rhum: Relative humidity (%).
wdir: Wind direction (degrees).
wspd: Wind speed (m/s).
pres: Atmospheric pressure (hPa).
year, month, day, hour, minute: Breakdown of the timestamp for easy time-series analysis.
moving_avg_3: 3-time-step moving average of power demand.

## 18. `PV_EV_Charging_Dataset`
- **Description:** Microgrid PV-EV Charging Dataset - Real-time energy control data for optimizing EV charging in a smart grid
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/microgrid-pv-ev-charging-dataset</a>
- **Task:** Classification
- **#Rows:** 1000
- **#Features:** 19
- **Target:** `Energy_Efficiency`
- **#Views:**  1620 (as of October 28, 2025)
- **#Downloads:**  325 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is designed for research and development in demand-side energy management for a microgrid-connected PV-EV charging system. It contains real-time data representing solar power generation, EV charging parameters, microgrid load, and energy efficiency optimization.
- **Features:** <br>
PV System Features (Solar Energy Generation)
Solar_Power_Generation_kW – Power generated by the PV system (kW)
Solar_Irradiance_Wm2 – Solar radiation intensity (W/m²)
Battery_Storage_Capacity_kWh – Storage capacity of the battery (kWh)
Battery_SOC_% – Current battery state of charge (%)
EV Charging Station Features
Number_of_EVs_Charging – Number of electric vehicles charging at the station
Charging_Power_per_EV_kW – Charging power per EV (kW)
Charging_Duration_min – Charging duration for EVs (minutes)
EV_Battery_SOC_Before_% – EV battery state of charge before charging (%)
EV_Battery_SOC_After_% – EV battery state of charge after charging (%)
Charging_Mode – Fast or slow charging mode
Microgrid Load Features
Grid_Energy_Supply_kW – Energy supplied by the grid (kW)
Demand_Side_Load_kW – Total energy demand from residential & business loads (kW)
Peak_Load_kW – Maximum power demand during peak hours (kW)
Off_Peak_Load_kW – Power demand during off-peak hours (kW)
Energy_Cost_per_kWh – Energy cost per unit (USD/kWh)
Control & Optimization Features
Demand_Response_Event – Whether a demand response event occurred (0 = No, 1 = Yes)
Predicted_Energy_Demand_kW – Predicted power demand based on current usage (kW)
Optimal_Charging_Schedule – Whether the charging schedule was optimized (0 = No, 1 = Yes)
Load_Balancing_Action – Whether a load balancing action was taken (0 = No, 1 = Yes)
Target Variable
Energy_Efficiency – 1 (Efficient charging), 0 (Inefficient charging)

## 19. `power_grid_dataset`
- **Description:** 
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/power-grid</a>
- **Task:** 
- **#Rows:** 1000
- **#Features:** 114
- **Target:** `grid_status`
- **#Views:**  1028 (as of October 28, 2025)
- **#Downloads:**  126 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is designed for simulating power grid operations, fault detection, and optimization in grid management. The dataset includes synthetic data related to power grid systems, such as load profiles, voltage and frequency stability metrics, power flow between grid nodes, and fault detection information. It is intended for use in research related to power grid optimization, fault detection, and grid efficiency improvement through advanced methods, including quantum computing-based optimization models.
- **Features:** <br>
timestamp:
Type: Datetime
Represents the timestamp when the data was recorded.
The dataset spans over a specified number of samples, recorded at hourly intervals.

load_node_1 to load_node_10:
Type: Float
Represents the load (in megawatts, MW) for each of the 10 grid nodes. The load is randomly generated between 50 and 500 MW.

fault_detected:
Type: Binary (0/1)
Indicates whether a fault was detected at a particular timestamp. A value of 1 means a fault is detected, while 0 means no fault.

voltage:
Type: Float
Represents the grid voltage (in per unit, pu). It is randomly generated between 0.95 and 1.05 pu to simulate normal grid conditions.

frequency:
Type: Float
Represents the grid frequency (in Hz). It is randomly generated between 49.5 and 50.5 Hz to simulate normal grid conditions.

power_flow_X_to_Y (for X, Y = 1 to 10):
Type: Float
Represents the power flow (in MW) between grid nodes X and Y. The values are randomly generated between 0 and 100 MW, simulating the transmission of power between different grid nodes.

grid_status:
Type: Binary (0/1) – Target Column
Represents the overall grid status, which is used as the target for classification tasks.
A value of 1 indicates that the grid is unstable due to either a fault detection, voltage, or frequency deviation outside acceptable limits.
A value of 0 means the grid is stable and functioning normally.

## 20. `iiot_smart_grid_dataset`
- **Description:** IoT-Enabled Smart Grid Dataset - Real-time power consumption, grid parameters, and IoT sensor data for ML modelin
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/iot-enabled-smart-grid-dataset</a>
- **Task:** Regression
- **#Rows:** 8737
- **#Features:** 19
- **Target:** `Energy_Efficiency_Score`
- **#Views:**  1262 (as of October 28, 2025)
- **#Downloads:**  302 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is designed for AI and ML-based energy efficiency optimization in IoT-enabled smart grids. It contains real-time and historical data on power consumption, voltage, current, grid frequency, reactive and active power, renewable energy generation, and environmental conditions. The dataset supports energy forecasting, load balancing, and anomaly detection using AI-driven predictive analytics.

The target variable, Energy_Efficiency_Score, quantifies the overall efficiency of power usage based on consumption patterns, renewable energy integration, and demand response events. This dataset is valuable for research on smart grid optimization, sustainable energy management, and AI-driven IoT applications.
- **Features:** <br>
Time-based energy data (hourly resolution for one year)
IoT sensor readings (temperature, humidity, weather conditions)
Smart grid parameters (power factor, grid frequency, voltage, reactive & active power)
Energy sources (grid, solar, wind, hybrid)
Demand response events (indicating peak load management strategies)
Target column: Energy_Efficiency_Score (scaled between 0-100)

## 21. `EV_Charging_Grid_Optimization_Categorical`
- **Description:** EV Charging Grid Optimization Dataset - AI-driven dataset for reducing power losses & voltage fluctuations in EV chargin
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/ev-charging-grid-optimization-dataset</a>
- **Task:** Classification
- **#Rows:** 1000
- **#Features:** 18
- **Target:** `Reduced Power Loss` and `Voltage Stability Improvement`
- **#Views:**  1271 (as of October 28, 2025)
- **#Downloads:**  221 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** The EV Charging Grid Optimization Dataset is designed to support research in AI-driven energy management for electric vehicle (EV) charging systems. This dataset captures real-time power grid parameters, charging session details, and AI-optimized charging predictions to minimize power losses and voltage fluctuations.
- **Features:** <br>
Key Features:
✅ Charging Station Data: Location, number of chargers, charging type (Conventional, Fast, V2G).
✅ Grid Parameters: Voltage level, current flow, power consumption, power loss, voltage fluctuation.
✅ EV Charging Details: Battery capacity, charging time, power demand, charging cost.
✅ AI-Optimized Variables: Predicted power demand, optimized charging power, grid stability score.
✅ Target Variables (Categorical):

Reduced Power Loss: "Low," "Medium," "High"
Voltage Stability Improvement: "Poor," "Moderate," "Excellent"

## 22. `HESS_Dataset`
- **Description:** Hybrid Energy Storage Dataset - Renewable Power Distribution & Efficiency Classification
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/hybrid-energy-storage-dataset/data</a>
- **Task:** Classification
- **#Rows:** 1000
- **#Features:** 10
- **Target:** `Optimization_Level`
- **#Views:**  836(as of October 28, 2025)
- **#Downloads:**  128 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:**
- **Features:** <br>
Features & Columns
Time-Based Data: Timestamped entries recorded at 5-minute intervals
Renewable Energy Inputs: Solar, wind, and grid power supply values (in kW)
Storage System Metrics: Battery SoC, supercapacitor charge, hydrogen production
Load & Power Distribution: Load demand, power supplied, and power loss
Optimization_Level (Target Variable):
"Low" → High power loss (> 4 kW)
"Medium" → Moderate power loss (2-4 kW)
"High" → Efficient system (≤ 2 kW power loss)

## 23. `smart_grid_stability_dataset`
- **Description:** Smart Grid Stability and Reliability Dataset - dataset for modeling grid performance, faults, and external factors
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/smart-grid-stability-and-reliability-dataset</a>
- **Task:** Classification
- **#Rows:** 1000
- **#Features:** 22
- **Target:** `grid stability` and `failure risk`
- **#Views:**  829(as of October 28, 2025)
- **#Downloads:**  149 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is designed to support the development of machine learning models for predicting the stability and reliability of smart grids. It includes synthetic data collected from various grid sensors, historical performance indicators, and external factors such as weather conditions and energy demand forecasts. The dataset is structured to facilitate research into early detection of grid disturbances, fault identification, and the optimization of smart grid operations.

Key attributes include real-time grid parameters such as voltage, current, power factor, and frequency, as well as performance metrics like outage frequency, mean time between failures (MTBF), and fault occurrences. Additionally, the dataset incorporates environmental variables such as temperature, wind speed, solar radiation, and energy demand forecasts, all of which are essential for assessing the grid’s performance under varying conditions.

The dataset also provides labels for grid stability (binary: stable or unstable) and failure risk (categorical: low, medium, or high), making it ideal for training and evaluating predictive models aimed at ensuring grid reliability and preventing potential breakdowns.
- **Features:** <br>
labels for grid stability (binary: stable or unstable) and failure risk (categorical: low, medium, or high)

## 24. `renewable_energy_rural_home_dataset`
- **Description:** Renewable Energy-Optimized Interior Design Dataset - Smart Spatial Planning & Energy Efficiency for Sustainable Rural Homes
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/renewable-energy-optimized-interior-design-dataset</a>
- **Task:** Regression
- **#Rows:** 500
- **#Features:** 26
- **Target:** `Energy_Efficiency_Score`
- **#Views:**  264 (as of October 28, 2025)
- **#Downloads:**  41 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** The Renewable Energy-Optimized Interior Design Dataset is a dataset designed to support research on integrating renewable energy technologies into interior design for rural homes. It includes various structural, environmental, and energy-related attributes to optimize spatial planning, thermal efficiency, and energy consumption using computational intelligence techniques.

This dataset provides valuable insights into energy-efficient housing by considering factors such as solar exposure, ventilation efficiency, lighting optimization, and the strategic placement of passive heating and cooling elements. The target variable, Energy Efficiency Score, quantifies the overall sustainability and effectiveness of interior designs in rural homes.
- **Features:** <br>
Structural Information: House size, room layout, wall material, roof type, window count, and orientation.
Renewable Energy Data: Solar panel area, solar exposure, energy generation, and battery storage.
Environmental & Thermal Factors: Indoor/outdoor temperatures, airflow patterns, humidity levels, and ventilation efficiency.
Optimization Metrics: Energy savings percentage, lighting efficiency, thermal regulation, and computed Energy Efficiency Score.
This dataset is suitable for machine learning, optimization algorithms, and smart home energy research aimed at promoting sustainable housing development in rural areas.

## 25. `power_marketing_dataset`
- **Description:** Personalized Energy Marketing Analytics Dataset - User-level energy data for ML-driven marketing and consumption forecasting
- **Source:** <a href="">https://www.kaggle.com/datasets/ziya07/personalized-energy-marketing-analytics-dataset</a>
- **Task:** Regression
- **#Rows:** 1000
- **#Features:** 13
- **Target:** `Energy Usage Reduction (%)`
- **#Views:**  501 (as of October 28, 2025)
- **#Downloads:**  100 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** The SmartPowerML dataset is a user-level dataset designed to simulate the operation of a Power Marketing Management Platform (PMMP) enhanced by machine learning. It captures detailed information on users’ electricity consumption behaviors, demographics, pricing plans, and marketing engagement. The dataset supports use cases such as consumption forecasting, dynamic pricing strategy development, user segmentation, and targeted marketing in the energy sector.

This dataset is ideal for researchers and developers looking to build or evaluate machine learning models in the fields of energy analytics, smart grid management, and personalized marketing.
- **Features:** <br>
User Demographics: Includes age, location, and household size.
Electricity Consumption: Daily, monthly, peak, and time-of-day usage patterns.
Marketing Engagement: Tracks user interaction with marketing campaigns.
Pricing Plans: Indicates user enrollment in dynamic or flat rate plans.
Incentive Participation: Flags users who opted into energy-saving incentive programs.
Behavioral Metrics: Contains user engagement rates and energy usage reduction percentages.
Target Variable: Energy Usage Reduction (%) to support regression modeling and impact analysis.

## 26. `client_data`
- **Description:** Customer Churn Analysis Dataset - BCG Gamma Customer Churn Prediction job simulation on Forage
- **Source:** <a href="">https://www.kaggle.com/datasets/chayanroy3/customer-churn-analysis-dataset</a>
- **Task:** Classification
- **#Rows:** 14606
- **#Features:** 25
- **Target:** `churn`
- **#Views:**  230 (as of October 28, 2025)
- **#Downloads:**  19 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset is derived from the BCG Gamma Customer Churn Simulation on Forage, designed to help analysts understand and predict customer attrition. It contains detailed customer behavioral data, transaction history, and engagement metrics, making it ideal for churn prediction models, exploratory data analysis (EDA), and machine learning applications.
- **Features:** <br>
● id = client company identifier
● activity_new = category of the company’s activity
● channel_sales = code of the sales channel
● cons_12m = electricity consumption of the past 12 months
● cons_gas_12m = gas consumption of the past 12 months
● cons_last_month = electricity consumption of the last month
● date_activ = date of activation of the contract
● date_end = registered date of the end of the contract
● date_modif_prod = date of the last modification of the product
● date_renewal = date of the next contract renewal
● forecast_cons_12m = forecasted electricity consumption for next 12 months
● forecast_cons_year = forecasted electricity consumption for the next calendar year
● forecast_discount_energy = forecasted value of current discount
● forecast_meter_rent_12m = forecasted bill of meter rental for the next 2 months
● forecast_price_energy_off_peak = forecasted energy price for 1st period (off peak)
● forecast_price_energy_peak = forecasted energy price for 2nd period (peak)
● forecast_price_pow_off_peak = forecasted power price for 1st period (off peak)
● has_gas = indicated if client is also a gas client
● imp_cons = current paid consumption
● margin_gross_pow_ele = gross margin on power subscription
● margin_net_pow_ele = net margin on power subscription
● nb_prod_act = number of active products and services
● net_margin = total net margin
● num_years_antig = antiquity of the client (in number of years)
● origin_up = code of the electricity campaign the customer first subscribed to
● pow_max = subscribed power
● churn = has the client churned over the next 3 months

## 27. `PowerCo's Customer DataSet`
- **Description:** This Dataset contains two energy pricing and client data datasets, which can be used for various analytical and predictive modeling tasks.
- **Source:** <a href="">https://www.kaggle.com/datasets/gatabhjsbaj/powercos-customer-company-dataset</a>
- **Task:** Classification
- **#Rows:** 
- **#Features:** 
- **Target:** `churn`
- **#Views:**  381 (as of October 28, 2025)
- **#Downloads:**  61 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:**
File Name: client_data.csv
Description: The Client Data dataset includes detailed information about clients and their energy consumption patterns. This data can be used to understand customer behavior and preferences, as well as to tailor services and offers.
Rows: 14,606
Columns: 26

File Name: data_for_predictions.csv
Description:The Data for Predictions dataset is designed for building predictive models. It includes a variety of features that can be used to predict future consumption patterns, pricing, or other key metrics.
Rows: 8,163
Columns: 64
- **Features:** <br>
client_data:
id: Unique identifier for each client.
channel_sales: The sales channel through which the client was acquired.
cons_12m: Total electricity consumption over the last 12 months.
cons_gas_12m: Total gas consumption over the last 12 months.
cons_last_month: Electricity consumption in the last month.
date_activ: The date the client activated their service.
date_end: The date the client’s service ended or is scheduled to end.
date_modif_prod: The date the client's product was last modified.
date_renewal: The date the client’s service is due for renewal.
forecast_cons_12m: Forecasted electricity consumption for the next 12 months.
forecast_cons_year: Forecasted electricity consumption for the next year.
forecast_discount_energy: Expected discount on energy prices.
forecast_meter_rent_12m: Forecasted meter rental costs for the next 12 months.
forecast_price_energy_off_peak: Expected off-peak energy prices.
forecast_price_energy_peak: Expected peak energy prices.
forecast_price_pow_off_peak: Expected off-peak power prices.
has_gas: Indicates whether the client has a gas supply (Yes/No).
imp_cons: Important consumption metrics.
margin_gross_pow_ele: Gross margin from power electricity.
margin_net_pow_ele: Net margin from power electricity.
nb_prod_act: Number of active products/services the client has.
net_margin: Net margin for the client.
num_years_antig: Number of years the client has been with the company.
origin_up: Origin of the client, indicating the initial source or method of acquisition.
pow_max: Maximum power consumption.

data_for_predictions:
id: Unique identifier for each record.
cons_12m: Total electricity consumption over the last 12 months.
cons_gas_12m: Total gas consumption over the last 12 months.
cons_last_month: Electricity consumption in the last month.
date_activ: The date the client activated their service.
date_end: The date the client’s service ended or is scheduled to end.
date_modif_prod: The date the client's product was last modified.
date_renewal: The date the client’s service is due for renewal.
forecast_cons_12m: Forecasted electricity consumption for the next 12 months.
forecast_cons_year: Forecasted electricity consumption for the next year.
forecast_discount_energy: Expected discount on energy prices.
forecast_meter_rent_12m: Forecasted meter rental costs for the next 12 months.
forecast_price_energy_off_peak: Expected off-peak energy prices.
forecast_price_energy_peak: Expected peak energy prices.
forecast_price_pow_off_peak: Expected off-peak power prices.
has_gas: Indicates whether the client has a gas supply (Yes/No).
imp_cons: Important consumption metrics.
margin_gross_pow_ele: Gross margin from power electricity.
margin_net_pow_ele: Net margin from power electricity.
nb_prod_act: Number of active products/services the client has.
net_margin: Net margin for the client.
num_years_antig: Number of years the client has been with the company.
origin_up: Origin of the client, indicating the initial source or method of acquisition.
pow_max: Maximum power consumption.
target: Target variable for prediction (e.g., client churn, consumption increase).

## 28. `market_pipe_thickness_loss_dataset`
- **Description:** Predictive maintenance oil and gas pipeline data - 1000 pipeline dataset in oil and gas sector used predictive maintenance
- **Source:** <a href="">https://www.kaggle.com/datasets/muhammadwaqas023/predictive-maintenance-oil-and-gas-pipeline-data</a>
- **Task:** Classification
- **#Rows:** 1000
- **#Features:** 10
- **Target:** `Maintenance_Required`
- **#Views:**  3574(as of October 28, 2025)
- **#Downloads:**  668(as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This dataset contains 1,000 samples of pipeline data collected from the oil and gas industry, intended for use in predictive maintenance modeling. Each record represents sensor and operational data from pipelines, with corresponding labels indicating whether maintenance was required.

The goal is to develop models that can predict potential failures or maintenance needs before they occur, ensuring pipeline safety, reducing downtime, and minimizing operational costs.
- **Features:** <br>
Pipe Size: Diameter of the pipeline
Thickness: Measured wall thickness of the pipe
Material: Type of material used (e.g., steel, composite)
Maximum Pressure: Peak pressure experienced (psi)
Temperature: Internal fluid temperature (°C)
Corrosion Impact Percentage: Estimated corrosion level (%)
**Thickness Loss: **Loss of wall thickness due to wear or corrosion
Material Loss Percentage: Percentage of overall material loss
Year Times: Age or time in service (years)
**Conditions: **Operational condition category (Normal, Moderate, Critical)
Maintenance_Required (Target): Binary label (1 = maintenance needed, 0 = no maintenance)

## 29. `pipe_thickness_loss_dataset`
- **Description:** Pipeline dataset in oil and gas sector/fertilizer - Dataset about pipelines that used in oil and gas sector and also in fertilizers
- **Source:** <a href="">https://www.kaggle.com/datasets/muhammadwaqas023/pipeline-dataset-in-oil-and-gas-sector</a>
- **#Rows:** 1000
- **#Features:** 13
- **Target:** `Condition`
- **#Views:**  2396 (as of October 28, 2025)
- **#Downloads:**  408 (as of October 28, 2025)
- **#Citations:**
- **Additional Description:** This pipeline dataset used in different sector like oil and gas sector and fertilizers. This dataset is about 1000 pipeline dataset with different pipe size, materials, material grade, corrosion impact etc
- **Features:** <br>
Pipe_ID - ID
Pipe_Size_mm - Pipe size
Diameter_mm - Diameter of pipe
Thickness_mm - Thickness of pipe
Material - Material of pipe
Strength_MPa - Strength of pipe
Grade - Grade of pipe
Max_Pressure_Bar - Maximum pressure
Corrosion_Impact_Percent - Corrosion impact
Thickness_Loss_mm - Thickness loss percentage
Material_Loss_Percent - 
Time_Years - 
Temperature_C - 
Condition - 
---