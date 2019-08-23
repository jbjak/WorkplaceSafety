# WorkplaceSafety
AI based - Custom Vision Workplace Safety detection system.

# Use Case
Ability to detect vision-based compliance. In a environment where safety is important for workforce to work there are Compliance rules in place to wear proper gear to safe guard the environment and keep the humans working safe and secured. For example, depending on what manufacturing company the human causality is one thing every one wants to avoid. So, they insist on wearing proper vest, hard hats and safety glass or lab coats and glass to protect. In some cases, may be mask and complete covered suits for chemical spills etc. So, the idea here is to detect human and then see if they are wearing Vest, Hard hats and Safety glass. Usually in manufacturing there are lines where folks can walk and that would be the next future work. Ability to detect humans and compliance and alert management with reporting and Realtime alerts. Also, ability to detect forklift and alert humans on the way to the fork lift operator. The system just not only detect the objects but also ability to store the information for further reporting and analysis.
For example: usually the plants has to provide yearly or quarterly report to OSHA auditors to make sure if there is human causality and what actions were taken not repeat it. Having the picture when the objects were detected and when not detected is super helpful to analyze the data by the auditors. That makes it very simple and easy for auditors. But the main purpose is the plant or factory can be running and there is no downtime or pull work force to go through the auditing process. Usually there is a down time when auditing happens which in this case will reduce and increase productivity and uptime.  
It is necessary to detect and provide a report and also it is important to store the data for historical purpose to able to do auditing and also learn from the data. The historical data can be combined with other productivity data and find insights as well. Mostly likely pushing the data in data lake make sense. It is also very important to know how the system is performing. So we need to collect the telemetry and store in Azure SQL and Blob for further processing. We can generate monthly report or weekly report on how many compliance issues were raised. We can also analyze the data and find if the model is performing well or find where is it not.
The scenario can be customized to other use cases like hospitals, chemical plant and various other heavy machinery and mining industries as well.

#Architecture
![alt text](https://github.com/balakreshnan/WorkplaceSafety/blob/master/WorkplaceSafetyarch.jpg "Architecture")
