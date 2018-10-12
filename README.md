# Distributed Disaster Impact Analysis

## The Issue We Address
We strive to restrict the impact that a natural disaster has on the population by means of helping relief organisation better serve the distressed population. Usually NGOs and or Governments have to spend resources and time to do an initial survey of affected areas (as in the the case of kerala flood). If immediate and accurate heat map of damage and threats can be generated, it can result in better allocation of relief resources as well as quicker rescue efforts which could save lives.

## Our Proposed Solution

###  Harnessing The Power Of The Masses
Creating an impact analysis is usually a difficult process which usually involves a lot of groundwork. We plan to automate this process by collecting and processing self reported data from the people themselves which can then be used to create a heat map showcasing the extent of damage across the city/state.
The solution needs to be accessible in order to paint an accurate picture of the impact of the disaster. This mandates an easy to use interface as well as robustness in the lack of or limited availability of internet. The system will include the features described below. 

### Portal 
A web portal will be created where people can self report a damage/threat score in their location or that of their friends and family. To prevent intentional/ unintentional misrepresentation of damage, an option to upload images can be provided. These images can then be verified manually or automatically verified using data of disasters in the past. If not all, at least some of the people will be willing and able to upload images.

### SMS
In order to be accessible to the masses, the solution should be able to accommodate the technically challenged as well. To ensure equal opportunity to report damage, people can be provided with the option to report via sms.

### Processing The Information
In order to make more sense of the self reported scores, other available data of the region can be presented alongside them to enhance the damage metric proposed above. This could include incorporating:
- Distinction of areas as urban and rural to accurately judge the density of reports (urbans areas might generally have a higher number of reports and thus the must be accounted for.)
- The ratio of active users to the number of expected users. Severely affected areas will have a sparse proportion of active users indicating either damage to cell towers which in turn indicates substantial damage or power outage in the region which is also an emergency. 
- Existing weather data for regions

## Tech We Plan To Use:
- Twillo API <SMS> to urge users to self report the conditions with guidelines on scores, and use Twillo to obtain the data required for the map(https://www.twilio.com/blog/2011/05/how-to-create-a-simple-sms-voting-system-using-php.html).
- Microsoft Azure compute VM to serve as the server for the project.
